# Credit Card Fraud Detection using Machine Learning

## Overview

This project implements a complete machine learning pipeline to detect fraudulent credit card transactions using a real-world dataset containing more than 284,000 transactions.

The main challenge in this dataset is severe class imbalance, where fraudulent transactions represent only a small percentage of the total data. To address this issue, the project applies data preprocessing, class balancing techniques, and multiple machine learning models to improve fraud detection performance.

---

## Objectives

• Detect fraudulent credit card transactions using machine learning  
• Handle extreme class imbalance in financial data  
• Compare performance of multiple classification models  
• Evaluate models using appropriate metrics for fraud detection  

---

## Dataset

The dataset contains anonymized credit card transaction data.

Key characteristics:

Total transactions: 284,807  
Fraudulent transactions: 492  
Features: 30 (including anonymized PCA components)

The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling
5. Handling Class Imbalance using SMOTE
6. Model Training
7. Model Evaluation
8. Visualization of Results

---

## Machine Learning Models Implemented

The following models were trained and compared:

• Logistic Regression  
• Decision Tree  
• K-Nearest Neighbors (KNN)  
• Random Forest  

Random Forest achieved the best performance due to its ability to capture complex patterns in the data.

---

## Evaluation Metrics

Because fraud detection focuses on minimizing missed fraud cases, the models were evaluated using:

• Confusion Matrix  
• Precision  
• Recall  
• F1 Score  
• ROC Curve  
• Precision-Recall Curve  

Special attention was given to **Recall**, which measures how many fraudulent transactions were correctly detected.

---

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Imbalanced-Learn (SMOTE)  
Jupyter Notebook

---

## Results

The models successfully detected fraudulent transactions while handling the dataset’s extreme imbalance.

Random Forest provided the strongest performance with improved recall and balanced precision.

---

## Applications

This system can be applied in:

• Banking fraud detection systems  
• Online payment security  
• Financial risk monitoring  
• Transaction anomaly detection  

---

## Future Improvements

• Implement Deep Learning models  
• Apply anomaly detection algorithms  
• Use real-time fraud detection pipelines  
• Deploy as an API-based fraud detection service  

---

