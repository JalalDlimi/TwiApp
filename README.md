# Twitter Sentiment Analysis

This is the code for the Twitter Sentiment Analysis using the <b>tweepy</b> library to access the <i>Twitter API</i> and the <b>TextBlob</b> library to perform Sentiment Analysis on each Tweet. Sentiment Analysis is the process to understand and extract feelings from data.

We will be able to see how positive or negative each tweet is about <strong>whatever topic we choose</strong>.

<strong>PS:</strong> <i>Many of you  will wonder why did I use TextBlob instead of just using NLTK!</i> Well, <strong>TextBlob does use NLTK internally.</strong>

Find out more about TextBlob : https://textblob.readthedocs.io/en/dev/


In this project, we first started with tokenizing tweets, so that we can create our bag of words model. Right after our bag of words is created, we will look for the sentiment value for each word from the sentiment lexicon that has it all pre-recorded so that we can classify the total sentiment value of our tweet.
