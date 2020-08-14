# Twitter Sentiment Analysis

### Project Overview
Great companies strive to provide outstanding customer satisfaction like it's an additional product or service. Understanding the market's opinion about your business or brand name is valuable to business owners but getting that information can be expensive and hard. Luckily for us, 330 million people around the world are already using Twitter to talk about their experiences whether good or bad. Twitter's search API allows us to access atomic tweet data which we can use to analyze and calculate the average consumer's sentiment related to any given keyword(s).

The sentimate_analysis script returns a 'sentiment score' calculated for any given topic provided by the user. 100 tweets posted within the last seven days are analyzed for positive or negative sentiment determined by the NaiveBayesClassifier. The output is a score between 1-5 and two randomly chosen tweets used during the analysis.

### What I would do to improve
1) Analyze each tweet for the user's intent.
    * This can provide actionable insight and help business owners understand how their customers are interacting with their products and services. 
2) Analyze larger amounts of tweets.
    * Twiter restricts the number of returned tweets to 100 per API request when using a standard developer account.
    * Upgrading to premium or enterprise account is required to access more tweets per request.
3) Lemmatize words like 'hi' and 'hiiii'.
4) Detect sarcasm in tweets.

### References
1) Training the NaiveBayesClassifier - https://www.digitalocean.com/community/tutorials/how-to-perform-sentiment-analysis-in-python-3-using-the-natural-language-toolkit-nltk#step-1-%E2%80%94-installing-nltk-and-downloading-the-data
