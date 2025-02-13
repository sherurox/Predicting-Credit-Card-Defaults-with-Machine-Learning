# Predicting-Credit-Card-Defaults-with-Machine-Learning

This repository contains the implementation and analysis of predicting credit card defaults using machine learning techniques. The research explores logistic regression and Naïve Bayes classifiers on a dataset containing credit card transaction and payment behavior. The study aims to assist financial institutions in credit risk assessment by developing predictive models that analyze key features related to credit card usage.

# Features

Exploratory Data Analysis (EDA) with visualizations
Data preprocessing, including handling missing values and feature engineering
Implementation of Logistic Regression and Naïve Bayes models
Performance evaluation using metrics such as accuracy, precision, recall, and F1-score
Comparison of models for predictive effectiveness

#Dataset
The dataset used for this study was sourced from Kaggle and contains credit card usage and payment behavior data. It includes various attributes such as:

Demographic details (age, gender, marital status, education level)
Financial data (credit limit, bill amounts, previous payments)
Payment history (delinquency records over six months)
<img width="708" alt="Screenshot 2025-02-13 at 3 50 15 PM" src="https://github.com/user-attachments/assets/5febac04-3b9b-4e64-9395-e17e2bf1b7e6" />


#Exploratory Data Analysis (EDA)
EDA was conducted to understand the dataset’s distribution and identify important features. Key insights include:

Class Imbalance: Majority of users do not default, leading to imbalance in labels.
Feature Correlation: Payment history and credit utilization significantly impact default prediction.
<p align="center">
  <img src="https://github.com/user-attachments/assets/32e0bd35-7d69-4881-9a14-38a88d4ae797" width="600" />
  <img src="https://github.com/user-attachments/assets/5ef8cbf1-fa41-44b3-b13b-37625e201297" width="600" />
  <img src="https://github.com/user-attachments/assets/c31acd06-aef3-45bf-841c-7f69328c5ec7" width="600" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5524f64-74b1-421a-b4d6-a53a03723b51" width="600" />
  <img src="https://github.com/user-attachments/assets/cece486e-2edc-41c7-b517-5322d9b3b682" width="600" />
</p>

# Models Implemented
Two machine learning models were used:

1️⃣ Logistic Regression: A linear classification model effective for binary classification tasks.
2️⃣ Naïve Bayes Classifier: A probabilistic classifier that assumes independence among features.

# Conclusion
This research demonstrates that Logistic Regression is an effective model for predicting credit card defaults. The findings emphasize the importance of payment history and credit utilization in risk assessment. This work can help financial institutions improve risk management strategies.

### Performance Comparison

| Model               | Accuracy  | Precision | Recall  | F1-Score |
|---------------------|----------|----------|--------|----------|
| **Logistic Regression** | **93.59%** | High | High | High |
| **Naïve Bayes**    | 85.88%   | Moderate | Moderate | Moderate |

# Authors & Acknowledgments
This research was conducted by Shreyas Khandale (me), 
Prathamesh Patil (https://github.com/PrathameshPatil547), and 
Rohan Patil (https://github.com/rohanpatil2), published in IJRASET, October 2023.

🔗 Paper Link: Predicting Credit Card Defaults with Machine Learning
https://www.ijraset.com/best-journal/predicting-credit-card-defaults-with-machine-learning













