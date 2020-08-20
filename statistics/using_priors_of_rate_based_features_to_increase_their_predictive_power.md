# Using priors of rate-based features to increase their predictive power

Authors: Adrian Foltyn (Ocado Polska) 

# Description 

Classic machine learning often encounters the problem of rate-based features (e.g. average incidence of an event of rejecting a substitute product by an online retailer's customer) being based on very small samples. I will show how modifying the values  of such predictors with well-crafted priors can enhance predictive power of a model used to predict the aforementioned rate of rejections. The prototype has been built both in R and Python.