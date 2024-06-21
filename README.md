# Online Payment Fraud Detection Model

## Introduction
Fraudulent online payments have become a significant concern for e-commerce platforms and financial institutions. To address this issue, we have developed a machine learning model that detects fraudulent transactions with high accuracy. This markdown provides an overview of the model, including the dataset used, preprocessing steps, model selection, and evaluation metrics.

## Dataset
The dataset used for this project is sourced from Kaggle and can be accessed [here](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection?resource=download). It contains various features related to online transactions that help in identifying potential fraud.

## Data Preprocessing
Before training the model, the dataset underwent several preprocessing steps:

1. **Data Cleaning**: Handled missing values and removed any duplicates.
2. **Feature Encoding**: Converted categorical features to numerical values using techniques like one-hot encoding.
3. **Feature Scaling**: Standardized the numerical features to ensure they are on a similar scale.

## Model Selection
Several machine learning algorithms were evaluated for this task, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- Support Vector Machines (SVM)
- Neural Networks

## Model Evaluation
The performance of each model was assessed using the following metrics:

- **Accuracy**: The proportion of correctly identified transactions (both fraud and non-fraud).
- **Precision**: The proportion of true fraud cases among the identified fraud cases.
- **Recall**: The proportion of actual fraud cases that were correctly identified.
- **F1 Score**: The harmonic mean of precision and recall, providing a balance between the two.
