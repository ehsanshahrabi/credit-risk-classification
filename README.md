# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to assess the performance of a machine learning model for credit risk analysis. The model uses logistic regression to predict whether a loan is classified as a "healthy loan" (0) or a "high-risk loan" (1). Two different approaches are evaluated: one using the original data and another using resampled data to address class imbalance.

## Results

### 1- Logistic Regression Model with Original Data

Accuracy Score: 0.9918

Precision Score:
Healthy Loan (0): 1.00

High-Risk Loan (1): 0.85

Recall Score:
Healthy Loan (0): 0.99

High-Risk Loan (1): 0.91

F1-Score:
Healthy Loan (0): 1.00

High-Risk Loan (1): 0.88

### 2-Logistic Regression Model with Resampled Data

Accuracy Score: 0.9938

Precision Score:
Healthy Loan (0): 1.00

High-Risk Loan (1): 0.84

Recall Score:
Healthy Loan (0): 0.99

High-Risk Loan (1): 0.99

F1-Score:
Healthy Loan (0): 1.00

High-Risk Loan (1): 0.91

## Summary

The logistic regression model shows promising performance for credit risk analysis in both the original data and the resampled data scenarios. 
Considering the importance of correctly identifying high-risk loans in credit risk analysis, the logistic regression model trained on resampled data is recommended for use by the company. While the precision for high-risk loans is slightly lower compared to the model using original data, the higher recall score ensures that a significant portion of true high-risk loans is identified. This model strikes a good balance between precision and recall, providing a reliable tool for the company to assess credit risk accurately.
Here are the key findings:

### Logistic Regression Model with Original Data:

The model achieves a high accuracy score of 0.9918, indicating its overall effectiveness in classifying loans.
The precision score for the "healthy loan" (0) class is perfect at 1.00, indicating that all predicted healthy loans are correct.
The precision score for the "high-risk loan" (1) class is 0.85, suggesting that approximately 85% of the predicted high-risk loans are correct.
The recall score for the "healthy loan" (0) class is 0.99, meaning that nearly all actual healthy loans are successfully identified.
The recall score for the "high-risk loan" (1) class is 0.91, indicating that the model captures around 91% of the true high-risk loans.
The F1-scores for both classes show a similar trend, with a perfect score of 1.00 for healthy loans and 0.88 for high-risk loans.

### Logistic Regression Model with Resampled Data:

The model's performance improves slightly when trained on resampled data.
The accuracy score increases to 0.9938, indicating improved overall performance.
The precision score for the "high-risk loan" (1) class decreases to 0.84, meaning that approximately 84% of the predicted high-risk loans are correct.
The recall score for the "high-risk loan" (1) class remains high at 0.99, indicating that the model effectively identifies nearly all true high-risk loans.
The F1-score for high-risk loans decreases slightly to 0.91 while maintaining a perfect score of 1.00 for healthy loans.
Based on the results, both versions of the logistic regression model show strong predictive capabilities for identifying healthy loans. However, when it comes to high-risk loans, there is a trade-off between precision and recall. The model trained on resampled data achieves a higher recall score for high-risk loans (0.99) at the expense of a slightly lower precision score (0.84). Overall, both models demonstrate high accuracy, making them reliable choices for predicting loan classifications.

