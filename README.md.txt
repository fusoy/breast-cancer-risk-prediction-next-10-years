# Breast Cancer Survival Prediction using Machine Learning and Survival Analysis

## Project Overview
This project predicts breast cancer patient mortality risk using Machine Learning and Survival Analysis techniques.

The objective is to identify important clinical factors influencing survival and build predictive models to support treatment planning and patient prognosis.

---

## Objectives
- Perform Exploratory Data Analysis (EDA)
- Predict mortality risk using Machine Learning
- Analyze survival trends
- Identify important medical factors

---

## Dataset Features
Some important variables:

- Age at Diagnosis
- Tumor Size
- Tumor Stage
- Mutation Count
- Nottingham Prognostic Index
- Lymph Nodes Examined Positive
- Molecular Subtypes

Target:
- Mortality Risk

---

## Data Preprocessing
Performed:

- Removed Patient ID
- Handled missing values using Median Imputation
- Encoded categorical variables
- Feature scaling
- Removed leakage columns:
  - Overall Survival Status
  - Relapse Free Status
  - Overall Survival (Months)

---

## Exploratory Data Analysis (EDA)

Performed:

- Dataset summary
- Missing value analysis
- Age distribution
- Survival status visualization
- Correlation heatmap
- Pairplot
- Feature importance analysis

---

## Machine Learning Models

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 71.9% |
| SVM | 74.7% |
| Decision Tree | 68.9% |

Best Model:
Support Vector Machine (SVM)

---

## Survival Analysis

Implemented:

- Kaplan-Meier Survival Curve
- Cox Proportional Hazards Model

Findings:

- Age increased mortality risk
- Tumor Stage increased mortality risk
- Tumor Size affected survival

---

## Technologies Used

Python

Libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Lifelines
- Plotly

---

## Project Outcomes

Built an end-to-end healthcare machine learning pipeline for breast cancer survival prediction.

---

## Author

Yoosuf Mohammed