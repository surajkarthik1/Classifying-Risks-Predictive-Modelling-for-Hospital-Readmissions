# Classifying-Risks-Predictive-Modelling-for-Hospital-Readmissions

Overview:
This repository hosts a predictive modeling project aimed at forecasting hospital readmissions among diabetic patients. The project utilizes data from the UC Irvine Machine Learning Repository, applying various advanced machine learning algorithms to uncover the primary drivers behind patient readmissions.

Dataset:
The dataset features 101,766 instances, each representing a hospital visit by a diabetic patient. It includes comprehensive data across 50 features such as demographics (race, gender, age), medical details (number of lab procedures, diagnoses, medication changes), and the target variable, which indicates whether a patient was readmitted within 30 days, after 30 days, or not readmitted.

Exploratory Data Analysis (EDA)

Initial data exploration involved:

-> Cleaning the dataset by addressing missing values, especially in the 'weight' and 'medical specialty' categories.

-> Analyzing feature distributions and relationships using visualizations to understand the data better and prepare it for modeling.

Feature Engineering

-> Imputation of missing values in 'weight' using a Random Forest algorithm based on related features like 'age' and 'race'.

-> Transformation of skewed numerical features to reduce variance and improve model accuracy.

-> Encoding of categorical variables to numeric forms suitable for machine learning models.

Model Development

Several predictive models were evaluated for their effectiveness in predicting readmissions:

1. Logistic Regression: Served as a baseline for performance comparison.
2. Naive Bayes: Tested for its simplicity and speed in model training.
3. K-Nearest Neighbors (KNN): Utilized for its efficacy in capturing the complexity of datasets through instance-based learning.
4. Decision Trees and Random Forests: Employed for their ability to handle non-linear data and provide feature importance estimates.
5. XGBoost: Chosen for its outstanding performance on structured data and its ability to handle large datasets efficiently.

 XGBoost emerged as the most effective model, achieving an accuracy of 64% based on the given metrics.

Evaluation and Results:
The model's performance was critically assessed using various metrics, including accuracy, precision, recall, F1-score, and AUC-ROC curve. These metrics helped in fine-tuning the model parameters and selecting the best model for deployment.





