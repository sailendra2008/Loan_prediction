
# Loan Prediction using Machine Learning

## Overview

This project predicts whether a loan application will be approved or not using Machine Learning techniques. The dataset contains applicant information such as income, education, marital status, loan amount, and credit history.

The goal is to build a classification model that can predict loan approval status based on applicant details.

## Dataset

The dataset contains the following features:

* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area

Target Variable:

* Loan_Status (Y = Approved, N = Rejected)

## Project Workflow

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Handled missing values using mode imputation
* Converted categorical variables into numerical values
* Processed the Dependents column
* Prepared data for model training

### 2. Exploratory Data Analysis (EDA)

* Generated correlation heatmaps
* Visualized Loan Amount distribution
* Visualized Applicant Income distribution
* Analyzed relationships between features

### 3. Model Building

Algorithm Used:

* Logistic Regression

Steps:

* Split data into training and testing sets
* Trained the model using training data
* Evaluated model performance on testing data

### 4. Results

* Model Accuracy: **78%**
* Successfully predicted loan approval status on unseen data

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

## Project Structure

```
Loan-Prediction/
│
├── Loan_Prediction.ipynb
├── README.md
├── train.csv
├── test.csv
└── submission.csv
```

## Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Random Forest Classifier
* XGBoost Classifier
* Cross Validation

## Learning Outcomes

Through this project, I learned:

* Data Cleaning
* Data Visualization
* Feature Engineering
* Classification Models
* Logistic Regression
* Model Evaluation
* Exploratory Data Analysis (EDA)

## Author

Sailendra Reddy

First-Year Mechanical Engineering Student

Interested in Machine Learning, AI, Python, and Engineering Applications.
