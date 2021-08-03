# SentimentAnalysis

Sentiment Analysis and Text Mining Project

Authors:
Rahil Ansari | Parth Shah | Rangeetha | Melissa Pinheiro | Shivani Nanavati

Final Group Project 

Dataset used – Hotel reviews from Kaggle.
Exploratory Data Analysis using ML to understand and extract the useful information from the reviews.
Performing Sentiment analysis on hotel reviews, to find if it’s a positive or a negative review,
using two machine learning techniques - logistic regression model and Vader sentiment analyzer and determining the best model

Analytical Process:

1. Data Loading
2. Data Exploration
3. Data Claning 
4. Data Preprocessing - Stemming, Lemmatization, Stop Words removal, Tokenization 
5. Descriptive Analysis - Building visualizations (Histogram, Word cloud, etc.)
6. Building Logistic Model - Calculating accuracy of the model
7. Using Sentiment Analyzer to calssify sentiment - calculating accuracy 
8. Comparign accuracy and declaring which technique did a better job

Outcome:
Vader sentiment analyzer – 68% Accuracy 
logistic regression model which was 91.47%.

There seems to be two reasons for lower accuracy for Vader sentiment analyzer 
Ambiguity -  vader sentiment analyzer classified a 19 thousand 8 hundred 26 reviews as positive while the logistic model classifed 
18 thousand 4 hundred 25 reviews as positive. It means that certain words that would be considered non positive were considered as
positive because of their ambigous nature. 

Noise in the dataset - As reviews are user input texts, they naturally have noise in them. We tried to preprocess and remove noise 
from data but evidently it weakened the accuracy of our model. 

        
