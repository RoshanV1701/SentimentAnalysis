# SentimentAnalysis

## Description

A NLP project to classify tweets on any subject as positive, neutral or negative. Also includes a tweet scraper built from scratch to pull data from Twitter.

## Getting Started	

### Setting up the project

* Open the Jupyter notebook on Google Colab. If it is not opening from the github file, use this url : [Google Colab](https://colab.research.google.com/github/RoshanV1701/SentimentAnalysis/blob/main/SentimentAnalysis_Twitter.ipynb)
* To change the subject being scraped change the value of the variable search_params :
```
search_params = {
    'q': 'Google',
#     'result_type': 'recent',
    'count': 50000,
    'tweet_mode' : 'extended'
}
```
* Run the code on colab.