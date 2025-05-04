# Fraud_Detection_System
Fraud Detection System using Logistic Regression

This project demonstrates how to build a fraud detection system using machine learning with the Logistic Regression algorithm. It uses the popular credit card fraud dataset and handles class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

**Dataset**
The dataset used is creditcard.csv, which includes transactions labeled as:

0: Legitimate

1: Fraudulent

Make sure the dataset is placed in the same directory as the notebook or script.

**Tools & Libraries Used**
Python

Pandas & NumPy

Scikit-learn

imbalanced-learn (for SMOTE)

**How It Works**
Data Preprocessing:

Scales the Amount feature.

Drops the Time feature.

**Train-Test Split:**

Data is split into training and test sets.

**Balancing with SMOTE:**

The training data is balanced using SMOTE to handle class imbalance.

**Model Training:**

A Logistic Regression model is trained on the balanced data.

**Evaluation:**

Accuracy and classification report are generated.

**Custom Prediction:**

A test function allows prediction for any individual transaction.

**Results**
The model prints:

**Accuracy**

Classification report showing precision, recall, and F1-score for both classes.
