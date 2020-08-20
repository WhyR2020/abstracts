# What’s new in DrWhy.AI? (2020)

Authors: Hubert Baniecki(Warsaw University of Technology)Przemyslaw Biecek

# Description 

DrWhy.AI [1] is the collection of tools for eXplainable AI (XAI). It's based on shared principles and simple grammar for exploration, explanation and examination of predictive models [2]. The main concept implies using model-agnostic post hoc explanations to visualize black-box model complex behaviour.



I will start this talk by providing background for why XAI has become an integral part of the model development process. Then, I will briefly showcase several new additions to the DrWhy.AI family; R packages implementing various ideas that enhance the XAI toolkit. These include: 



- xai2cloud - automated deployment of the model explainer into the cloud,

- triplot - instance and data level explanations for the groups of correlated features,

- corrgrapher - graph of variable correlations, complemented by partial dependence profiles,

- arenar - XAI dashboard to explore and compare multiple models,

- fairmodels - flexible tool for bias detection, visualization, and mitigation,

- vivo - variable importance measure based on partial dependence profiles,

- treeshap – fast SHAP values calculation for tree ensemble models in R.



Last but not least, I shall bring to light the Python implementation of moDel Agnostic Language for Exploration and eXplanation (DALEX [3]).



[1] https://github.com/ModelOriented/DrWhy

[2] https://pbiecek.github.io/ema/

[3] https://github.com/ModelOriented/DALEX