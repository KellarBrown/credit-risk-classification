# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to create and evaluate the performance of machine learning models to predict loan risk. The models were trained and tested on a dataset with a variety of financial features. The target variable was defined as either `0` (healthy loan) or `1` (high-risk loan). Two models were implemented and evaluated based on their performance metrics: the original model and the oversampled model.

## Results

The performance metrics for the original and oversampled models are as follows:

### Original Model:

- **Accuracy Score**: 0.99
- **Precision Score**: 
  - Healthy Loan (0): 1.00
  - High-Risk Loan (1): 0.87
- **Recall Score**: 
  - Healthy Loan (0): 1.00
  - High-Risk Loan (1): 0.89

### Oversampled Model:

- **Accuracy Score**: 1.00
- **Precision Score**: 
  - Healthy Loan (0): 1.00
  - High-Risk Loan (1): 0.87
- **Recall Score**: 
  - Healthy Loan (0): 1.00
  - High-Risk Loan (1): 1.00

## Summary

Based on the results of the machine learning models, both models demonstrated excellent performance. The accuracy score of both models was high, indicating a high rate of correct predictions for both healthy and high-risk loans. However, the oversampled model outperformed the original model in terms of the recall score for high-risk loans, achieving a perfect score of 1.00 compared to 0.89 from the original model.

This indicates that the oversampled model was better at identifying all high-risk loans, making it more reliable for predicting high-risk instances. However, both models achieved the same precision score for high-risk loans, indicating that when they predicted a loan to be high-risk, they were equally accurate.

Given these results, I would recommend the use of the oversampled model by the company due to its superior ability to identify all high-risk loans, thus making it more reliable for predicting high-risk instances.
