# Customer Churn Prediction

## Project Overview

This project uses machine learning to predict whether a customer is likely to churn based on their demographic information, services, contract details, and billing information.

## Dataset

The project uses the **Telco Customer Churn** dataset, containing customer information, services, billing details, and churn status.

* **Rows:** 7,032
* **Target:** Churn (Yes/No)
* **Problem Type:** Supervised Binary Classification

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Project Workflow

* Data loading and understanding
* Data cleaning
* Exploratory Data Analysis (EDA)
* Categorical encoding and numerical scaling
* Train-test split
* Machine learning model training
* Model evaluation
* Feature importance analysis
* Business insights

## Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |   78.75% |
| Decision Tree       |   71.07% |
| Random Forest       |   78.75% |
| XGBoost             |   76.83% |

## Key Insights

* Month-to-month customers show substantially higher churn than customers on longer-term contracts.
* Churned customers have lower median tenure than non-churned customers.
* Customers with higher monthly charges show higher churn.
* Fiber optic customers show higher churn compared with DSL and no-internet customers.
* Electronic check users show higher churn compared with other payment methods.
* Senior citizens have a higher churn proportion than non-senior customers.
* Male and female customers show similar churn patterns.

## Conclusion

The project demonstrates an end-to-end machine learning workflow for customer churn prediction, from data preprocessing and exploratory analysis to model training, evaluation, and business insights.
