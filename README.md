# Loan Status Prediction using PySpark MLlib

## Overview
This project demonstrates how to build a robust loan approval prediction pipeline using **PySpark MLlib**. It leverages real-world loan applicant data to predict whether a loan application will be **Approved** or **Rejected** based on various financial and personal attributes.

## The pipeline includes:
- Data preprocessing and feature engineering
- Handling missing values with imputation
- Encoding categorical variables
- Feature scaling
- Training a machine learning model with cross-validation
- Evaluation using AUC and confusion matrix
- Generating prediction results for further analysis

---

## Dataset

| Column                  | Description                                   |
|-------------------------|-----------------------------------------------|
| no_of_dependents        | Number of dependents of the applicant          |
| income_annum            | Annual income                                   |
| loan_amount             | Requested loan amount                           |
| loan_term               | Loan term (months)                              |
| cibil_score             | Credit score (CIBIL)                            |
| residential_assets_value| Value of residential assets                     |
| commercial_assets_value | Value of commercial assets                      |
| luxury_assets_value     | Value of luxury assets                           |
| bank_asset_value        | Value of bank assets                            |
| total_assets            | Total assets (engineered feature)               |
| debt_to_income          | Debt-to-income ratio (engineered feature)       |
| cibil_flag              | Binary flag derived from cibil_score            |
| is_self_employed        | Binary flag indicating self-employment status   |
| is_graduate             | Binary flag indicating graduate education       |
| education_index         | Encoded education level                           |
| self_employed_index     | Encoded self-employed status                      |
| loan_status_index       | Target variable (encoded loan status)            |

---
## Model Performance
- Mean Cross-Validated AUC: 0.9650
- Test AUC: 0.9720
The model demonstrates strong predictive power in distinguishing approved vs rejected loans.

## Visualizations:
- ROC Curve: Shows the trade-off between true positive rate and false positive rate.
- Confusion Matrix: Displays the counts of true positives, false positives, true negatives, and false negatives.
- Both visualizations are saved in the outputs/ directory for further analysis.

## contact
If you have questions or want to collaborate, feel free to reach out!
GitHub: github.com/zaralrubaie


