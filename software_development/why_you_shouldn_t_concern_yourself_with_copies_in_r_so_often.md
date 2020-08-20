# Why you shouldn’t concern yourself with copies in R (so often)

Authors: Mateusz Bakala (Warsaw University of Technology) 

# Description 

Copying objects in R is actually assigning value associated with one variable name to the other variable name. As (almost) everything in R is an object, you could expect this behaviour to be universal. However, this is not.

I want to show you how R is programmed to efficiently handle cases where copying is not necessary – and why you shouldn’t end up overoptimizing every bit of code.