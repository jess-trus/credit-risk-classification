# credit-risk-classification


## Overview of the Analysis



* The purpose of this analysis was to use existing credit risk information to create a model that would predict credit risk for potential loan applicants.
* The data provided financial information about each borrower. The Y value was set at "loan status" which had a value of either 0 or 1. The X values were loan size	, interest rate, 	borrower income,	debt to income ratio, 	number of accounts,	derogatory marks and	total debt.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

* The oversampled model performs best. When looking at the recall, which is 88% in the first model and 91% in the second model, we see that the oversampled model is caputuring a higher amount of 
* In the case of this credit risk classification, performance is mostly based on the models ability for accurately predict the 1's. Borrowers labeled as 1 are high-risk, indicating that the chance the loan will not be repaid or that the borrower defaults is high. If the borrowers are inaccurately predicted as low-risk (0) when they are actually high-risk, the lending agency may suffer great finanical loss.

Although the oversampled model performed better, it would still need further considerations of the problem in order to select it as a recommended model.
