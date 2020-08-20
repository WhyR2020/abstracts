# Still parsing User Agent strings for your models? Use this instead!

Authors: Sergey Mastitsky (Aviva UK) 

# Description 

User Agent strings (UAS) are header fields in HTTP requests used to identify the device and browser making the request.  By parsing a UAS, one can extract many data points (type and make of the visitor’s device, operating system and its version, etc.) that can be used as valuable inputs for Machine Learning models (e.g., encoding customer affluence and tech savviness).  However, UAS are lacking standardised formatting, which makes their parsing a formidable task, requiring high-quality regular expressions.  In addition, the variety of values one can encounter in UAS is astronomically large and constantly growing, making one-hot encoding of the respective features impractical.  In this talk, I will demonstrate how these problems can be overcome by embedding UAS into a low-dimensional space using a Natural Language Processing technique.  I will also illustrate the use of UAS embeddings in unsupervised and supervised learning applications, with examples of implementation in R.