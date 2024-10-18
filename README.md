# Churn Analysis Project

## Introduction
The **Churn Analysis Project** aims to predict customer churn using machine learning techniques. The goal is to analyze customer data from a telecom company and build models to predict whether a customer will churn (leave the service) or stay.

This project follows a typical machine learning workflow:
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Building (Logistic Regression, Random Forest)
- Model Evaluation

## Dataset
The dataset used in this project is the **Telco Customer Churn** dataset, which includes customer data such as:
- **Demographics** (e.g., gender, SeniorCitizen, Partner, Dependents)
- **Services** (e.g., PhoneService, InternetService, OnlineSecurity)
- **Account Information** (e.g., Contract, Payment method, MonthlyCharges, TotalCharges)
- **Churn**: The target variable indicating if a customer churned or not.

## Models Used
Two machine learning models were built to predict churn:
- **Logistic Regression**: A linear model for binary classification.
- **Random Forest**: An ensemble method that uses multiple decision trees for improved predictive performance.

## Results
The models were evaluated using key metrics such as:
- **Accuracy**: The overall percentage of correct predictions.
- **Precision**: The proportion of positive identifications that were actually correct.
- **Recall**: The ability to find all the relevant instances of churn.
- **F1-Score**: The harmonic mean of precision and recall.
- **Confusion Matrix**: A table used to evaluate the performance of a classification model.

The **Random Forest** model performed better than Logistic Regression in terms of capturing complex relationships in the data.

## Project Structure
```plaintext
├── Churn_Analysis.ipynb        # Jupyter notebook with the complete analysis and modeling.
├── requirements.txt            # Python libraries required to run the project.
├── README.md                   # Project documentation.
└── data                        # Directory for storing the dataset (optional).
