# twitter_sentiment_analysis
This repository contains a sentiment analysis project on Twitter data, comparing a baseline logistic regression model (67% accuracy) and random forest classifier model(69% accuracy) with a fine-tuned DistilBERT model (86% accuracy). The project uses the Twitter Airline Sentiment dataset from Kaggle, classifying tweets about airlines into positive, neutral, and negative sentiments.

# Project Overview
The goal was to build and compare machine learning models for sentiment analysis on real-world Twitter data. Starting with a simple logistic regression model as a baseline with a random forest classifier, I then leveraged DistilBERT—a lightweight transformer model—to achieve significantly higher accuracy. This showcases the power of modern NLP techniques over traditional methods.

Dataset: 14,640 labeled tweets from the Twitter Airline Sentiment dataset.
Task: Binary-class classification (positive, negative).
Models:
Logistic Regression (baseline): 67% accuracy.
Random Forest Classifier:69% accuracy.
DistilBERT (fine-tuned): 86% accuracy.

# Future Improvements
Experiment with other transformers (e.g., BERT, RoBERTa).
Add hyperparameter tuning for DistilBERT.
Deploy as a web app with Streamlit.
