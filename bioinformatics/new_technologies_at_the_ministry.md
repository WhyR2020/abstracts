# Differential equations or: how we learned to stop worrying and tackle the coronavirus modeling crisis in Poland

Authors: Klaudiusz Witczak (Ministry of Health) 

# Description 

The novel SARS-CoV-2 coronavirus has taken us all by suprise. At the Ministry of Health of the Republic of Poland, we resorted to the classical compartmental models used in the modeling of infectious diseases.

Having built upon the widely popular SEIR epidemiological model, we extended its structure to include the information about the usage of medical resources, such as hospital beds and mechanical ventilators.

Due to the rather peculiar course of the coronavirus pandemic in Poland, namely no visible exponential growth phase, as well as non-pharmacological interventions implemented by the government in its relatively early stage, the model required an enhanced parameter estimation procedure. Furthermore, the disparities of the coronavirus spread at the regional level in Poland entailed the necessity to develop a metapopulation model in which 16 distinct regional models for the voivodeships were combined.

Although several different epidemiological models are at the decision-makers? disposal, the model proposed by the Department of Analyses and Strategy emerges as a clear winner in terms of the execution time. Given its deterministic nature, as opposed to the stochastic, let alone multi-agent models, the model results are generated within half an hour of the arrival of new data with the utilization of parallel computing in R programming language.