# ml-project-premium-prediction
Health Insurance Premium Prediction App
Project Overview
This project is a Machine Learning-powered web application that predicts health insurance premiums based on user input. The app was developed using Streamlit for the frontend interface and a predictive model trained on a health insurance dataset. It was part of a course project guided by Codebasics.

Key Features
User-Friendly Interface: The app features an intuitive and interactive UI built using Streamlit.
Real-Time Predictions: Users can input their details and receive instant predictions on expected insurance premiums.
Data-Driven Insights: The predictive model analyzes various user parameters like age, BMI, smoking status, region, etc., to estimate the premium.
Deployed for Easy Access: The application can be easily deployed and accessed via any web browser.
Technologies Used
Frontend: Streamlit
Backend: Python
Machine Learning: Scikit-learn
Version Control: GitHub
Deployment: Can be hosted on platforms like Streamlit Cloud or Heroku
Dataset
The model was trained using a publicly available health insurance dataset containing features such as:

Age: Age of the insured person.
BMI: Body Mass Index, indicating the health condition.
Number of Children: Number of dependents.
Smoker: Indicates if the person smokes (Yes/No).
Region: The region where the person lives (e.g., northwest, southwest).
Charges: The insurance premium charges (used as the target variable).
How the App Works
User Input: The user enters information such as age, BMI, smoking status, and region.
Prediction: The input is passed through a pre-trained machine learning model, which predicts the insurance premium.
Display Result: The predicted premium is displayed instantly to the user.
Model Details
The machine learning model was built using Scikit-learn with the following steps:

Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
Model Training: The model was trained using a regression algorithm (e.g., Linear Regression or Random Forest Regressor).
Model Evaluation: Performance metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were used for evaluation.
