# AI_Trading Bot

### Telegram Bot


- able to scrap all message from specific channel
- please input your own account credential to test it

    * Add the following to your GitHub Codespace or Local file
    * API_ID, API_HASH, PHONE, USERNAME
    * api_id = os.getenv('API_ID')
    * api_hash = os.getenv('API_HASH')
    * phone = os.getenv('PHONE')
    * username = os.getenv('USERNAME')

- example message scrapped file is on slack group chat

### Sentiment Analyzer
Please see below for an example use case / pipeline for the sentiment analysis:

```
import pandas as pd
from flatten_tweets import flatten_tweets
from sentiment_analyzer import sentiment_generator
from sentiment_analyzer import find_sentiment
```
