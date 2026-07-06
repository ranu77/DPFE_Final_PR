# DPFE_Final_PR

# PR_Final_Data_Preprocessing_Feature_Engineering

# Customer Credit Risk Data Preprocessing & Feature Engineering Project

## Project Overview

This project focuses on complete data preprocessing and feature engineering for a Customer Credit Risk dataset. The objective is to clean, transform, and prepare the dataset for Machine Learning by handling missing values, treating outliers, encoding categorical variables, scaling numerical features, applying feature transformations, and creating new features.

The final dataset is fully processed and ready for building a Loan Default Prediction Machine Learning model.

---

## Problem Statement

A fintech company has provided a Customer Credit Risk dataset collected from multiple sources. The objective is to preprocess the data and perform feature engineering so that the dataset becomes clean, consistent, and suitable for Machine Learning.

Target Variable:

- **default_flag**
  - 0 → No Default
  - 1 → Default

---

# Dataset Sources

The project demonstrates data collection from multiple sources:

- CSV File
- JSON File
- SQL Database
- Dummy API

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- ydata-profiling
- SQLite3
- Requests

---

# Project Workflow

## Part A - Conceptual Foundation

- Data Analysis
- Planning a Data Science Project
- Framing a Machine Learning Problem
- Tensors with NumPy Examples

---

## Part B - Data Acquisition

- Import CSV Dataset
- Read JSON File
- Fetch Data from SQL Database
- Fetch Data from API

---

## Part C - Data Understanding & Cleaning

- Dataset Information
- Statistical Summary
- Data Profiling
- Missing Value Handling
  - Simple Imputer
  - Most Frequent Imputation
  - Missing Indicator
  - Random Sample Imputation
  - KNN Imputer
  - MICE
  - Complete Case Analysis

---

## Part D - Outlier Handling

- Box Plot
- Z-Score Method
- IQR Method
- Percentile Method
- Winsorization

---

## Part E - Feature Engineering

### Variable Handling

- Mixed Variables
- Date & Time Features

### Encoding

- Ordinal Encoding
- Label Encoding
- One-Hot Encoding

### Numerical Encoding

- Binning
- Binarization
- Quantile Binning
- K-Means Binning

---

## Part F - Feature Scaling

- StandardScaler
- Normalizer
- MinMaxScaler
- MaxAbsScaler
- RobustScaler

---

## Part G - Feature Construction & Transformation

### Transformations

- Log Transformation
- Reciprocal Transformation
- Square Root Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation
- ColumnTransformer

### Feature Engineering

- Debt-to-Income Ratio
- Average Monthly Transactions
- Spending-to-Income Ratio

---

## Final Output

The final dataset contains:

- Cleaned Missing Values
- Treated Outliers
- Encoded Features
- Scaled Numerical Features
- Engineered Features
- Machine Learning Ready Dataset

---

# Project Structure

```
PR_Final_Data_Preprocessing_Feature_Engineering/
│
├── customer_credit_risk.csv
├── customer_metadata.json
├── credit_risk.db
├── Theory_Concepts_Data_Preprocessing_Project.pdf
├── PR_Final_Data_Preprocessing_Feature_Engineering.ipynb
├── customer_credit_risk_final.csv
├── README.md
└── screenshots/
```

---

# Video Demonstration

**Google Drive / YouTube Link:**

Paste your project explanation video link here.

Example:

https://drive.google.com/your-video-link

---

# Learning Outcomes

After completing this project, I learned to:

- Import datasets from multiple sources.
- Perform data cleaning and preprocessing.
- Handle missing values using different imputation techniques.
- Detect and treat outliers.
- Encode categorical and numerical variables.
- Apply feature scaling and transformations.
- Create meaningful features.
- Prepare datasets for Machine Learning.

---

# Author

**Name:** Devanshi Kanthariya

Course: Data Preprocessing & Feature Engineering
