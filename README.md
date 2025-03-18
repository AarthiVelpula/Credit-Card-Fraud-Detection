# Credit-Card-Fraud-Detection
Project Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions efficiently. The dataset contains transaction details such as amount, merchant information, timestamps, and other relevant attributes. The objective is to minimize false positives while ensuring high fraud detection accuracy.

Dataset Information
The dataset consists of two files:

Training Set: Used for training the machine learning model.
Test Set: Used for evaluating model performance and generating predictions.
Features in the Dataset:
trans_date_trans_time: Transaction date and time
cc_num: Credit card number
merchant: Merchant name
category: Type of transaction
amt: Transaction amount
first, last, gender, street, city, state, zip, lat, long: User details
city_pop: Population of the city
job: Occupation of the cardholder
dob: Date of birth
trans_num: Unique transaction ID
unix_time: Transaction timestamp
merch_lat, merch_long: Merchant's location
is_fraud: Target variable (1 for fraud, 0 for non-fraud)
Approach & Methodology
Data Preprocessing

Handled missing values
Encoded categorical variables
Scaled numerical features
Handling Class Imbalance

Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance fraud and non-fraud transactions
Feature Engineering

Removed unnecessary features
Standardized numerical columns for better performance
Model Selection & Training

Used Random Forest Classifier for classification
Tuned hyperparameters for improved accuracy
Evaluation Metrics

Accuracy Score
Confusion Matrix
Precision, Recall, and F1-score
Predictions on Test Data

Applied the trained model on the test dataset

Files in the Repository
Credit_Card_Fraud_Detection.ipynb → Jupyter Notebook with full implementation
fraud_test_predictions.csv → Final predictions for test data
README.md → Project description and instructions
