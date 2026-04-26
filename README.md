# DevelopersHub Corporation — Data Science & Analytics Internship

## Overview
This repository contains all 5 Data Science & Analytics internship tasks completed at DevelopersHub Corporation. Each task covers a different aspect of data science including EDA, classification, regression, and business insight extraction.

---

## Tasks Summary

| Task | Project | Algorithm | Result |
|------|---------|-----------|--------|
| Task 1 | Iris Dataset EDA & Visualization | EDA Only | 4 visualizations |
| Task 2 | Credit Risk Prediction | Logistic Regression | 78.86% accuracy |
| Task 3 | Bank Customer Churn Prediction | Random Forest | 86.45% accuracy |
| Task 4 | Insurance Charges Prediction | Linear Regression | R² = 0.7833 |
| Task 5 | Personal Loan Acceptance | Decision Tree | 98.08% accuracy |

---

## Task Details

### Task 1 — Iris Dataset EDA & Visualization
- Loaded and explored the classic Iris dataset (150 rows × 5 columns)
- Created scatter plots, histograms, box plots, and correlation heatmap
- **Key Finding:** Petal measurements are the strongest species differentiators (0.96 correlation)

### Task 2 — Credit Risk Prediction
- Predicted loan approval/rejection using Logistic Regression
- Handled 7 columns with missing values
- **Key Finding:** 25 false positives represent real financial risk — approved applicants who may default

### Task 3 — Bank Customer Churn Prediction
- Identified customers likely to leave the bank using Random Forest
- Analyzed churn by geography, age, and balance
- **Key Finding:** Germany has double the churn rate (32%) vs France/Spain (16%). High-balance customers churn more

### Task 4 — Insurance Charges Prediction
- Predicted medical insurance costs using Linear Regression
- Visualized impact of BMI, age, and smoking on charges
- **Key Finding:** Smokers pay 5x more than non-smokers. BMI + smoking is the highest risk combination

### Task 5 — Personal Loan Acceptance Prediction
- Predicted which customers accept personal loan offers using Decision Tree
- Achieved 98.08% accuracy with near-perfect confusion matrix
- **Key Finding:** Education (0.45) and Income (0.32) are the top predictors. Bank should target high-income graduates

---

## Technologies Used
- **Python** — Core programming language
- **Pandas & NumPy** — Data manipulation
- **Scikit-learn** — Machine learning models
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Development environment

---

## Repository Structure
├── Task-1-Iris-EDA/
│   ├── iris_task1.ipynb
│   └── raw_data/
├── Task-2-Credit-Risk/
│   ├── credit_risk_task2.ipynb
│   └── raw_data/
├── Task-3-Customer-Churn/
│   ├── churn_task3.ipynb
│   └── raw_data/
├── Task-4-Insurance-Charges/
│   ├── insurance_task4.ipynb
│   └── raw_data/
└── Task-5-Personal-Loan/
├── loan_task5.ipynb
└── raw_data/

---

**Intern:** Muneeb Ur Rehman  
**Internship:** DevelopersHub Corporation — Data Science & Analytics  
**Email:** mu181842@gmail.com
