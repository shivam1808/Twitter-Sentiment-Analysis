# Twitter-Sentiment-Analysis-Supervised-Learning
![alt text](https://support.appsflyer.com/hc/article_attachments/360001968989/twitter_logo.jpg "logo 1")

A Twitter Sentiment Analysis model developed using python and NLTK (NLP Library). Its a sentiment analysis project. It fetches tweets using Twitter API. Then, parses and evaluate each tweet against list of positive, negative words. It gives sentiments polarity based on the keyword that user gives. It relies upon tweepy-api for tweet collection from twitter server and on textblob for sentiment polarity calculation. Features of tweetwingle include :

- Collects most recent tweets based on the keyword that user gives.
- For each tweet, a polarity (-1 to 1) score and a subjectivity (0 to 1) score is assigned
- Based on the polarity a pie chart is plotted

## Dataset Overview:

The data has been split into two groups:
<ul>
  <li>training set ( <a href="https://github.com/shivam1808/Twitter-Sentiment-Analysis/blob/master/train_tweets.csv">train_tweets.csv</a> )</li>
  <li>test set ( <a href="https://github.com/shivam1808/Twitter-Sentiment-Analysis/blob/master/test_tweets.csv">test_tweets.csv</a> )</li>
</ul>

## Technologies used:
* Python
* Tweepy library to acces Twitter API and parse tweets
* NTLK(Natural Language Toolkit) library to analyze the tweets

## How to use
- Step 1: Sign up here https://developer.twitter.com/
- Step 2: Generate Consumer API keys, Access token & access token secret (check cred.py)
- Step 3: Update credentials.py

## Accuracy:
<img src='https://raw.githubusercontent.com/shivam1808/Twitter-Sentiment-Analysis/master/accuracy.PNG' border='0' alt='Prediction'/>

## Output:
<img src='https://raw.githubusercontent.com/shivam1808/Twitter-Sentiment-Analysis/master/tweets.PNG' border='0' alt='Prediction'/>

## Reference:
YouTube <a href="https://www.youtube.com/watch?v=ujId4ipkBio">Link</a>



