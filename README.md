# Credit_Cartd-_Fraud_Detection
# Overview
#### This project focuses on detecting fraudulent credit card transactions using machine learning. The initiative addresses the challenges of digital fraud in the era of online transactions, aiming to mitigate financial losses and enhance trust in financial systems.

# Objectives
#### Develop robust and accurate predictive models for real-time fraud detection.
#### Employ advanced machine learning techniques to identify patterns indicative of fraudulent behavior.
#### Provide actionable insights through a user-friendly web application for financial institutions and merchants.

# Key Features
#### Machine Learning Models: Utilized Gradient Boosting Machine (GBM), Logistic Regression, Naive Bayes, SVM, Random Forest, and others.
#### Web Interface: A Flask-based application that integrates the GBM model for real-time fraud detection.
#### Data Insights: Visual analytics on fraud distribution by gender, age, country, bank, etc.
#### Real-Time Predictions: Immediate feedback on transaction status—Fraud or Not Fraud.
#### Scalable Solution: Designed to handle large volumes of transactional data efficiently.

# Dataset
#### The dataset was sourced from Kaggle: [Credit Card Fraud Transaction Data](https://www.kaggle.com/datasets/anurag629/credit-card-fraud-transaction-data/data). It includes features such as transaction amount, merchant category, type of card, and more.

# Preprocessing Steps
#### Data Cleaning: Removed unnecessary columns and handled null values.
#### Data Standardization: Ensured consistency in date formats and numeric values.
#### Outlier Detection: Addressed outliers using the Interquartile Range (IQR) method.
#### Encoding: Converted categorical data to numerical format using One-Hot Encoding and Label Encoding.
#### Normalization: Scaled numeric features to a uniform range using Min-Max Scaling.

# Models and Results
| **Algorithm**           | **Accuracy** | **Precision (Fraud)** | **Recall (Fraud)** | **F1-Score** |
|-------------------------|--------------|------------------------|--------------------|--------------|
| Gradient Boosting (GBM) | 97.5%        | 0.87                   | 0.76               | 0.81         |
| Logistic Regression     | 96.8%        | 0.81                   | 0.73               | 0.77         |
| Naive Bayes             | 88.1%        | 0.38                   | 0.98               | 0.54         |
| SVM (RBF Kernel)        | 97.4%        | 0.89                   | 0.73               | 0.80         |
| Random Forest           | 97.4%        | 0.89                   | 0.73               | 0.80         |
| Multi-layer Perceptron  | 97.3%        | 0.82                   | 0.76               | 0.79         |

# Web Application
## Streamlit Interface:
#### We have built an interactive web interface using Streamlit for real-time fraud detection. This user-friendly web app allows users to input transaction data directly and get predictions immediately.

## Features:
#### Input Options: Users can enter transaction details manually in the provided input fields.
#### Real-Time Predictions: Once the transaction details are filled, the system predicts whether the transaction is fraudulent or not.
#### Visual Analytics: Visualizations are provided to analyze fraud trends by country, gender, bank, and age.
