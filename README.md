# Twitter Sentiment Analysis using Machine Learning Model

### Description
* Aimed to study the sentiment in microblogging, which in view to analyse the COVID'19 PANDEMIC.
* A training and predicting pipeline is implemented to contrast performance of various popular classification algorithms and determine the best suited model.
* Sentiment Analysis was determined using **Natural Language Processing (NLP) API -> Natural Language Toolkit (NLTK)**
* Sentiment was retrieved using dictionary-based sentiment -> **Vader Lexicon**

### Data
* Data used for sentiment analysis are retrieved from Twitter
* At time of usage, API can ONLY get **100 tweets per hashtag** at a time.
* The main file "Corona_Tweets.csv" was create by running the code to get tweets again and again and clubbing the data together

### Code Files
* **Notebook for Downloading Twitter Tweets.ipynb** -> to download tweets using Twitter API
* **Twitter Sentiment Analysis using Machine Learning.ipynb** -> applying Machine Learning model on tweets

### Note
* To retrieve data (tweets) from Twitter, you need a **Twitter Developer Account**
* To create Developer Account visit -> "https://developer.twitter.com/en"
* Apply for Developer Account and create a new Project
* Get Keys and Tokens and enter the details in "Twitter_API_Credentials.py"
