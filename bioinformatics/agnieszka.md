# Non-stationary pharmacokinetics of caspofungin in ICU patients

Authors: Agnieszka Borsuk-De Moor (1), Justyna Sysiak-Sławecka (2), Elżbieta Rypulak (2), Michał Borys (2), Paweł Piwowarczyk (2), Grzegorz Raszewski (3), Dariusz Onichimowski (4), Mirosław Czuczwar(2),  Paweł Wiczling (1)

Institution: 

- (1) Department of Biopharmaceutics and Pharmacodynamics, Medical University of Gdańsk, Al. Gen. Hallera 107, 80-416 Gdańsk, Poland,
- (2) 2nd Department of Anaesthesiology and Intensive Therapy, Medical University of Lublin, Lublin, Poland, 
- (3) Department of Physiopathology, Institute of Rural Health, Lublin, Poland, 
- (4) Department of Anesthesiology and Intensive Care, Faculty of Medical Sciences, University of Warmia and Mazury, Olsztyn, Poland

# Description

Introduction: Caspofungin is an echinocandin antifungal agent widely used in treating invasive fungal infections in the intensive care unit (ICU) setting. Critically ill patients have altered physiology and undergo multiple medical procedures, which can affect the pharmacokinetics of drugs. Standard dosing of caspofungin in critically ill patients has been reported to result in lower drug exposure, which can lead to subtherapeutic AUC0–24/MIC ratios [1,2].

Objectives: The aim of the study was to investigate the population pharmacokinetics of caspofungin in a cohort of 30 ICU patients with a suspected invasive fungal infection, with a large proportion of patients requiring extracorporeal therapies including ECMO and CRRT. We also explored the influence of patient's characteristics and vital parameters on caspofungin pharmacokinetics and assessed drug exposure.

Methods: It was a prospective observational study conducted in adult critically ill patients admitted to ICU due to severe sepsis requiring broad-spectrum antibiotics with a high risk of fungal infection. Caspofungin was administered as empirical antifungal therapy 70 mg i.v. on the first day and 50 mg i.v. on the consecutive days once daily and the concentrations were measured after 3 subsequent doses. Recorded patient's characteristics included sex, age, weight, height, SOFA score, procalcitonin (PCT) concentration, dialysis dose, ultrafiltration rate (UF), extravascular water index (ELWI), cardiac output, albumin, and total plasma protein concentrations. Population pharmacokinetic data were analysed by nonlinear mixed-effects modeling in NONMEM (version 7.3, Icon Development Solutions, Ellicott City, Md, USA), GNU Fortran 95 compiler (GCC 4.6.0) and Wings for NONMEM (WFN741, http://wfn.sourceforge.net). R computing environment (R Core Team 2019) was used for data processing and visualization.

Results: The pharmacokinetics of caspofungin was described by 2-compartment model. A particular drift of individual CL and V1 values with time was discovered and described by including three separate typical values of CL and V1 in the final model. The typical CL values at day one, two and three were 0.563 L/h (6.7 %RSE), 0.737 L/h (6.1 %RSE) and 1.01 L/h (9.1 %RSE), respectively. The change in parameters with time was not explained by any of the recorded covariates. The drug exposure in the analyzed population was lower than the minimal value associated with efficacy [1]. Increasing clearance with subsequent doses results in a clinically relevant decrease in caspofungin exposure (>20%). The use of ECMO, CRRT, albumin concentration, and other covariates did not significantly affect caspofungin pharmacokinetics. 

Conclusions: The pharmacokinetics of caspofungin in our study was non-stationary as clearance and volume of the central compartment were changing over 72-h period of the study. However, it is possible that non-stationarity of caspofungin pharmacokinetics is characteristic for the studied group of patients (with sepsis pathophysiology together with invasive treatment such as ECMO or CRRT). Additional pharmacokinetic studies are urgently required to assess the possible lack of acquiring steady-state and suboptimal concentrations of the drug in critically ill patients.

References:

- [1] van der Elst KCM, Veringa A, Zijlstra JG, Beishuizen A, Klont R, Brummelhuis-Visser P, Uges DRA, Touw DJ, Kosterink JGW, van der Werf TS, Alffenaar J-WC. 2016. Low caspofungin exposure in patients in the Intensive Care Unit. Antimicrob Agents Chemother 61:AAC.01582-16.
- [2] Pérez-Pitarch A, Ferriols-Lisart R, Aguilar G, Ezquer-Garín C, Belda FJ, Guglieri-López B. 2018. Dosing of caspofungin based on a pharmacokinetic/pharmacodynamic index for the treatment of invasive fungal infections in critically ill patients on continuous venovenous haemodiafiltration. Int J Antimicrob Agents 51:115–121.
