

## Sentiment Analysis Using Natural Language Processing and  Naive Bayes Classifier
### Introduction
This project aims to perform sentiment analysis on tweets related to the arts of the British Museum. By analyzing the emotions expressed in these tweets, museum authorities can gain insights into the public's perception of their exhibits.

### Features
Sentiment Analysis: Analyze emotions felt by people after viewing art at the British Museum.
Data Cleaning and Preprocessing: Clean and preprocess tweet texts to remove ambiguities.
Naive Bayes Classifier: Use a Naive Bayes classifier to categorize the sentiments.
Visualization: Visualize sentiment distribution and create a word cloud of common words in tweets.
Libraries Used pandas,numpy,matplotlib,seaborn,nltk,tweepy,scikit-learn,wordcloud

### Steps to Perform Sentiment Analysis
Load the Dataset:-
Load the dataset containing tweets in CSV format.
Exploratory Data Analysis (EDA):- Perform EDA on the dataset to understand its structure and content.
Data Cleaning:- Remove special characters and missing values from the tweets.
Preprocessing:- Remove stop words, tokenize, lemmatize, and vectorize the tweets.
Train-Test Split:- Split the data into training and testing sets.
Apply Naive Bayes Classifier:- Train a Naive Bayes classifier on the training data.
Model Evaluation:- Evaluate the model's accuracy on the test data.
Predict Sentiment of New Tweets:- Use the trained model to predict the sentiment of new, unknown tweets.

