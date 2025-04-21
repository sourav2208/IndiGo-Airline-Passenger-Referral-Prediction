# IndiGo-Airline-Passenger-Referral-Prediction analysis using python

![Indigo Logo](https://github.com/sourav2208/IndiGo-Airline-Passenger-Referral-Prediction/blob/main/IndiGo-Logo-768x483.png)

## Objective
* To develop a classification model that predicts whether a passenger will refer IndiGo Airlines to others, based on their travel experience and demographic information.

## Problem Statement:
* Customer referrals are a strong indicator of brand loyalty and service satisfaction. This project aims to help IndiGo Airlines identify passengers who are likely to recommend the airline, enabling better-targeted marketing and customer retention strategies.

## Tools & Technologies Used:
* Python
* Pandas, NumPy for data manipulation
* Matplotlib, Seaborn for data visualization
* Scikit-learn for machine learning models
* Jupyter Notebook for experimentation

## Key Steps:
* Data Collection & Understanding:
  - The dataset contains features such as flight distance, in-flight service ratings, seat comfort, customer type, class of travel, and more.
  - The target variable is whether the passenger will refer the airline.

* Data Preprocessing:
  - Handled missing values and outliers.
  - Encoded categorical variables using Label Encoding and One-Hot Encoding.
  - Scaled numerical features using StandardScaler.

* Exploratory Data Analysis (EDA):
  - Identified key factors affecting customer referrals.
  - Visualized trends such as satisfaction vs referral, class of travel vs referral, etc.

* Model Building:
  - Trained and evaluated multiple models:
  - Logistic Regression
  - Decision Tree
  - Random Forest

* Model Evaluation:
  - Evaluated models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.
  - The best-performing model achieved high accuracy and F1-score, indicating strong predictive performance.
