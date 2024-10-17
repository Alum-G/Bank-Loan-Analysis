# Bank-Loan-Analysis

## Problem Statement

### High Loan Default Rates and Credit Risk Management

#### Context:
Platinum-Trust bank has a reputation for aligning well with the goals of a forward-thinking financial institution focused on excellence and innovation. The bank has experienced a steady rise in loan defaults over the past fiscal year, leading to increased financial losses and deteriorating credit quality. The current loan approval process relies heavily on standard credit score assessments and manual underwriting, which may overlook other significant risk factors like debt-to-income ratio (DTI), employment history, and repayment behavior. This lack of comprehensive risk assessment is contributing to an inaccurate evaluation of borrower creditworthiness.

#### Problem:
How can the bank better assess and mitigate credit risk to reduce loan default rates and improve the overall quality of its loan portfolio?

#### Key Points:
The current loan approval and risk assessment models do not effectively account for all risk factors, leading to a higher-than-expected default rate.
There is a need to analyze borrower characteristics such as employment length, income stability, and past payment history to develop more reliable risk models.
Enhancing the use of KPIs such as the debt-to-income (DTI) ratio, loan-to-income ratio, and historical repayment behavior could improve the decision-making process.

#### Objective:
To perform an in-depth analysis of the bank’s loan portfolio, identifying patterns in defaulted loans and developing a predictive model for assessing credit risk. This would allow the bank to tailor its lending criteria, improve borrower risk profiling, and ultimately reduce the loan default rate.

This repository contains step-by-step documentation of the process for analyzing bank loan data using SQL for data querying and Tableau for data visualization.

## Dashboard Overview 
The Bank Loan Data Analysis project aims to provide a comprehensive guide for analyzing and visualizing bank loan data using SQL and Tableau. This project demonstrates how to extract, clean, and analyze large datasets related to loans, focusing on key metrics such as loan approval rates, customer demographics, loan amounts, and repayment performance.

#### Data Source
Bank Data Available at [Google Drive](https://drive.google.com/drive/folders/1xqdUuTfUKXVLH7jXORupccsCMKY5dLRy)
Generate your own dataset using [Google Drive](https://colab.research.google.com/drive/1kGDnIw1M1QqEVbC0NT8rwAD7zON97qvA?usp=share_link)

### Key Performance Index
Key Performance Indicators (KPIs) help assess the health of the loan portfolio, the efficiency of the lending process, and overall business performance. 
Some important KPIs that can be considered for the loan analysis include:

1. Loan Approval Rate: The percentage of loan applications that are approved versus those that are submitted, serving as a good indicator for the efficiency of the loan approval process.

  Formula:
  Loan Approval Rate = ( Number of Approved Loans / Total Loan Applications ) × 100
  
2. Average Loan Amount: Helps assess the lending strategy and customer borrowing behavior by measuring the average amount of loans issued over a specific period.

  Formula:
  Average Loan Amount = ( Total Loan Amount Issued / Number of Loans Issued )

3. Default Rate: Indicates the risk level associated with the loan portfolio by measuring the percentage of loans that are in default relative to the total number of loans issued.

  Formula:
  Default Rate = ( Number of Defaulted Loans / Total Loans ) * 100

4. Average Interest Rate: The average interest rate charged on the loans issued.

  Formula:
  Average Interest Rate = ( Total Interest Collected / Total Loan Amount ) × 100

5. Debt-to-Income Ratio (DTI): A measure of a borrower's monthly debt payments relative to their monthly income. DTI evaluates borrower creditworthiness and repayment ability.

  Formula:
  DTI Ratio = ( Total Monthly Debt Payments / Gross Monthly Income ) × 100

6. Repayment Rate: The percentage of the loan amount that is repaid by borrowers within the agreed time frame.

  Formula:
  Repayment Rate = ( Total Amount Repaid / Total Amount Loaned ) × 100

7. Loan Term Length: Provides insights into customer preferences and repayment schedules by measuringtThe average length of time (in months) for which loans are issued.

  Formula:
  Average Loan Term = ( Total Loan Terms / Number of Loans Issued )

### sql_querries


