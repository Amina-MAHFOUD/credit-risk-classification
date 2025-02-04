# Credit Risk Analysis Report

## Overview of the Analysis 

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk. Specifically, the model is designed to classify loans into two categories:

 - Class Purple (Healthy Loan - Label 0): Low-risk loans that are likely to be repaid.
 - Class Yellow (High-Risk Loan - Label 1): Loans with a higher probability of default.

The dataset consists of financial information used to train the model, and we aimed to predict whether a given loan is high-risk or healthy. The analysis followed a standard machine learning workflow, including:

 1. Data Preprocessing: Separating columns and splitting data for modeling.
 2. Model Training: Using Logistic Regression as the primary algorithm.
 3. Model Evaluation: Measuring performance using accuracy, precision, recall, and F1-score.


## Results

The performance metrics of the logistic regression model are as follows:

#### Class Purple (Healthy Loans - 0)

* Precision: 1.00
* Recall: 1.00
* F1-score: 1.00
* Support: 18,759

#### Class Yellow (High-Risk Loans - 1)

* Precision: 0.87
* Recall: 0.95
* F1-score: 0.91
* Support: 625

#### Overall Performance

* Accuracy: 0.99
* Macro Average F1-score: 0.95
* Weighted Average F1-score: 0.99

## Summary

The logistic regression model performs exceptionally well in predicting healthy loans (Class 0) with perfect precision and recall (1.00). However, it has slightly lower precision (0.87) for high-risk loans (Class 1), meaning some false positives exist.

***Recommendation:***


If the primary goal is overall accuracy, the logistic regression model is highly effective.
If the company needs better detection of high-risk loans, improving precision is key. This could involve trying Random Forest for better handling of non-linear relationships.
