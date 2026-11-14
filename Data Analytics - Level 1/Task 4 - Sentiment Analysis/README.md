# Sentiment Analysis Using Machine Learning

## Internship Details
- **Organization:** Oasis Infobyte
- **Internship Track:** Data Analytics
- **Level:** Level 1
- **Task:** Task 4 – Sentiment Analysis
- **Intern:** Saurabh Shukla

## Project Overview

This project focuses on building a Machine Learning model to classify text comments into three sentiment categories: Positive, Negative, and Neutral.

The objective is to analyse social media and review comments using Natural Language Processing (NLP) techniques and understand public opinion through text data.

The project uses TF-IDF feature extraction and multiple machine learning algorithms to identify the sentiment of text.

## Dataset Information

- Dataset: Social Media / Review Comments Dataset
- Approximate Records: 241,000 comments
- Target Column: Sentiment
- Sentiment Categories:
  - 0 – Negative
  - 1 – Neutral
  - 2 – Positive

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- TextBlob
- Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the sentiment dataset.
- Inspected dataset structure and data types.
- Analysed sentiment class distribution.
- Checked missing values and duplicate comments.

### 2. Text Preprocessing
- Converted text into lowercase.
- Removed URLs, punctuation, and unnecessary digits.
- Applied tokenization.
- Removed stopwords while preserving negation words.
- Applied lemmatization.

### 3. Exploratory Data Analysis
- Analysed positive, negative, and neutral sentiment distribution.
- Examined comment lengths.
- Created sentiment-specific WordCloud visualizations.
- Identified frequently used words in each sentiment category.

### 4. Feature Extraction – TF-IDF

Used TF-IDF (Term Frequency–Inverse Document Frequency) to convert text comments into numerical features.

The implementation uses:
- Unigrams and Bigrams
- Minimum document frequency of 3
- Maximum 150,000 features
- Sublinear term frequency scaling

### 5. Model Training

Trained and compared three machine learning algorithms:

1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear Support Vector Machine (Linear SVM)

Additionally, TextBlob was used as a rule-based baseline for comparison.

### 6. Model Evaluation

Evaluated the models using:
- Accuracy
- Precision
- Recall
- Macro F1-score
- Weighted F1-score
- Confusion Matrix
- Classification Report

An 80:20 train-test split was used with stratification.

### 7. Error Analysis

- Identified incorrectly classified comments.
- Analysed common classification mistakes.
- Investigated confusion between neutral and other sentiment classes.
- Examined challenges involving sarcasm, negation, and short comments.

## Key Findings

- Positive comments represent the largest sentiment category.
- Negative comments represent the smallest category.
- Logistic Regression and Linear SVM performed better than Naive Bayes.
- Neutral sentiment was more difficult to classify accurately.
- Macro F1-score was considered important because
