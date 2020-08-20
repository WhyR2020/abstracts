# A machine-learning approach to survival time-event modeling and predicting with R

Authors: Lubomír Štepánek(Department of Biomedical Statistics, Institute of Biophysics and Informatics, First Faculty of Medicine, Charles University, Prague, Czech Republic & Department of Statistics and Probability, Faculty of Informatics and Statistics, University of Economics, Prague, Czech Republic)Filip Habarta, Stanislav Kovác, Filip Pazdírek

# Description 

Survival analysis is a very well established method in applied biostatistics and is popularly used whenever it is at least a bit possible. Predictions of both the fact whether an event of interest does occur and when exactly occurs for a given individual based on values of selected independent variables are usually modeled using hazard functions and derived survival time-event curves. That requires to estimate one dependent time-event survival variable predicting when and even whether an individual could experience the event of interest.



In this work, we propose a new approach to predicting if and when an event of interest will likely happen to a subject. We assumed a logic of modeling the event of interest based on a bunch of predictors by the Cox proportional hazard model. However, we decomposed the dependent, two-dimensional survival time-event variable into its components by which we could omit the statistical assumptions required to be met by the Cox model. The first component is a categorical binary variable depicting whether an event of interest is about to be evinced, based on predictors, which was treated as a classification machine-learning task. The second component is a continuous numeric variable estimating times when the event of interest occurs (if so) given the predictors' values, considered as a regression machine-learning task. The resulted classification and regression tasks were modeled with R using machine-learning algorithms such as naïve Bayes classifiers, support vector machines, decision trees, random forests, and neural networks. The introduced approach's performance was compared to the classic Cox proportional hazard model's predictions using real-world medical data of patients with stomach cancer.



The machine-learning modeling of survival time-event variable, decomposed into its binary event-vs-no-event part, and continuous exact-event-times part seems to be a promising alternative to predictions based on the Cox hazard model. After its other performance inspection and working out of an appropriate mathematical background, the proposed approach could be a topic for a new R package development.

