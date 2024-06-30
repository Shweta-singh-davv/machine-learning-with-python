# machine-learning-with-python
This repository showcases various projects completed by me in the field of machine learning. Below are the details of the projects I have undertaken:

## Book Recommendation System
### Introduction
This project aims to create a book recommendation system for users using a popularity-based measure. The system recommends similar books based on the popularity and taste of the user, leveraging the concept of cosine similarity.

### Features- 
Popularity-Based Recommendations: Recommends books based on popularity metrics. Cosine Similarity: Utilizes cosine similarity to find books similar to the input book title. Exploratory Data Analysis (EDA): Includes EDA to understand the dataset better before building the recommendation system. Libraries Used numpy,pandas,matplotlib,seaborn,scikit-learn

Dataset-- The dataset includes user ratings for various books. It has been filtered to include: Books that have received at least 50 ratings. Users who have rated 200 or more books.

Usage-- To use the recommendation system, simply call the recommend function with the title of the book you want recommendations for. The system will output the top 5 books similar to the input book title based on popularity and cosine similarity.

Conclusion-- This Book Recommendation System efficiently recommends books to users based on their popularity and similarity. It demonstrates the use of various Python libraries and machine learning techniques to build a functional recommendation engine.


## Sentiment Analysis Using Natural Language Processing and Hybrid Naive Bayes Classifier
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

