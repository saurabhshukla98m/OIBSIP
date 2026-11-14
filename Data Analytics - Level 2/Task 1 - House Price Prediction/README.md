# House Price Prediction Using Linear Regression

## Internship Details
- **Organization:** Oasis Infobyte
- **Internship Track:** Data Analytics
- **Level:** Level 2
- **Task:** Task 1 – House Price Prediction
- **Intern:** Saurabh Shukla

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques, primarily Linear Regression.

The objective is to understand how different house features, such as area, location, number of bedrooms, bathrooms, floors, condition and house age, relate to property prices.

## Dataset Information

- **Dataset:** House_Price_Prediction_Dataset.csv
- **Total Records:** 2,000 houses
- **Total Columns:** 10
- **Target Variable:** Price

### Features Used
- Area
- Bedrooms
- Bathrooms
- Floors
- Location
- Condition
- Garage
- YearBuilt

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Loading and Inspection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Feature Engineering
6. Categorical Encoding
7. Correlation Analysis
8. Train-Test Split (80:20)
9. Linear Regression Model Building
10. Model Evaluation
11. Residual Analysis
12. Ridge and Lasso Regression
13. Random Forest Comparison

## Model Performance

| Model | R² Score |
|---|---:|
| Linear Regression | -0.007 |
| Ridge Regression | -0.002 |
| Lasso Regression | -0.002 |
| Random Forest | -0.02 |

## Key Findings

- The dataset contained no missing values or duplicate records.
- Area and other features showed almost no correlation with house prices.
- Linear Regression achieved an R² score close to zero.
- Ridge and Lasso regularization did not significantly improve performance.
- Random Forest also failed to identify meaningful patterns.
- The results suggest that the dataset may contain randomly generated prices with little predictive relationship to the features.

## Project Files

- `House_Price_Prediction.ipynb` – Complete Python analysis and machine learning implementation.
- `House_Price_Prediction_Dataset.csv` – Dataset used for the project.

## Conclusion

This project provided practical experience in data preprocessing, exploratory data analysis, feature engineering and regression modelling.

It also demonstrated the importance of data quality and meaningful relationships between variables when building reliable machine learning models.

---
**Created by Saurabh Shukla | Oasis Infobyte Data Analytics Internship**
