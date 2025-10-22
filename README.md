🫀 Heart Disease Prediction

This project focuses on predicting the presence of heart disease in patients using machine learning algorithms. By analyzing health-related features such as age, blood pressure, cholesterol, and others, the model aims to assist in early diagnosis and risk prediction.

📌 Project Overview

Goal: Build a machine learning model to predict heart disease presence.
Algorithms Used:
Logistic Regression
Support Vector Machine (SVM)
XGBoost
Dataset: UCI Heart Disease dataset (or equivalent)
Tools & Libraries:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost

📊 Features Considered

Age
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Serum Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting Electrocardiographic Results (restecg)
Maximum Heart Rate Achieved (thalach)
Exercise Induced Angina (exang)
ST Depression (oldpeak)
Slope of the peak exercise ST segment
Number of Major Vessels (ca)
Thalassemia (thal)

⚙️ Workflow

Data Preprocessing

Handling missing values
Encoding categorical variables
Feature scaling
Exploratory Data Analysis (EDA)

Visualizations for understanding data distribution and relationships
Model Building

Splitting dataset into training and testing sets
Training Logistic Regression, SVM, and XGBoost classifiers
Model Evaluation

Accuracy, Precision, Recall, F1-Score
Confusion Matrix
ROC-AUC Curve

✅ Results
Compared performance across all models.
XGBoost achieved the highest overall accuracy.
Logistic Regression and SVM provided interpretable and reliable outputs.

📦 Installation
To install the required libraries, run:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost
