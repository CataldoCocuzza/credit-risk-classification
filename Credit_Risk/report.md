# Module 20 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
Can logistic regression machine learning model predict healthy loans vs high-risk loans.

* Explain what financial information the data was on, and what you needed to predict.
loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt	loan_status

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
Loan_status

* Describe the stages of the machine learning process you went through as part of this analysis.
data prep, sepereating features into training and testing data, import LogisticRegression, fit the model, make preditions, accuracy score.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
LogisticRegression, confusion_matrix


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: Accuracy: 0.99
    * Logistic Regression 
    0 (healty Loans):  Precision: 1.00, and Recall: 0.99.
    1 (High-risk loans): Precision: 0.85, and Recall: 0.91.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The Model works well and the precision and recall scores back that up. The model is more accurate with Healthy loans but it is still very accurate with 
High-risk loans. considering all this, I would reccomend this model.

