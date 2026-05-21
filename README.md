# DevelopersHub Corporation - Data Science & Analytics Internship Tasks

## 📌 Overview

This repository contains my completed tasks for the Data Science & Analytics Internship at DevelopersHub Corporation. I have completed 
***3 out of 5 tasks*** as required, focusing on data exploration, visualization, machine learning, and model evaluation using Python.

***Due Date:*** 5th June, 2026

---

## 📊 Completed Tasks

### ✅ Task 1: Iris Dataset Exploration
***Objective:*** Understand how to read, summarize, and visualize a dataset.

***What I did:***
- Loaded the Iris dataset using seaborn
- Displayed dataset structure (.shape, .columns, .head())
- Created visualizations:
  - Scatter plots to analyze relationships between variables
  - Histograms to examine data distribution
  - Box plots to detect outliers

***Results:***
- Found 3 flower species: Setosa, Versicolor, Virginica (50 samples each)
- Setosa has the smallest petals, Virginica has the largest
- No missing values in the dataset
- Petal length and width are highly correlated (0.96)

***Technologies:*** pandas, matplotlib, seaborn

---
### ✅ Task 4: Predicting Insurance Claim Amounts
***Objective:*** Estimate medical insurance claim amount based on personal data.

***What I did:***
- Trained Linear Regression model to predict charges
- Visualized how BMI, age, and smoking status impact insurance charges
- Evaluated using MAE and RMSE

***Results:***
- MAE: ~$4,200 (average prediction error)
- Smoking increases insurance cost by ~$23,000 on average
- Age and BMI also positively correlate with charges

***Technologies:*** pandas, scikit-learn, matplotlib, seaborn

---
### ✅ Task 2: Credit Risk Prediction
***Objective:*** Predict whether a loan applicant is likely to default on a loan.

***What I did:***
- Handled missing data using median and mode imputation
- Visualized key features (loan amount, income, education)
- Trained Logistic Regression and Decision Tree models
- Evaluated using accuracy and confusion matrix

***Results:***
- Model accuracy: ~78-82%
- Credit history is the strongest predictor of loan approval
- Higher applicant income increases approval chances
- Education level has moderate influence

***Technologies:*** pandas, scikit-learn, matplotlib, seaborn

---
