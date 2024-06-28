# Logistic Regression for Predicting Heart Disease Risk

## Introduction
In the realm of healthcare analytics, the Logistic Regression for Predicting Heart Disease Risk project focuses on using logistic regression to predict the Ten-Year Coronary Heart Disease (CHD) risk based on various health-related features. By analyzing a dataset encompassing demographic and health parameters, this project aims to enhance early detection and management strategies for CHD.

## Features
- Implements logistic regression for binary classification of Ten-Year CHD risk.
- Utilizes a dataset containing features such as age, sex, smoking habits, cholesterol levels, blood pressure, and glucose levels.
- Includes data preprocessing steps including data cleaning, normalization, and splitting into training and testing sets.
- Evaluates model performance using accuracy metrics to gauge predictive efficacy.

## Usage
### Importing Necessary Modules and Dataset:
To start, import essential Python modules required for data analysis and machine learning, including `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`. The dataset used in this project is loaded using pandas' `read_csv` function, ensuring data accessibility and management.

### Data Preprocessing:
Perform initial data preprocessing steps to prepare the dataset for analysis. This includes handling missing values, renaming columns for clarity, and normalizing numerical features using `sklearn`'s `StandardScaler`.

### Building and Evaluating the Model:
Train a logistic regression model using `scikit-learn`'s `LogisticRegression` class, evaluate its performance on the test set using accuracy metrics, and visualize results using `seaborn` for clarity.

## Conclusion
This project demonstrates the application of logistic regression in predicting Ten-Year CHD risk based on demographic and health data. The achieved accuracy of 0.84 showcases the model's effectiveness in assisting healthcare professionals with early risk assessment and intervention strategies.
