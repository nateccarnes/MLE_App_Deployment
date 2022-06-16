# Analysis and Deployment of Capstone Project for UCSD Machine Learning Engineering Bootcamp

This project aims to predict hospital readmissions (within 30 days) for patients with mental, behavioral, and developmental disorders. The data is from the Healthcare Cost and Utilization Project (HCUP) National Readmission Database (NRD) year 2018; the data will not be shared in this repository because the HCUP Data Use Agreement restricts the sharing of this sensitive database to protect the privacy of patients and partners. If the user obtains access to HCUP data for themselves, the code in this repository can take aggregated and cleaned input data, prepare it, preprocess it, train a DNN model, evaluate the model, and make predictions. HCUP data can be purchased from the HCUP Central Distributor using the following link.

https://www.distributor.hcup-us.ahrq.gov/

A DNN model was fit to the training data and yielded binary classification metrics that, despite extensive hyperparamter tuning and model/data refinement, indicated modest but acceptable fit. Nonetheless, this prediction function may be of substantial real-world use for clinicians to assess the likelihood of readmission for their patients. As such, an we app was developed and deployed on streamlit permitting users to easily utilize this prediction function. This repository contains the code and dependencies for this web app. The web app can be accessed at TBD.
