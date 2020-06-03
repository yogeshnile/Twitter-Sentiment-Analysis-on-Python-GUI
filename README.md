# Twitter-Sentiment-Analysis-on-Python-GUI
On this Repo created a Twitter Sentiment Analysis on python GUI (Tkinter) library.

## Dependentias
```python
from tkinter import *
import numpy as np
import tweepy 
import pandas as pd
from textblob import TextBlob
from wordcloud import WordCloud
import re 
import matplotlib.pyplot as plt

```

# Disclaimer
I am not provideing twitter **API** keys. You have get twitter API keys on twitter developer account. Get [API Keys](https://developer.twitter.com/)

Get a API key and put in the below code section

```python
def click():  
    user_name = user_value.get()
    hash_name = hash_value.get()
    
    consumerKey = ""
    consumerSecret = ""
    accessToken = ""
    accessTokenSecret = ""
    
    authenticate = tweepy.OAuthHandler(consumerKey, consumerSecret)
    authenticate.set_access_token(accessToken, accessTokenSecret)
    api = tweepy.API(authenticate, wait_on_rate_limit = True) # api object
```
    
    

## ScreenShot:-

<img src="https://github.com/yogeshnile/Twitter-Sentiment-Analysis-on-Python-GUI/blob/master/Images/3.png"/> 

<img src="https://github.com/yogeshnile/Twitter-Sentiment-Analysis-on-Python-GUI/blob/master/Images/1.png"/> 

<img src="https://github.com/yogeshnile/Twitter-Sentiment-Analysis-on-Python-GUI/blob/master/Images/2.png"/> 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Follow on a Social Media
- [LinkedIn](https://bit.ly/2Ky3ho6)
- [Instagram](https://bit.ly/3b9Qeo4)
- [Instagram](https://bit.ly/32SXHV0) Personal
- [Twitter](https://bit.ly/3dbLJLC)
