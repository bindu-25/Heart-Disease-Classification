# Heart-Disease-Classification
Project Overview

This project predicts the risk of heart disease for an individual based on key health indicators. Using machine learning algorithms, the app provides a quick assessment to help users understand their heart health and take preventive measures.

Dataset

Source: Cleveland Heart Disease Dataset from UCI Repository

Number of Records: 303

Number of Features: 14

Target: target (0 = low risk, 1 = high risk)

Key Features:

Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Serum Cholesterol (chol)

Fasting Blood Sugar (fbs), Resting ECG (restecg), Max Heart Rate Achieved (thalach)

Exercise Induced Angina (exang), ST Depression (oldpeak), Slope of Peak Exercise ST Segment (slope)

Number of Major Vessels (ca), Thalium Stress Test Result (thal)

Objectives-

Predict heart disease risk using multiple machine learning models.

Identify key factors influencing heart health.

Deploy a Streamlit web application for interactive predictions.

Machine Learning Approach

Algorithms Used:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Naive Bayes

XGBoost

Performance Evaluation:

Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

Best Model: Logistic Regression with 86% training accuracy

Insights from Analysis:

Higher max heart rate (thalach) correlates with lower risk.

Higher ST depression (oldpeak) correlates with increased risk.

Key predictive features: thalach, oldpeak, cp, age, chol.

Web App

Built using Streamlit

Interactive interface for users to input their health data

Provides real-time prediction of heart disease risk

[Optional] Can be deployed online for public access

How to Run Locally:

# Clone repo
git clone <your-repo-link>

# Navigate into project folder
cd project-folder

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run healthy-heart-app.py

Note

This tool is for educational purposes only.

It does not replace professional medical advice. Please consult a doctor for health concerns.

Future Work

Include larger datasets for better generalization.

Add clustering to identify patient risk groups.

Enhance predictive performance using ensemble models and hyperparameter tuning.
