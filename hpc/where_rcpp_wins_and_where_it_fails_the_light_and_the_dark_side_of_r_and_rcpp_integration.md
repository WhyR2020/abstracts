# Where Rcpp wins and where it fails - the light and the dark side of R and Rcpp integration

Authors: Jadwiga Słowik

# Description

It is challenging to write high performing software in a high-level and interpretable programming language as R. Fortunately, the Rcpp package provides C++ interface for R internals. It allows the usage of a high performant programming language, simultaneously providing a high-level interface familiar for R users.  However, Rcpp has some limitations which require specific solutions, e.g. memory management. In my presentation, I will showcase these problems and describe potential solutions. 