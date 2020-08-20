# Count data analysis with countfitteR.

Authors: Jaroslaw Chilimoniuk (University of Wroclaw) Alicja Gosiewska, Jadwiga Slowik, Romano Weiss, P. Markus Deckert, Stefan Rödiger, Michal Burdukiewicz

# Description 

Count data is one of the most common data types occurring in multiple fields. This kind of data is often assumed to follow the Poisson distribution. However, it could deviate from the Poisson distribution by possessing excess zeros (zero-inflation), variance larger than the mean (overdispersion), or both. The selection of an incorrect distribution model underlying the data introduces a bias to the estimation of the mean and variance of counts. 

Count data occurs in precision medicine. An example is DNA double-strand breaks, a highly specific and sensitive molecular biomarker for monitoring DNA damage in cancer, aging research, and in the evaluation of drug efficacy. 

To simplify the selection of the most appropriate distribution for these types of data, we have developed a new tool - countfitteR. It offers multiple functions for a comprehensive automated evaluation of distribution models for count data. Although it was designed for the analysis of focus data in biomedical applications, it can also be used in other areas where overdispersed counting data is prevalent.

countfitteR is available as an R package and a webserver.