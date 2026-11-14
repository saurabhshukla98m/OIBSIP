# Titanic Dataset – Data Cleaning & Preprocessing

## Internship Details
- **Organization:** Oasis Infobyte
- **Internship Track:** Data Analytics
- **Level:** Level 1
- **Task:** Task 3 – Data Cleaning
- **Intern:** Saurabh Shukla
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Project Overview

This project focuses on cleaning and preprocessing the Titanic passenger dataset to make it suitable for further analysis.

The dataset contains information about 891 passengers, including their age, gender, ticket class, fare, family details, and survival status.

The objective is to identify and handle missing values, remove inconsistencies, detect outliers, correct data types, and prepare a reliable dataset for analysis.

## Objectives

- Identify and handle missing values.
- Detect and remove duplicate records.
- Standardize inconsistent text and formatting.
- Detect and investigate outliers.
- Correct inappropriate data types.
- Validate the cleaned dataset.
- Compare data quality before and after cleaning.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning Process

### 1. Data Quality Assessment
- Analyzed missing values and data types.
- Checked duplicate records.
- Identified inconsistent text and unusual values.

### 2. Text Standardization
- Removed unnecessary spaces.
- Standardized passenger names and ticket numbers.
- Converted gender labels into consistent formats.
- Replaced embarkation codes with port names.

### 3. Duplicate Handling
- Checked duplicate records.
- No exact duplicate rows were found.

### 4. Missing Value Treatment
- Embarked: Filled missing values using mode.
- Age: Applied median imputation based on passenger Title and Pclass.
- Cabin: Extracted Deck information and created a Has_Cabin indicator instead of guessing missing cabin values.

### 5. Outlier Detection
- Used IQR and Z-score methods.
- Investigated extreme values.
- Retained valid observations instead of unnecessarily removing them.
- Created a log-transformed Fare feature.

### 6. Data Type Correction
- Converted identifiers into strings.
- Converted categorical columns into category types.
- Corrected numeric and Boolean data types.

### 7. Final Validation
- Checked missing values.
- Verified duplicate records.
- Validated passenger IDs and numerical ranges.
- Compared the dataset before and after cleaning.

## Key Results

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Total Rows | 891 | 891 |
| Total Columns | 12 | 16 |
| Missing Values | 866 | 0 |
| Duplicate Rows | 0 | 0 |
| Data Type Accuracy | 67% | 100% |

## Key Insights

- Missing values were reduced from 866 to zero.
- All 891 passenger records were retained.
- No duplicate records were found.
- Data type accuracy improved from 67% to 100%.
- Additional features such as Title, Age_Imputed, Fare_Log, Has_Cabin, and Deck were created.

## Project Files

- `Titanic_Data_Cleaning.ipynb` – Complete data cleaning notebook.
- `titanic.csv` – Original dataset.
- `titanic_cleaned.csv` – Final cleaned dataset.

## Conclusion

This project demonstrates a complete data cleaning workflow using Python.

By applying appropriate missing value treatment, text standardization, outlier investigation, feature extraction, and data type correction, the original Titanic dataset was transformed into a clean and analysis-ready dataset.

The project highlights the importance of data quality and proper preprocessing before performing exploratory data analysis or building machine learning models.

---

**Prepared by:
