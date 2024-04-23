# Online Payments Fraud Detection Using Logistic Regression and SMOTE
## Overview
This project aims to develop a fraud detection system for online payments using logistic regression and the Synthetic Minority Over-sampling Technique (SMOTE). Fraudulent transactions in online payments pose a significant threat to the security and integrity of digital financial systems. However, detecting fraud is challenging due to the imbalance between fraudulent and legitimate transactions in the dataset. This project addresses the imbalance issue by applying SMOTE to create synthetic samples of the minority class, thereby balancing the dataset. I then train a logistic regression model to classify transactions as fraudulent or legitimate based on their features.

## Dataset
The dataset used in this project is the Online Payments Fraud Detection Dataset, which contains transaction data from an online payments system. The dataset includes features such as transaction amount, type of transaction, and timestamp, along with a binary label indicating whether the transaction is fraudulent or legitimate.

## Methodology
### Data Preprocessing:
Handle missing values and encode categorical variables.
Use SMOTE to address class imbalance by oversampling the minority class.
### Model Training:
Split the resampled data into training and testing sets.
Train a logistic regression model on the balanced training data.
### Model Evaluation:
Evaluate the logistic regression model on the test set to assess its performance.
Compute evaluation metrics such as accuracy, precision, recall, and F1-score.
### Results
The logistic regression model trained on the balanced dataset achieved an accuracy of 92% on the test set. The model demonstrates robust performance in identifying fraudulent transactions, effectively leveraging SMOTE to mitigate class imbalance.
