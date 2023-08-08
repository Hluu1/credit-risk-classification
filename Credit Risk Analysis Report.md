# Module 12 Report Template

## Overview of the Analysis

The goal of this analysis was to evaluate various machine learning models for credit risk assessment.
The purpose was to determine which model performs best in predicting whether a loan is likely to be safe or risky.
The dataset consisted of financial information related to loan applications, and the objective was to predict whether a loan would fall into the category of "high-risk" or "healthy" based on this information.
The variables of interest were the loan outcomes, specifically:
 - 0 for healthy loans (low risk)
 - 1 for high-risk loans (potential risk)
The machine learning process involved the following stages:
 - Data Preprocessing: The dataset was cleaned and prepared, handling missing values and converting categorical variables into numerical format if needed.
 - Feature Selection/Engineering: Relevant features were selected or engineered to improve model performance.
 - Model Training and Evaluation: Several machine learning models were trained using the data. The models were evaluated using balanced accuracy, precision, and recall scores to assess their performance in predicting high-risk loans while minimizing false positives and false negatives.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - Balanced Accuracy: 99%
  - Precision (High-Risk Loans): 87%
  - Recall (High-Risk Loans): 89%

* Machine Learning Model 2:
  - Balanced Accuracy: 98%
  - Precision (High-Risk Loans): 85%
  - Recall (High-Risk Loans): 91%

## Summary

Both machine learning models demonstrated strong performance in predicting loan outcomes.Model 1 achieved slightly higher balanced accuracy, precision, and recall scores compared to Model 2While Model 2 showed a slightly better recall score, Model 1 exhibited better precision and overall balanced accuracy.

In a credit risk context, it's important to strike a balance between precision and recall. Predicting high-risk loans with high recall can help minimize missed high-risk loans, while a high precision can reduce the likelihood of approving loans that may default. Considering the balance between these factors, Model 1 seems to perform better overall.

However, the choice of the best-performing model may depend on the specific priorities of the business. If the company is more concerned about avoiding risky loans, a model with higher recall might be preferred. If minimizing false positives (approving loans that might default) is a higher priority, a model with higher precision might be favored.

Given its strong overall performance, Model 1 is recommended as it strikes a good balance between precision and recall, making it a solid choice for credit risk assessment.
