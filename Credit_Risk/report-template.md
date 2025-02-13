# Module 12 Report Template

Here's a proposed summary and results section based on your analysis:

## Overview of the Analysis

The analysis aimed to evaluate the performance of machine learning models in predicting credit risk classification. The purpose of the analysis was to identify high-risk loans (`1`) versus healthy loans (`0`) using financial data such as loan size, interest rate, borrower income, debt-to-income ratio, and derogatory marks.

Key stages in the machine learning process included:
- Data preparation, splitting the dataset into training and testing subsets.
- Training a logistic regression model on the training data.
- Evaluating model performance using a confusion matrix and classification report.

The variables to predict were binary, with `0` representing healthy loans and `1` representing high-risk loans. The class distribution was imbalanced, as healthy loans far outnumbered high-risk loans.

## Results

- **Logistic Regression Model:**
  - **Accuracy**: 99%
  - **Precision**: 1.00 (healthy loans), 0.86 (high-risk loans)
  - **Recall**: 0.99 (healthy loans), 0.94 (high-risk loans)
  - **F1-Score**: 1.00 (healthy loans), 0.90 (high-risk loans)

## Summary

The logistic regression model demonstrated high performance in predicting both healthy loans and high-risk loans. It achieved near-perfect precision, recall, and F1-scores for healthy loans (`0`). However, its precision for high-risk loans (`1`) was slightly lower, reflecting the model's challenge in handling class imbalance.

### Recommendation
The logistic regression model is recommended for deployment, as it achieves a strong balance between accuracy and recall for high-risk loans. Given the importance of correctly identifying high-risk loans, the model's recall of 94% for high-risk loans ensures most risky cases are captured.

