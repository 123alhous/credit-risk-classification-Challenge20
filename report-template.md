
## Overview of the Analysis


* The purpose of this analysis was to develop and evaluate a machine learning models to predict loan risk based on financial data.
* The dataset is related to loan applicants, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

* The goal is to predict and classify loans into 2 different class: Healthy Loans (Class 0) and High-Risk Loans (Class 1) based on their associated risk factors.
* A Logistic Regression model from sklearn was created with the Limited-memory BFGS ('lbfgs') solver

## Results

- Accuracy: 0.99
- Balanced Accuracy: 0.97
- Precision
    - Healthy: 1.00
    - High-Risk: 0.84
- Recall
    - Healthy: 0.99
    - High-Risk: 0.94

## Summary

We can noticed that the Logistic Regression model is able to predict very well healthy loans. 
