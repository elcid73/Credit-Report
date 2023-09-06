# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis was to use existing healthy and high risk loans data to create a predictive model to help identify high risk loans based on the various available variables.
* The data included information regarding various loans that included fields like loan_size, interest_rate, borrower_income, debt_to_income ratio, number of accounts, deragotary_marks, total_debt and loan status.
* All variables were used to predict loan status, which can be (0) - healthy loand and (1)- high risk loan
* The stages of machine learning process used in the analysis included;
  * Reading in the leanding data into data frame
  * Defining y (loan_status) and X variables (all other variables) to be used in logistic regression
  * Spliting the data into train and test bucket
  * Using train data to fit logistic regression
  * Generating prediction uding test data
  * Evaluating results and accuracy of the model by reviewing accuracy score, confusion matrix and classification report.
* The method used was logistic regression, first with original data and then with oversampled data.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy -- 0.9918489475856377
  * Precision -- 0.85 (for risky loand 1)
  * Recall -- 0.91 (for risky loand 1)

* Machine Learning Model 2:
  * Accuracy -- 0.9938093272802311
  * Precision -- 0.84 (for risky loand 1)
  * Recall -- 0.99 (for risky loand 1)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The model with oversampled data needs to be used. The model with oversampled data provides much lower percentage of false negatives with recall increasing to 99% from 91%, with precision only dropping 1% to 84% from 85%.  Model with oversampled data potentially significantly reduces financial losses from bad loans by minimizing high risk loans appearing as healthy.

* It is more important to accurately predict 1 (high risk loans), since these loans contribute to financial losses.


