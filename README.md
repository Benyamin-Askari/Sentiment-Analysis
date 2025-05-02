# Sentiment-Analysis
This is one of the assignments for the MLDM module

## Overview

This Python script performs sentiment analysis on product reviews from the "flipkart.csv" dataset.  It involves data loading, exploratory data analysis (EDA), text preprocessing, sentiment labeling, model training, and evaluation. The script uses Support Vector Machines (SVM) and Logistic Regression to classify the sentiment of reviews and compares their performance. It also includes functionality to predict sentiment for new reviews.

## Table of Contents

1.  **Imports**
2.  **Data Loading**
3.  **Exploratory Data Analysis (EDA)**
    * 3.1  Dataset Overview
    * 3.2  Rating Distribution
    * 3.3  Missing Value Analysis
4.  **Text Preprocessing**
    * 4.1  SpaCy Setup
    * 4.2  Stopword Handling
    * 4.3  Text Cleaning
    * 4.4  Word Cloud Visualization
5.  **Sentiment Labeling**
    * 5.1  Rating-Based Sentiment
    * 5.2  VADER Sentiment Analysis
    * 5.3  Sentiment Comparison
    * 5.4  Combined Sentiment
6.  **Data Preparation for Modeling**
    * 6.1  Feature Selection
    * 6.2  Sentiment Encoding
    * 6.3  TF-IDF Vectorization
    * 6.4  Train-Test Split
7.  **Model Training and Evaluation**
    * 7.1  Support Vector Machine (SVM)
    * 7.2  Logistic Regression
    * 7.3  Model Comparison
8.  **Sentiment Prediction for New Reviews**

## Usage

1.  Ensure you have the required libraries installed (pandas, numpy, matplotlib, seaborn, spacy, wordcloud, nltk, scikit-learn).
2.  Download the "flipkart.csv" dataset and place it in the "/content/" directory or modify the file path in the script.
3.  Run the script.  It will perform the analysis and output results and visualizations.
