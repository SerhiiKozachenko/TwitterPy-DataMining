How to run:

1. Generate twitter access tokens:
2. Replace following:
```
access_token = "ENTER YOUR ACCESS TOKEN"
access_token_secret = "ENTER YOUR ACCESS TOKEN SECRET"
consumer_key = "ENTER YOUR API KEY"
consumer_secret = "ENTER YOUR API SECRET"
```
3. Run ```python twitter_streaming.py > twitter_data.txt```
4. Wait for 5 mins and check that twitter_data.txt has data
5. Run ```python analyze_tweets.py```
6. Check project folder for charts.

Source code from blog post: An Introduction to Text Mining using Twitter Streaming API and Python

Blog Post Link: http://adilmoujahid.com/posts/2014/07/twitter-analytics/
