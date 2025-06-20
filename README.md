# Predicting Coronary Artery disease with Random Forest, Multi-layer Perceptron and Logistic Regression Models

This project focuses on the prediction of cardiovascular diseases (CVDs) using machine learning models. The dataset used for this project contains various features like age, weight, cholesterol levels, blood pressure, and other health indicators to predict the presence of heart disease. The primary objective is to use different machine learning models to accurately classify whether a patient is likely to have a heart disease or not.

Models Used:
Random Forest: A powerful ensemble model that combines the results of multiple decision trees to improve prediction accuracy.

Logistic Regression: A commonly used algorithm for binary classification, which estimates the probability of the presence or absence of a disease.

Multi-layer Perceptron: A type of artificial neural network that uses layers of neurons to process data and make predictions.

Dataset:
The dataset is sourced from Kaggle and contains 70,000 data points with 13 features such as age, cholesterol level, and smoking habits. The dataset is well-balanced with an equal ratio of healthy and unhealthy hearts, allowing for reliable model evaluation and testing.

Methodology:
Data Preprocessing: The dataset is cleaned by removing irrelevant columns (e.g., ID), converting age from days to years, and performing necessary transformations.

Feature Engineering: Additional features such as BMI (Body Mass Index) are derived from available data like height and weight to enhance model performance.

Model Training and Evaluation: The data is split into training and test sets, and models are trained to predict the presence of cardiovascular diseases. Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated to assess model performance.

Key Findings:
The Random Forest model achieved a high accuracy of 98% on the training set and 71% on the test set.

Logistic Regression and Multi-layer Perceptron models also showed comparable performance with accuracy values around 72-73%.

This project demonstrates the application of machine learning techniques in healthcare, specifically in early diagnosis and risk prediction for cardiovascular diseases, ultimately aiming to assist in more accurate and timely medical decision-making.

