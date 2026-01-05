# customer-churn-analysis-ml
Customer churn analysis and machine learning model evaluation using Python and scikit-learn
# Customer Churn Analysis & Model Evaluation

## Overview
This project focuses on evaluating multiple machine learning models for
customer churn analysis. Instead of emphasizing high accuracy, the goal
is to understand model behavior, data limitations, and real-world ML challenges.

## Dataset
- Customer demographic and service-related data
- Target variable: Churn (Yes / No)

## Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Gradient Boosting

## Model Performance Summary
All models achieved accuracy between **47%–50%** with ROC–AUC ≈ **0.49**.
This indicates weak predictive signal in the dataset rather than modeling errors.

## Key Learnings
- Data quality and feature relevance matter more than algorithm choice
- Accuracy alone is misleading for churn prediction problems
- Ensemble models handled feature interactions better but were still limited

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Conclusion
This project demonstrates honest model evaluation and highlights the
importance of understanding data limitations in real-world machine
learning applications.
