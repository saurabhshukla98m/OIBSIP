# Credit Card Fraud Detection Using Machine Learning

## Internship Details
- **Organization:** Oasis Infobyte
- **Internship Track:** Data Analytics
- **Level:** Level 2
- **Task:** Task 3 – Credit Card Fraud Detection
- **Intern:** Saurabh Shukla

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

The main challenge is class imbalance because fraudulent transactions represent only a very small percentage of all transactions.

The objective is to build and evaluate classification models that can identify fraudulent transactions while minimising missed fraud cases and unnecessary false alarms.

## Dataset Information

- **Dataset:** credit_card_fraud_10k.csv
- **Total Transactions:** 10,000
- **Fraudulent Transactions:** 151
- **Fraud Percentage:** Approximately 1.5%
- **Target Variable:** is_fraud

### Features Used
- Amount
- Transaction Hour
- Merchant Category
- Foreign Transaction
- Location Mismatch
- Device Trust Score
- Velocity Last 24 Hours
- Cardholder Age

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Project Workflow

1. Data Loading and Inspection
2. Class Imbalance Analysis
3. Exploratory Data Analysis (EDA)
4. Transaction Amount Analysis
5. Transaction Time Analysis
6. Feature Analysis
7. Data Preprocessing
8. Stratified Train-Test Split
9. Handling Class Imbalance
10. SMOTE and Class Weight Techniques
11. Logistic Regression
12. Random Forest Classification
13. Model Evaluation
14. Confusion Matrix Analysis
15. ROC-AUC and Precision-Recall Curves
16. 5-Fold Cross-Validation
17. Threshold Optimisation
18. Feature Importance Analysis
19. Model Scalability Analysis

## Machine Learning Models

The following models were implemented:

- Logistic Regression
- Random Forest Classifier
- Dummy Classifier (Baseline)

### Class Imbalance Techniques
- Class Weight Balancing
- SMOTE / SMOTENC
- Stratified Train-Test Split

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- PR-AUC (Average Precision)
- Confusion Matrix

Recall and Precision-Recall AUC were given special importance because fraud detection involves highly imbalanced data.

## Key Insights

- Fraudulent transactions account for approximately 1.5% of the dataset.
- Fraud is concentrated between midnight and 3:59 AM.
- Foreign transactions and location mismatches show higher fraud rates.
- Low device trust scores are associated with increased fraud risk.
- Transactions involving five or more transactions within 24 hours show higher fraud rates.
- Transaction amount, cardholder age and merchant category have relatively low predictive importance.
- Random Forest performs better than Logistic Regression at identifying important threshold-based fraud patterns.

## Model Optimisation

The project also explores:

- Decision threshold optimisation using F2-score.
- Out-of-fold predictions.
- Five-fold cross-validation.
- Feature importance and permutation importance.
- Model prediction speed and scalability.

## Conclusion

This project demonstrates how Machine Learning can be applied to detect fraudulent credit card transactions.

It highlights the importance of handling imbalanced datasets and selecting appropriate evaluation metrics rather than relying only on accuracy.

The analysis provides practical experience in data preprocessing, exploratory data analysis, classification modelling, model evaluation and fraud detection strategies.

---

**Created by Saurabh Shukla | Oasis Infobyte Data Analytics Internship**
