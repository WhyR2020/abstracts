# Text Mining Techniques on Polish National News

Authors: [Michel Voss](https://www.linkedin.com/in/michel-voss-206683172/)

### How to use the data
To use those .srt file in R install a package named subtools. It allows to import .srt files into R.

Download the package with the following command:
devtools::install_github("fkeck/subtools")

To import the data I used the following code:

```r
read_plus <- function(flnm) {
    read_subtitles(flnm) %>%
        mutate(date = as.Date(str_extract(tools::file_path_sans_ext(basename(flnm)), "[0-9]{4}-[0-9]{2}-[0-9]{2}"), format="%Y-%m-%d"))
}


tvp <- list.files(getwd(),
               pattern = "*.srt",
               full.names = T) %>%
    map_df(~read_plus(.))
```
