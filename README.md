# Bankruptcy-Prediction-for-NYSE-NASDAQ-Companies
A model to predict bankruptcy risk for companies listed on NYSE and NASDAQ, using financial indicators and logistic regression. Aims to assist in assessing financial health and investment risks.
Project Overview
This project aims to predict the likelihood of bankruptcy for companies listed on the New York Stock Exchange (NYSE) and NASDAQ. Using financial indicators and logistic regression, the model assesses the financial health of companies and helps in evaluating potential investment risks.

Dataset - Link: https://www.kaggle.com/datasets/utkarshx27/american-companies-bankruptcy-prediction-dataset
The dataset includes financial data for companies, with features such as:

X1, X2, ... X18: Various financial metrics (e.g., profitability, liquidity ratios)
status_label: Target variable indicating company status (0 for "alive" and 1 for "distressed")
Project Steps
Data Preprocessing:

Encode status_label as binary.
Drop unnecessary columns (company_name, year).
Check and handle missing values.
Feature Selection and Engineering:

Analyze financial indicators that contribute most to predicting bankruptcy.
Create new features if necessary.
Modeling with Logistic Regression:

Train a logistic regression model to classify companies as financially healthy or at risk of bankruptcy.
Evaluation Metrics:

Evaluate the model using accuracy, precision, recall, F1 score, and ROC-AUC.
Use SMOTE for class balancing if needed.
Interpret Results:

Interpret feature coefficients to understand which metrics most influence bankruptcy prediction.
Results
The model provides insights into the financial health of companies and can be used to assess potential investment risks. It highlights critical financial indicators affecting bankruptcy risk.

