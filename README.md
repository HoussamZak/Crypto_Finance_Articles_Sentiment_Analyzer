# Crypto_Finance_Articles_Sentiment_Analyzer Version 2.0 
Sentiment Analysis

Python Bot to Extract -> Summarize -> Analyze Sentiment of Crypto, Finance news articles from Google News.
The end goal is to generate a pie chart to get an idea of the sentiments' spread between Positive, Neutral & Negative.

I improved the code to parse more articles for the given keyword of interest and run deeper analysis.
Articles extracted for the last 24 hours.

The bot generates a graph showing the sentiment evolution in the past day regarding the keyword of interest.
It also produces a polarity graph.

https://colab.research.google.com/drive/1-g6hK7gwOkMEAdoUbCuefYiu4tatiZWC?usp=sharing

Packages required:

    newspaper3k
    GoogleNews
    nltk
    wordcloud
    pandas 
    matplotlib
    datetime