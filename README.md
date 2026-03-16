# Telco Customer Churn Prediction

## Project Overview
This project analyzes customer churn behavior in a telecommunications company and builds a machine learning model to predict whether a customer is likely to churn.

Customer churn is a major challenge for telecom companies.  
The goal of this project is to identify patterns associated with churn and build a predictive model to help businesses retain customers.

---

## Dataset

The dataset includes customer information such as:

- Contract type
- Payment method
- Monthly charges
- Total charges
- Paperless billing
- Customer churn status

Target variable:

Churn Label

---

## Exploratory Data Analysis (EDA)

Key insights from the analysis:

- Customers with **month-to-month contracts** show the highest churn rate.
- Customers paying via **electronic check** tend to churn more frequently.
- Higher **monthly charges** are associated with increased churn probability.
- Customers using **paperless billing** show slightly higher churn rates.

---

## Model

A Logistic Regression model was used to predict customer churn.

Workflow:

- Data Cleaning
- Feature Encoding
- Train/Test Split
- Model Training
- Model Evaluation

---

## Model Performance

The model was evaluated using:

- Accuracy
- Confusion Matrix

The model achieved approximately **80% accuracy** in predicting customer churn.

---

## Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter / Google Colab

---

## Project Structure

telco-churn-project

- churn_analysis.ipynb
- README.md
- dataset