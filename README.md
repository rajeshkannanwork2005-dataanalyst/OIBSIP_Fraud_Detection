# Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent transactions using Machine Learning techniques and data analysis.

The workflow includes preprocessing transaction data, handling class imbalance using SMOTE, training a Logistic Regression model, and evaluating performance.

---

## Objective

To classify transactions as fraudulent or non-fraudulent and improve fraud detection accuracy.

---

## Dataset

Credit Card Transaction Dataset

Features:
- Time
- Amount
- V1–V28 transformed variables
- Class (Target)

Class:
- 0 → Non-Fraud
- 1 → Fraud

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## Project Workflow

### 1. Data Loading
- Imported transaction dataset

### 2. Data Cleaning
- Checked missing values
- Removed incomplete records

### 3. Exploratory Data Analysis
- Statistical summary
- Fraud distribution analysis

### 4. Data Balancing
- Applied SMOTE technique

### 5. Model Training
- Logistic Regression

### 6. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Key Insights

- Original dataset contained class imbalance.
- SMOTE improved class distribution.
- Logistic Regression produced strong classification performance.
- Confusion matrix showed effective fraud detection.

---

## Results

Model evaluation was performed using:
- Precision
- Recall
- F1 Score
- Accuracy

---

## How to Run

1. Clone repository

git clone <repo-link>

2. Install dependencies

pip install -r requirements.txt

3. Open notebook in Google Colab

---

## Internship

Completed as part of OASIS INFOBYTE Internship.
