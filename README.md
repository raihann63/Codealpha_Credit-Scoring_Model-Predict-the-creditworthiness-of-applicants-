# Codealpha_Credit-Scoring_Model-Predict-the-creditworthiness-of-applicants-

CodeAlpha — Credit Scoring Model
Predict the Creditworthiness of Applicants Using Machine Learning

Project Overview:

This project focuses on building a Credit Scoring Model that predicts whether a loan applicant is Good, Standard, or Bad based on their financial behavior and demographic data.
The goal is to help financial institutions make data-driven lending decisions and reduce credit risk.

Tech Stack:

Python (Jupyter Notebook)

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib

Machine Learning Algorithms: Decision Tree, Random Forest, XGBoost

Tools: Jupyter Notebook

Key Features:

Data cleaning and preprocessing
Feature selection and correlation analysis
Model training and hyperparameter tuning
Predictive interface to test applicant creditworthiness
Balanced dataset using SMOTE to improve fairness in predictions

Model Output:


 Final Model Comparison:
                 Model   ROC-AUC
0  Logistic Regression  0.606970
1        Decision Tree  0.948251
2        Random Forest  0.995907
3              XGBoost  0.995750


Goal:

sample = {
    'Age': 30,
    'Annual_Income': 50000,
    'Num_Bank_Accounts': 5,
    'Num_Credit_Card': 3,
    'Interest_Rate': 10,
    'Num_of_Loan': 2,
    'Delay_from_due_date': 5,
    'Outstanding_Debt': 10000,
    'Credit_Utilization_Ratio': 40,
    'Monthly_Balance': 2000
}

Output: Predicted Credit Mix: Good


sample = {
    'Age': 20,
    'Annual_Income': 10000,
    'Num_Bank_Accounts': 1,
    'Num_Credit_Card': 1,
    'Interest_Rate': 25,
    'Num_of_Loan': 6,
    'Delay_from_due_date': 30,
    'Outstanding_Debt': 10000,
    'Credit_Utilization_Ratio': 90,
    'Monthly_Balance': 200
}


output: Predicted Credit Mix: Standard

Outcome: 
To develop a reliable machine learning system that improves decision-making in credit scoring and minimizes financial losses.


Developed by:
Md. Raihan Ali
CodeAlpha Machine Learning Intern
