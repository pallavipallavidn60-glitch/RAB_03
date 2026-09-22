# 🚀 RAB Tech Academy – Task 04
## Supervised Classification Modeling & Hyperparameter Tuning

### 📌 Project Overview

This project is part of my **RAB Tech Academy Machine Learning Internship – Task 04**.

The objective of this task is to build and evaluate a supervised machine learning pipeline for **customer churn prediction**. Multiple classification algorithms are trained, optimized using hyperparameter tuning, and compared using different evaluation metrics.

The project demonstrates the complete machine learning workflow from model training and cross-validation to performance comparison and model serialization.

---

## 🎯 Objectives

- Build a supervised machine learning classification pipeline
- Train and compare multiple classification algorithms
- Perform hyperparameter optimization using `GridSearchCV`
- Apply Stratified K-Fold Cross-Validation
- Evaluate models using multiple performance metrics
- Generate confusion matrices
- Analyze ROC-AUC curves
- Select the best-performing model
- Save the trained model for future predictions

---

## 📊 Dataset

The project uses a customer churn dataset containing information such as:

- Customer ID
- Tenure
- Support Tickets
- Monthly Spending
- Last Login Days
- Plan Type
- Churn Status

### Target Variable

The target variable is:

```text
churned
