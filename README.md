# Classifying-Risks-Predictive-Modelling-for-Hospital-Readmissions

Overview
This repository contains the implementation of a machine learning model to predict hospital readmissions for diabetic patients. The analysis is based on data from the UC Irvine Machine Learning Repository and involves various machine learning techniques to identify key factors influencing readmission rates.

Dataset
The dataset comprises 101,766 patient records with 50 features, focusing on demographic details, patient medical history, and the outcome of hospital visits. Key attributes include patient number, race, gender, age, weight, admission details, diagnostic codes, and readmission status.

Exploratory Data Analysis (EDA)
The initial phase involved cleaning the dataset, handling missing values particularly in the 'weight' feature, and performing exploratory data analysis to understand the distribution and relationship of features.

Feature Engineering
We conducted feature engineering to transform and create new features to better represent the underlying processes affecting readmissions, which includes encoding categorical variables and imputing missing values using a Random Forest Regressor.

Model Building
We experimented with several machine learning models:

Logistic Regression
Naive Bayes
K-Nearest Neighbors (KNN)
Decision Trees
Ensemble methods like Random Forest and XGBoost
The XGBoost model performed the best with an accuracy of 64%.

Results
The final model provides insights into the likelihood of a patient being readmitted based on their medical history and current hospital stay. These predictions can help healthcare providers improve patient care and reduce unnecessary readmissions.



