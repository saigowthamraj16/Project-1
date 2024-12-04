# Project-1
Project 1

# Telco Customer Churn Prediction

This repository contains the Telco Customer Churn Prediction project, which aims to analyze and predict customer churn in the telecommunications industry using machine learning techniques. The project includes data preprocessing, exploratory data analysis (EDA), and the application of multiple machine learning models to evaluate their effectiveness.

---

## Dataset

### File: telco-customer-churn.csv
This dataset includes 7,043 records of customers with the following features:
- *21 variables* (3 numerical, 17 categorical, and 1 text).
- Less than 0.1% missing values.
- Includes details like customer demographics, account information, and churn status.



## Project Overview

### Goals
1. Perform data preprocessing and exploratory data analysis.
2. Handle data imbalance using SMOTE.
3. Build and compare the performance of four machine learning models:
   - Naïve Bayes
   - Logistic Regression
   - Random Forest
   - XGBoost
4. Evaluate model performance using metrics:
   - Accuracy
   - Precision
   - Recall
   - F1-score
5. Identify the most significant features influencing customer churn.

### Key Findings
- *EDA Insights*: Reports generated using Sweetviz and Pandas Profiling provide an overview of correlations, data imbalances, and distributions. Check the sweetviz_comparison_report.html and ydata_profiling_report.html for details.
- *Highly Correlated Features*: Relationships between features such as Contract, MonthlyCharges, and tenure are critical in churn prediction.

---

## Folder Structure

```plaintext
├── data/
│   └── telco-customer-churn.csv      # Input dataset
├── reports/
│   ├── sweetviz_comparison_report.html  # Sweetviz EDA report
│   └── ydata_profiling_report.html      # Pandas Profiling EDA report
├── notebooks/
│   └── project_work.ipynb           # Jupyter notebook for the analysis
├── src/
│   ├── preprocess.py                # Preprocessing functions
│   ├── modeling.py                  # Machine learning model implementation
│   ├── evaluation.py                # Model evaluation metrics
│   
├── README.md                        # Project documentation