# Customer Churn Prediction

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project aims to predict whether a customer is likely to leave a telecom company based on customer demographics, account information, and service usage patterns.

Using Machine Learning techniques, multiple classification models were trained and evaluated to identify the best-performing model for churn prediction.

---

## Problem Statement

The objective of this project is to build a machine learning model that can predict customer churn and help telecom companies take proactive measures to retain customers.

Target Variable:

* Churn = Yes (Customer leaves)
* Churn = No (Customer stays)

---

## Dataset

Dataset: Telco Customer Churn Dataset

Features include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib

---

## Machine Learning Workflow

### 1. Data Collection

Loaded the Telco Customer Churn dataset.

### 2. Data Cleaning

* Handled missing values
* Removed unnecessary columns
* Converted data types

### 3. Exploratory Data Analysis (EDA)

Performed:

* Target variable analysis
* Feature distribution analysis
* Correlation analysis
* Customer behavior analysis

### 4. Data Preprocessing

* Label Encoding
* One-Hot Encoding
* Feature Scaling using StandardScaler
* Train-Test Split

### 5. Model Building

The following machine learning models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

### 6. Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Score

### 7. Hyperparameter Tuning

Performed using GridSearchCV for XGBoost to improve model performance.

### 8. Feature Importance Analysis

Identified the most influential features contributing to customer churn.

### 9. Model Saving

The final trained model was saved using Joblib.

---

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 81%      |
| KNN                 | 76%      |
| Decision Tree       | 77%      |
| Random Forest       | 78%      |
| XGBoost             | 80%      |

### Best Performing Model

Logistic Regression achieved the highest test accuracy of approximately 81%.

---

## Key Insights

* Customers with month-to-month contracts are more likely to churn.
* Customers with higher monthly charges show higher churn rates.
* Longer tenure customers are less likely to leave.
* Contract type and tenure are among the most important features influencing churn.

---

## Business Impact

This model can help telecom companies:

* Identify high-risk customers
* Improve customer retention strategies
* Reduce customer acquisition costs
* Increase long-term revenue

---

## Project Structure

```text
customer-churn-prediction/
│
├── README.md
├── dataset.csvc
├── churn_model.pkl
└── customer-churn-prediction.ipyn
```

---


## Author

Kunal Singh

Aspiring Machine Learning Engineer focused on building practical end-to-end ML projects and solving real-world business problems.
