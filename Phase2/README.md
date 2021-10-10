# EC601_Project2_Phase2

- 2021 Fall Boston University Class EC601 Project 2 Phase 1(a)

- Bingquan Cai

## Social Media Analyzer

The Twitter API can be used to programmatically retrieve and analyze data, as well as engage with the conversation on Twitter. This API provides access to a variety of different resources including the following: Tweets, Users, Direct Messages, Lists, Trends, Media, Places. Also, the Google Natural Language Processing (NLP) has powerful pre-trained models. They empowers developers to easily apply natural language understanding (NLU) to their applications with features including sentiment analysis, entity analysis, entity sentiment analysis, content classification, and syntax analysis.

Therefore, we can obtain the tweets that we are interested in from the Twitter API and then analyze them by using the Google NLP API, especially for the sentiment analysis.

In [Twitter_Google NLP API.py](https://github.com/BingquanCai/EC601_Project2/blob/main/Phase2/Twitter_Google%20NLP%20API_analyzer.py), I gather tweets from the last 24 hours by using the Twitter API and typing in a keyword. Then I use the the Google NLP API to do the sentiment analysis with those related tweets and return some results.

- search_tweets( ) can search tweets based on time and quantity.
- clean_tweets( ) can clean tweets before analyzing in Google NLP API.
- get_sentiment_score( ) can use the sentiment analysis to get a score.
- analyze_tweets( ) can print out the final results.

## MVP and user stories

The MVP includes the Twitter API part and the Google NLP API part. For the Twitter API, I can get the tweets I want and send them to the Google NLP API. For the Google NLP API, I can use sentiment analysis to analyze the tweets from Twitter API and come out with the scores of them.

- For tweeters who are interested in a certain topic, they can get the sentiment score from others on the certain topic over a period of time through the social media analyzer.
- For tweeters who want to show their opinions on Twitter, they can use the social media analyzer to see if their opinions are positive, negative or neutral and then express relatively objective views.

## Modular Design

![](https://raw.githubusercontent.com/BingquanCai/EC601_Project2/main/Phase2/modular%20design.png)
