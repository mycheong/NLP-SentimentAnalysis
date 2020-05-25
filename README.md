# NLP - Sentiment analysis

This repository contains example of sentiment analysis, more specifically, classifcation of text into positive vs. negative sentiment. 

The first project is an analysis of movie reviews in Finnish language. The data used is obtained from www.leffatykki.com. Here, we train Naive Bayes classifiers and Logistic regression classifiers for comparison. We tested using mutual information (MI) based classifier to identify a list of words which has low MI values (poor discriminating power for the classes) and use them as stopwords. The jupyter notebook can be found here.

https://github.com/mycheong/NLP-SentimentAnalysis/blob/master/Sentiment_MovieReviewsFinnish.ipynb

The second one is classification of Amazon's Groceries & Gourmet Food reviews. The data is obtained from http://jmcauley.ucsd.edu/data/amazon/. 
The jupyter notebook can be found here.

https://github.com/mycheong/NLP-SentimentAnalysis/blob/master/sentimentClassif_AmazonGroceriesReview.ipynb
