# Loan-Report
# Overview
The goal of this project was to determine likely pointers to loan default in a Bank's borrowing system. Decision trees and random forests were utilised in this project. Recall was prioritized over the other metrics used. Recall measures how many actual defaulters (1s) we correctly identified. A high recall means the model will capture most defaulters. After feature engineering, the Decision tree with a Recall of 83% was used on test dataset. Based on the model, simple interest, credit type, interest to credit ratio and debt to income ratio were the most important pointers of loan default.

# Business Understanding
Loan default prediction is crucial for financial institutions as it minimizes financial risk, increases profitability, and ensures regulatory compliance. By accurately identifying high-risk borrowers, we can reduce non-performing loans (NPLs), prevent financial losses, and optimize interest rates to balance risk and reward. A well-tuned model improves credit decisioning enhances investor confidence by maintaining financial stability and reducing volatility in financial reports. Ultimately, an effective loan default prediction system leads to smarter lending decisions, increased revenue, and better risk management.

# Data Undestanding
This dataset contains 148,670 loan applications with various borrower and loan attributes used for predicting loan default risk. It includes demographic details (Gender, Age, Region), financial indicators (Income, Credit Score, Credit Worthiness), and loan-related factors (Loan Amount, Interest Rate, Term, Property Value, Collateral). Some columns, like rate_of_interest and property_value, have missing values, which may require imputation. The target variable, Status, indicates whether a loan was defaulted (likely 0 or 1). This dataset is useful for credit risk analysis, helping lenders assess borrower reliability and optimize lending decisions.
![image](https://github.com/user-attachments/assets/0e0996e3-5c91-4b0a-829e-8a1a3c8d133e)

