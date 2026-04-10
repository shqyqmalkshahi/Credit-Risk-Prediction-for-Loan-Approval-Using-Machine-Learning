# Credit-Risk-Prediction-for-Loan-Approval-Using-Machine-Learning
Credit Risk Prediction for Loan Approval
 Overview

This project applies machine learning techniques to predict credit risk and support loan approval decisions. The goal is to classify applicants as low-risk or high-risk borrowers using financial and demographic data.

 Business Problem

Financial institutions must balance risk and profitability when approving loans. Incorrect decisions can lead to financial losses or missed opportunities. This project builds a predictive model to improve credit risk assessment using data-driven methods.

 Dataset
German Credit Dataset
1,000 loan applicants
Features include:
Age
Credit amount
Loan duration
Account status
Loan purpose
 Methodology
Data Preparation
Removed unnecessary columns
Handled missing values using imputation
Encoded categorical variables
Scaled numerical features
Modeling
Logistic Regression (baseline model)
Decision Tree (nonlinear model)
Evaluation Metrics
Accuracy
Precision
Recall
Confusion Matrix
 Results
Logistic Regression Accuracy: 74.5%
Decision Tree Accuracy: 70%

Logistic Regression performed better overall

However:

Model struggled to identify high-risk applicants
Low recall for risky borrowers
 Key Insights
Higher credit amounts are associated with higher risk
Loan duration impacts repayment likelihood
Financial indicators (saving/checking accounts) are strong predictors
 Tools Used
Python
pandas
scikit-learn
matplotlib
 Business Impact

This model demonstrates how machine learning can:

Improve loan decision consistency
Reduce financial risk
Support automated credit evaluation systems
 Limitations
Dataset is relatively small
Class imbalance affects performance
Missing important real-world variables (income, employment details)
 Future Improvements
Apply advanced models (Random Forest, XGBoost)
Handle imbalance (SMOTE, class weighting)
Use larger real-world datasets
