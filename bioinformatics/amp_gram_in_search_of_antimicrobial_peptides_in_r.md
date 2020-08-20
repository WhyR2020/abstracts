# AmpGram: in search of antimicrobial peptides in R

Authors: Katarzyna Sidorczuk (University of Wroclaw) Michal Burdukiewicz, Dominik Rafacz, Filip Pietluch, Jaroslaw Chilimoniuk, Stefan Rödiger, Przemyslaw Gagat

# Description 

Antimicrobial peptides (AMPs) are ancient molecules that participate in host defence. Interestingly, they do not display consensus sequences but do share some common features, such as positive charge, hydrophobicity, and amphipathicity. Due to the current drastic loss of antibiotic effectiveness, AMPs are an important alternative, especially against multidrug resistant bacteria. Therefore, we developed AmpGram - a new tool for AMP prediction to identify the best AMP candidates without performing expensive experiments. In contrast to existing software, AmpGram is suitable for analysis of longer AMPs and proteome screening. 

AmpGram employs n-gram analysis to reveal amino acid motifs associated with the presence or absence of antimicrobial properties and encode information into informative features suitable for the machine learning algorithm. Prediction is performed with two-layered random forests implemented using the ranger package. 

To ensure reproducibility, the AmpGram model was built with drake and renv packages. AmpGram is available as a web server for multiple query sequences and as an R package. The easy to use standalone implementation is meant to be used for proteomic screening. 

