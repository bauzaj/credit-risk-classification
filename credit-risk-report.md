# Credit Risk Report 

## Overview of the Analysis


* The purpose of this analysis was to determine whether future loans would fall into one of two categories: Healthy or High Risk.
* The goal was to predict 0 for Healthy or 1 for High Risk, using a list of features: loan size, interest rate, debt to income ratio, etc.
* Once features were determined for prediction, incorporation of sklearn model for train_test_split.
* Compared results between two models: Model 1 using LogisticRegression with scaled data, Model 2 using LogisticRegression with RandomOverSample.

## Results



* Machine Learning Model 1:
  * Accuracy score of 99%
  * Macro Avg of Precision, Recall, F1-Score: 92%, 95%, 94%
  * Precision: 100% for Healthy, 85% for High Risk
  * Recall: 99% for Healthy, 91% for High Risk
  



* Machine Learning Model 2:
  * Accuracy score of 99%
  * Macro Avg of Precision, Recall, F1-Score: 92%, 99%, 94%
  * Precision: 100% for Healthy, 84% for High Risk
  * Recall: 99% for Healthy, 99% for High Risk

## Summary
* While both models scored 99% in Accuracy, there were slight distinctions between them when it came to the High Risk loan status. Model 1 was 1% better at predicting High Risk loans correctly than Model 2. While Model 2 was 8% better at capturing actual High Risk instances.     Because of this my recommendation would be to utilize Model 2 with a F1 Score of 91% over Model 1 with a score of 88%.

