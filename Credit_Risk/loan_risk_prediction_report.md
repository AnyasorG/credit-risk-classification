# Module 12 Report 

## Title: Loan Risk Prediction Analysis: A Comparative Analysis of Machine Learning Models for Informed Lending Decisions

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate machine learning models for predicting the risk of loans based on financial data. The dataset included information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (0 for healthy loans, 1 for high-risk loans). The goal was to build models that could effectively identify high-risk loans and assist in making informed lending decisions. 
The analysis involved preprocessing the data, splitting it into training and testing sets, and employing logistic regression models. Additionally, resampling techniques, specifically Random OverSampling, were utilized to address class imbalance.

## Results

    * Machine Learning Model 1:
        - Accuracy: 99%
        - Precision (High-Risk Loan): 86%
        - Recall (High-Risk Loan): 94%

    * Machine Learning Model 2 (Resampled):
        - Accuracy: 99%
        - Precision (High-Risk Loan): 85%
        - Recall (High-Risk Loan): 99%

## Summary

Both machine learning models demonstrated high accuracy, with Model 2 incorporating random oversampling to address class imbalance. While Model 1 exhibited slightly higher precision for high-risk loans, Model 2 displayed superior recall, minimizing the chances of missing actual high-risk loans. The choice between models depends on the specific lending strategy; if the priority is identifying the majority of high-risk loans, Model 2 is recommended. However, if precision is paramount, Model 1 may be preferable. The performance of the models indicates their potential usefulness in assisting financial institutions with loan risk assessment.
