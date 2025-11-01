# Project-3-Machine-Learining
## Overview
This project applies machine learning techniques to two distinct problems:
  1. Predicting customer credit scores for improved credit risk assessment.
  2. Predicting video game global sales performance based on multiple market features.

# 1. Credit Score Classification

## Goal:
Develop a classification model to predict a customer’s creditworthiness category — Good, Standard, or Poor — using demographic, financial, and behavioral features.

## Approach:
Explored and prepared the data by handling missing values and encoding categorical variables.
Built multiple classification models (Logistic Regression, KNN).
Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

# 2. Video Game Sales Prediction

## Goal:
Build a regression model to predict the Global Sales of video games based on platform, genre, publisher, and regional sales data.

## Approach:

Cleaned and prepared data by managing missing values and normalizing numeric features.
Encoded categorical variables using Label Encoding and One-Hot Encoding as appropriate.
Built and compared multiple regression models (Linear Regression, KNN).
Evaluated models with R², RMSE.

## Data Preparation:
Handled missing and inconsistent values.
Removed or treated outliers when necessary.
Applied encoding techniques for categorical features.
Used feature scaling (StandardScaler) to normalize numeric variables.
Split datasets into training and testing subsets for model evaluation.

## Tools Used:
Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
