# Module 12 Challenge

## Loan Risk Prediction Models for Informed Lending Decisions

### Contents

1. [Overview](#overview)
2. [Files and Directories](#files-and-directories)
3. [Project Development Stages](#project-development-stages)
4. [Set Up and Execution](#set-up-and-execution)
5. [Ethical Considerations](#ethical-considerations)
6. [Data Source](#data-source)
7. [Code Source](#code-source)
8. [License](#license)
9. [Summary](#summary)
10. [Author](#author)

---

## 1. Overview

This project aims to develop and evaluate machine learning models for predicting loan risks based on financial data. The dataset includes information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (0 for healthy loans, 1 for high-risk loans). The goal is to build models that can effectively identify high-risk loans and assist in making informed lending decisions.

---

## 2. Files and Directories

- `lending_data.csv`: Original dataset.
- `credit_risk_classification.ipynb`: Jupyter notebook for loan risk prediction.

---

## 3. Project Development Stages

i. **Data Loading and Exploration:**
   - Load loan data from `lending_data.csv`.
   - Explore and summarize the dataset to understand the variables.

ii. **Data Preprocessing:**
   - Encode categorical variables and scale numerical features.
   - Split the dataset into training and testing sets.

iii. **Model Building:**
   - Implement logistic regression models for loan risk prediction.
   - Evaluate model performance on the original data.

iv. **Resampling Techniques:**
   - Utilize Random OverSampling to address class imbalance.
   - Refit models with resampled training data.

v. **Evaluation and Comparison:**
   - Assess model performance using accuracy, precision, recall, and balanced accuracy.

---

## 4. Set Up and Execution

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/AnyasorG/credit-risk-classification.git
   cd credit-risk-classification

5. Ethical Considerations

- The dataset contains financial information, and care has been taken to ensure the privacy of individuals. All code is available publicly, promoting transparency in the analysis.

6. Data Source

- The dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

7. Code Source

- Parts of the code were adapted from documentation and resources such as:

    - scikit-learn documentation
    - pandas documentation
    - numpy documentation

8. License

- This project is open-source and is made available under the terms of the MIT License. For the full details of the MIT License, please refer to MIT [License](https://choosealicense.com/licenses/mit/).

9. Summary

- The project successfully develops and evaluates machine learning models for loan risk prediction, considering both the original data and resampled data to address class imbalance. The results and visualizations provide insights into the performance of the models.

11. Report

- The detailed written report file named loan_risk_prediction_report.md is located at [GitHub Repository] (https://github.com/AnyasorG/credit-risk-classification.git).

10. Author
- Godswill Anyasor 

