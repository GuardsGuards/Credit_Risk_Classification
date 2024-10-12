Credit Risk Classification - Module 20 Challenge
Overview
This project involves building a machine learning model to predict the creditworthiness of borrowers using historical lending data. The dataset provided includes various financial features, and the target is to classify loans as either "healthy" or "high-risk."

The machine learning model implemented is Logistic Regression, which is appropriate for binary classification tasks like this one. The objective is to help the peer-to-peer lending platform identify high-risk loans and mitigate default risks.

Purpose of the Analysis
The purpose of this analysis is to:

Predict whether a loan is high-risk (1) or healthy (0) based on several financial features.
Evaluate the model's performance to ensure it can effectively classify loans and identify potential risks.
Dataset and Variables
Input Variables (X):
Loan amount, interest rate, annual income, debt-to-income ratio, and other financial factors.
Target Variable (y):
loan_status: Binary variable where:
0 = Healthy loan
1 = High-risk loan
The dataset was split into training and testing sets, and a logistic regression model was trained and evaluated.

Model Development
Model Used: Logistic Regression
Data Split: The dataset was split into training and testing sets using an 80/20 split.
Metrics Used: Accuracy, precision, recall, F1-score, and confusion matrix were used to evaluate the model.
Results
Accuracy: 99%
Precision:
Class 0 (Healthy Loan): 100%
Class 1 (High-Risk Loan): 88%
Recall:
Class 0: 100%
Class 1: 94%
F1-Score:
Class 0: 100%
Class 1: 91%
The model demonstrates excellent performance in predicting healthy loans and good performance in predicting high-risk loans. The precision and recall for high-risk loans were slightly lower than for healthy loans.

Summary
The logistic regression model performs well, achieving high accuracy and excellent performance for healthy loans (class 0). However, its performance in predicting high-risk loans (class 1) is slightly lower, with an 88% precision, indicating some misclassification of high-risk loans.

Recommendations:
For Risk Management: The current model is reliable for identifying healthy loans. If minimizing high-risk loan approval is critical, further model tuning or exploration of alternative models may help improve precision in predicting high-risk loans.
This model is a good starting point for credit risk prediction, and with further refinements, it could become a powerful tool for managing financial risk in a lending environment.
