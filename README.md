# Customer-churn-prediction
End-to-End Customer Churn Prediction with Random Forest and Keras
End-to-End Customer Churn Prediction with Random Forest and Keras
📌 Project Overview

This project builds an end-to-end machine learning pipeline to predict customer churn using the Telco Customer Churn Dataset
.
We compare classical machine learning models (Random Forest, Logistic Regression) with a deep learning model (Keras) that uses embedding layers for categorical features and class weights to handle imbalance.

The goal is to:

Predict churn with high recall and F1-score

Identify key drivers of churn

Provide actionable insights (e.g., targeting top X% high-risk customers for retention offers)

📂 Dataset

Telco Customer Churn Dataset

Source: Kaggle

Contains 7,043 customer records with 21 features (demographics, services, account info, etc.)

Target variable: Churn (Yes/No)

🔑 Key Steps in the Pipeline

Exploratory Data Analysis (EDA)

Summary statistics, distributions, and churn rates

Visualization of categorical vs churn relationships

Data Preprocessing

Handling missing values (imputation)

Encoding categorical features (One-Hot for ML, Embeddings for Keras)

Scaling numerical features

Train-test split

Modeling

Classical ML: Random Forest, Logistic Regression

Deep Learning: Neural Network in Keras with Embedding Layers + Class Weights

Evaluation Metrics

Accuracy, Precision, Recall, F1-score

ROC-AUC curves

Interpretability & Insights

Feature importance (Random Forest)

Customer churn probability ranking

Target top 10% high-risk customers for retention offers

📊 Results

Random Forest: Balanced performance with good interpretability

Keras Neural Network: Comparable or better recall, especially on minority churn class

Actionable Business Strategy: Using predicted churn probabilities, businesses can target the top decile of high-risk customers with retention offers
