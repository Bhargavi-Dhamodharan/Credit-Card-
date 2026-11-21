# Credit-Card
💳 Credit Card Default Prediction Using Machine Learning

Project Overview:
This project focuses on predicting whether a customer will default on their credit card payment in the following month using Machine Learning techniques.
The project analyses customer demographic information, credit limits, repayment history, bill amounts, and previous payment amounts to identify patterns associated with credit card default.
The main objective is to build and evaluate classification models that can predict the likelihood of credit card payment default.

Project Objectives:
To analyse credit card customer data
To perform data cleaning and preprocessing.
To identify and handle outliers.
To visualise important patterns and relationships in the dataset.
To select relevant features using SelectKBest.
To build classification models for predicting credit card defaults.
To compare model performance using evaluation metrics.

Dataset Description:
The dataset contains 30,000 customer records with 25 original columns.
It includes:
Customer ID
Credit limit
Gender
uEducation
Marriage status
Age
Repayment stats
Bill statement amounts
Previous payment amounts
Default payment status for the next month

Target Variable: default payment next month
0 – No Default
1 – Default

Technologies and Libraries Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Project Workflow:

1. Data Collection
Imported the credit card dataset using Pandas.

2. Data Cleaning
Removed unnecessary index columns.
Converted columns into appropriate numerical formats.
Checked missing values.
Checked duplicate records.

3. Outlier Handling
Used the Interquartile Range (IQR) method to identify and handle outliers.

4. Data Encoding
Applied One-Hot Encoding to the MARRIAGE feature.

5. Exploratory Data Analysis
Created visualisations to understand the dataset, including:
Default vs Non-default customer distribution.
Customer age distribution.
Credit limit distribution.
Default rate by gender.
Default rate by education category.
Correlation heatmap.

6. Feature Selection
Used SelectKBest with the f_classif scoring function to identify the 20 highest-scoring features.

7. Train-Test Split
Split the dataset into:
80% Training Data
20% Testing Data
Used stratified sampling to maintain target class proportions.

8. Model Building and Training
Implemented the following Machine Learning classification algorithms:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

9. Model Evaluation
Evaluated the models using:
Accuracy
Precision
F1-Score

Conclusion:
This project demonstrates the application of Machine Learning techniques for predicting credit card payment defaults.
Three classification algorithms were implemented and evaluated using different performance metrics.
Among the tested models, Random Forest achieved the highest F1-score of 0.47, while Logistic Regression achieved the highest precision of 0.68.
The project provides practical experience in data preprocessing, exploratory data analysis, feature selection, classification, and model evaluation.

Author:
D Bhargavi
B.Sc. Computer Science with Artificial Intelligence
Area of Interest: Artificial Intelligence & Machine Learning

Thank you for exploring my Credit Card Default Prediction project!
