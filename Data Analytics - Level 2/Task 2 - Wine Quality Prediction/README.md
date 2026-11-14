# Wine Quality Prediction Using Machine Learning

## Internship Details
- **Organization:** Oasis Infobyte
- **Internship Track:** Data Analytics
- **Level:** Level 2
- **Task:** Task 2 – Wine Quality Prediction
- **Intern:** Saurabh Shukla

## Project Overview

This project focuses on predicting wine quality using Machine Learning classification algorithms.

The objective is to analyse the physicochemical properties of red and white wines and classify them into three quality categories: Low, Medium and High.

The project uses multiple classification models and compares their performance to identify the most suitable model for wine quality prediction.

## Dataset Information

**Dataset:** UCI Wine Quality Dataset

Two datasets are used:
- `winequality-red.csv`
- `winequality-white.csv`

The datasets contain physicochemical measurements of red and white wines along with quality scores provided by human tasters.

### Features Used
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Wine Type

**Target Variable:** Wine Quality

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Importing Libraries
2. Loading Red and White Wine Datasets
3. Data Cleaning and Preprocessing
4. Handling Duplicate Records
5. Exploratory Data Analysis (EDA)
6. Feature Distribution Analysis
7. Correlation Analysis
8. Handling Class Imbalance
9. Feature Engineering and Quality Binning
10. Stratified Train-Test Split (80:20)
11. Model Training and Hyperparameter Tuning
12. Model Evaluation
13. Confusion Matrix Analysis
14. Feature Importance Analysis
15. Model Comparison

## Machine Learning Models

Three classification algorithms were implemented:

- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

A Dummy Classifier was also used as a baseline for comparison.

## Wine Quality Classification

The original quality scores were grouped into three categories:

| Class | Quality Score | Category |
|---|---|---|
| 0 | 3, 4, 5 | Low |
| 1 | 6 | Medium |
| 2 | 7
