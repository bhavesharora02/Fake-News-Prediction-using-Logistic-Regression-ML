# Fake-News-Prediction-using-Logistic-Regression-ML
Logistic Regression
Dataset Link : https://www.kaggle.com/c/fake-news/data?select=train.csv

**Project Overview**
This project aims to build a machine learning model to detect fake news using logistic regression. By leveraging natural language processing (NLP) techniques, the model analyzes news articles and predicts whether they are fake or real.

**Dataset**
The dataset used for this project consists of labeled news articles, where each article is marked as either fake or real. The dataset was preprocessed to clean the text, tokenize words, remove stop words, and apply TF-IDF for feature extraction.

**Steps Involved**

1. Data Collection
Collected a dataset containing news articles labeled as fake or real.

2. Data Preprocessing
Performed the following steps to preprocess the text data:

Cleaning Text: Removed noise such as punctuation, numbers, and special characters.
Tokenization: Split the text into individual words or tokens.
Removing Stop Words: Removed common words that do not contribute much to the meaning (e.g., 'is', 'the').
Lemmatization: Reduced words to their base or root form using lemmatization.

3. Feature Extraction
Used Term Frequency-Inverse Document Frequency (TF-IDF) to convert text data into numerical features suitable for machine learning.

4. Model Training
Split the dataset into training and testing sets.
Trained a logistic regression model on the training set using the TF-IDF features.
5. Model Evaluation
Evaluated the model's performance on the test set using the following metrics:

Accuracy: The proportion of correctly classified instances.

Results
The logistic regression model achieved the following results on the test set:

**Accuracy**: 96%
