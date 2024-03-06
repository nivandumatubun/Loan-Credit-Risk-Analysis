# **Loan Credit Risk Analysis**

## Overview
Credit risk analysis is an important part in the banking and financial industry to measure potential losses that may occur due to credit that the borrower fails to repay. The background to the issue of credit risk analysis includes several important points including Credit Provision, Credit Risk, Analysis Objectives, Analysis Approach, and Risk Management. In this context, credit risk analysis becomes important in supporting appropriate decision making in granting credit, managing risks associated with credit portfolios, and ensuring the financial health and stability of financial institutions.

## Goals
- Provide insights into credit risk assessment methodologies and techniques.
- Develop predictive models to identify high-risk loan applicants and prevent defaults.
- Enhance decision-making processes for lenders and financial institutions.

## Objectives
- Generate prediction model (classification) for loan credit analysis
- Analyze the borrowers' credit profile

[Documentation Detail](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/FINAL%20TASK%20PBI%201.pdf)

### Data Preparation
- Fill Data Null
- Drop Unnecessary Data
- Outlier Removal
- Feature Selection
- Feature Encoding
- Feature Transformation

### Exploratory Data Analysis
- Grade Based on Bad Flag
![grade](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/grade.png)

- Homeownership Based on Bad Flag
![homeown](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/homeown.png)

- Application Type Based on Bad Flag
![apptype](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/apptype.png)

- Term Based on Bad Flag
![term](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/term.png)

### Modelling (Classification)
1. Logistic Regression
2. Random Forest Classifier
3. Decision Tree Classifier

### Feature Importance
![featimpor](https://github.com/nivandumatubun/Loan-Credit-Risk-Analysis/blob/master/featimpor.png)

### Summary
Based on the prediction model and feature importance that has been created, it is concluded that the appropriate algorithm is Logistic Regression because it produces quite high recall and F-1 Score, whereas in other algorithms the recall metrics are quite low. The recall metric is used because we focus on True Positive Rate and minimize large False Negatives.
For feature importance, a threshold is set at 0.05 so that features with a score > 0.05 are considered as features that influence the target. So the top 3 important features are produced, namely funded amount, total rec prncp, and out prncp.

### Recommendations
1. **Funded Amount**
- Pay attention to the amount of funds given to the borrower when granting a loan. This amount reflects the level of risk taken by the lender, because the greater the amount of funds provided, the greater the credit risk faced.
- Reevaluate the policy for determining the amount of loan funds to ensure that the level of credit risk is in line with the company's risk tolerance.

2. **Total Receive Principal**
- Monitor the total principal received from borrowers to date. This information helps in understanding how well the borrower fulfills its obligations in repaying the loan.
- Analysis of trends in total principal received can provide insight into a borrower's repayment behavior and possible repayment risks that may arise in the future.

3. **Outstanding Principal**
- Pay attention to the principal amount that still needs to be repaid by the borrower. This information is important for understanding the level of financial obligations the borrower still faces and the associated credit risks.
- Re-evaluate collection processes and credit handling policies to ensure that appropriate steps are taken to ensure the return of outstanding principal payments.

By monitoring and understanding information from these features, companies can better manage their credit risk, carry out risk evaluations effectively, and take the necessary steps to reduce potential credit losses.
