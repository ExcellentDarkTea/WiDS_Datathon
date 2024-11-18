# WiDS_Datathon



This repository contains the code and models developed for the WiDS Datathon 2024 Challenge #2



https://www.kaggle.com/competitions/widsdatathon2024-challenge2



The WiDS Datathon 2024 focuses on a prediction task using a roughly 19k record dataset (split into training and test sets) representing patients and their characteristics (age, race, BMI, zip code), their diagnosis and treatment information (breast cancer diagnosis code, metastatic cancer diagnosis code, metastatic cancer treatments etc.), their geo (zip-code level) demographic data (income, education, rent, race, poverty etc), as well as climate data that tie health outcomes to external conditions. Each row in the data corresponds to a single patient and her Diagnosis Period. 



***\*Your task\**** is to predict the patient's Metastatic Diagnosis Period in the Test Dataset using the provided characteristics and information about the patient. Some data may be messy to reflect real-world data. Our expectation is that you will address messy data issues through appropriate means.



***\*Target\****: 



metastatic_diagnosis_period: This is the period (in days) in which metastatic cancer was diagnosed. Specifically, it is relative to the fact that breast cancer has already been diagnosed. Then the breast cancer is further diagnosed as having become metastatic cancer.
