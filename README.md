# Crypto_Finance_Articles_Sentiment_Analyzer

Python Bot to Extract -> Summarize -> Analyze Sentiment of Crypto, Finance news articles from Google News.
The end goal is to generate a pie chart to get an idea of the sentiments' spread between Positive, Neutral & Negative.
Keep in mind that the python package Google News parse only the most recent 10 news each time, higher parsing requests will get blocked.

Packages required:

    newspaper3k
    GoogleNews
    nltk
    wordcloud
    pandas 
    matplotlib
    datetime