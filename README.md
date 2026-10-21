# computing-intelligence-lab-1
Lab 1: Telco Customer Churn Analysis using Python and pandas.

# Overview

This project explores why some telecommunications customers leave while others stay. Using Python and Pandas, I analyzed customer data to compare churn rates across demographic groups, phone service, contract types, and payment methods.

Dataset

The dataset contains 7,043 customer records and 21 attributes. It was provided through Kaggle.

What I Did

Loaded the dataset and inspected its first and last five rows.

Checked data types, converted Churn from Yes/No to 1/0, and removed the TotalCharges column because it contained 11 missing values.

Compared churn counts and percentages across eight customer attributes.

Interpreted each result to identify which groups had higher or lower observed churn rates.

Key Findings

Contract type: 42.71% of month-to-month customers churned, compared with 2.83% of customers on two-year contracts.

Payment method: Electronic check users had the highest churn rate at 45.29%.

Senior citizen status: The churn rate was 41.68% for senior citizens and 23.61% for non-senior customers.

Gender: The difference was small, with churn rates of 26.92% for female customers and 26.16% for male customers.

These results show clear differences between some customer groups, although they do not prove that any single attribute causes churn.

Tools

Python · Pandas · NumPy · Kaggle Notebooks

Conclusion

This lab gave me practical experience preparing data, comparing customer groups, and interpreting churn rates. It also showed me how exploratory data analysis can reveal patterns worth investigating further when trying to understand why customers leave.
