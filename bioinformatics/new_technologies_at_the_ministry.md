# New Technologies at the Ministry

Authors: Piotr Nowosielski (Ministry of Health) Klaudiusz Witczak

# Description 

During the last decade, the R programming language has become one of the established tools for statistical analyses, encompassing the big data analytics. Some of the current challenges the data-driven world is facing are the interpretability and accessibility of the results, and the possibility to convey them in a compelling way.

Having all those aspects in mind, five distinct web apps were developed at the Ministry of Health of the Republic of Poland using Shiny framework as part of the analysis of the most severe health problems in the country. The entire project pipeline from coming up with the idea to the successful publication of the web app will be explained during the presentation. 

The web applications contain a comprehensive overview of a given health problem based on a huge extent of data (billions of medical services provided to millions of patients in years 2009–2018), including the epidemiological aspects, treatment accessibility, survival and forecasting models, as well as the care pathways analysis. Such an evidence-based approach with complex results presented in a clear way allows for a better decision-making process and helps the policymakers draw practical conclusions concerning health system’s management.





The novel SARS-CoV-2 coronavirus has taken us all by suprise. At the Ministry of Health of the Republic

of Poland, we resorted to the classical compartmental models used in the modeling of infectious diseases.

Having built upon the widely popular SEIR epidemiological model, we extended its structure to include the

information about the usage of medical resources, such as hospital beds and mechanical ventilators.

Due to the rather peculiar course of the coronavirus pandemic in Poland, namely no visible exponential

growth phase, as well as non-pharmacological interventions implemented by the government in its relatively

early stage, the model required an enhanced parameter estimation procedure. Furthermore, the disparities

of the coronavirus spread at the regional level in Poland entailed the necessity to develop a metapopulation

model in which 16 distinct regional models for the voivodeships were combined.

Although several different epidemiological models are at the decision-makers’ disposal, the model proposed

by the Department of Analyses and Strategy emerges as a clear winner in terms of the execution time. Given

its deterministic nature, as opposed to the stochastic, let alone multi-agent models, the model results are

generated within half an hour of the arrival of new data with the utilization of parallel computing in R

programming language.