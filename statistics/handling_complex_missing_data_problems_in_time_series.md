# Handling complex missing data problems in time series

Authors: Steffen Moritz (Institute for Data Science, Engineering, and Analytics, TH Köln) Thomas Bartz-Beielstein

# Description 

Missing data is a common problem in time series. As an example, when sensors are used for data recording, missing values can be caused by multiple issues. There can be problems with the data recording itself (e.g. defect sensors), with the data transmission (e.g. internet outages) or with the data processing (e.g. faulty program code).



These missing values often complicate further processing and analysis steps. Replacing the missing values with reasonable values ('imputation') is one way to mitigate this problem. Hereby it is crucial to choose the right algorithm for the data at hand (as it is for most machine learning related tasks).



Sometimes the solution for these time series missing data problems is surprisingly easy and a simple linear interpolation will already give reasonably good results. This is often the case, with short gaps (only few successive NAs) in relative to the measuring interval slow-moving processes. E.g. the water temperature in a big lake won't change significantly from one minute to another. Additionally, these changes will happen without big offsets in a very continuous way.



But there are also more complex cases: long periods of missing data, fast-moving processes, noncontinuous changes, strong periodicities ,and seasonalities. In these cases, a simple interpolation usually won’t provide good imputation results.



This talk looks at how these problems can be approached for (univariate) time series and how the imputeTS R package can help here. The imputeTS package offers several different imputation functions for (univariate) time series. Some of the more advanced functions the package provides like 'Seasonally Decomposed Imputation' or 'Kalman Smoothing on Structural Time Series Models' can be good choices for these more complex imputation problems. 



The Goal of the talk is to give a short intro into imputeTS and its usage for handling missing data problems that are not straightforward to solve. 



Keywords: Time Series Imputation, Imputation, Time Series, Missing Data, Preprocessing

