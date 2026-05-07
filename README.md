Healthcare Premium Prediction Project – GitHub README Template
Healthcare Premium Prediction
Project Overview

This project focuses on predicting annual healthcare insurance premiums using Machine Learning techniques. The goal was to build a robust regression model capable of accurately estimating insurance premium amounts based on demographic, lifestyle, and medical factors.

The project includes:

Data cleaning and preprocessing
Outlier treatment
Feature engineering
Multicollinearity handling
Model training and tuning
Error analysis
Model segmentation
Model deployment preparation
Business Problem

Insurance companies require accurate premium prediction systems to estimate customer risk fairly and efficiently. This project helps predict premium amounts based on customer health and financial information.

Dataset Information
Total Records: 50,000+
Total Features: 13
Features Included
Gender
Region
Marital Status
Physical Activity
Stress Level
Number of Dependants
BMI Category
Smoking Status
Employment Status
Income Level
Income
Medical History
Insurance Plan
Target Variable
Annual Premium Amount
Project Workflow
1. Data Preprocessing
Standardized column names
Removed missing values
Removed duplicate records
Treated outliers using business thresholds
Standardized categorical values
2. Exploratory Data Analysis
Boxplots for outlier detection
Histograms for distribution analysis
Analysis of categorical feature distributions
3. Feature Engineering
Created Risk Score feature from Medical History
Applied Label Encoding
Applied Min-Max Scaling
Removed multicollinearity using VIF analysis
4. Models Used
Linear Regression
Ridge Regression
XGBoost Regressor
5. Hyperparameter Tuning
RandomizedSearchCV
6. Error Analysis
Residual analysis
Threshold-based prediction analysis
Population segmentation based on age groups
7. Model Segmentation

Separate models were trained for:

Young population (<25 years)
Remaining population

Performance improved significantly after introducing Genetic Risk Score feature.

Model Performance
Final Results
Linear Regression: ~92% performance
XGBoost Regressor: ~98–99% performance
Significant improvement after segmentation and feature enhancement
Deployment Preparation
Exported trained models using Joblib
Saved scaler objects for production use
Streamlit Application

Streamlit

GitHub Repository

azadahmed1/ml-project-premium-prediction: Codebasics ML Couse health insurance prediction project

Tech Stack
Python
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Seaborn
Joblib
Key Learnings
Feature engineering for healthcare analytics
Importance of error analysis
Model segmentation for specialized populations
Impact of multicollinearity on regression models
Hyperparameter tuning and model optimization

Author

Azad Ahmed Machine Learning Engineer
