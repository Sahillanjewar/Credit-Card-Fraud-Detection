# Credit-Card-Fraud-Detection
Machine Learning project to detect fraudulent credit card transactions using classification algorithms and data analysis techniques in Python.
# Credit Card Fraud Detection

## Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning algorithms. Credit card fraud detection is a critical problem in financial systems, where identifying fraudulent activities quickly helps prevent financial losses.

The model analyzes transaction patterns and classifies transactions as **fraudulent or legitimate**.

---

## Dataset

The dataset contains credit card transactions made by European cardholders.

Features include:

- Time
- Transaction Amount
- PCA-transformed features (V1, V2, V3 ... V28)
- Class (Target Variable)

Target Variable:
- 0 → Legitimate Transaction
- 1 → Fraudulent Transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Handling Imbalanced Data
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Fraud Detection

---

## Machine Learning Models Used

- Logistic Regression
- Random Forest
- Decision Tree
- Isolation Forest

---

## Model Evaluation Metrics

Due to class imbalance, the following metrics are used:

- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Key Insights

- Fraudulent transactions represent a very small portion of the dataset.
- Feature scaling improves model performance.
- Random Forest achieved the best detection accuracy.

---

## Results

The model successfully detects fraudulent transactions with high precision and recall while minimizing false positives.

---

