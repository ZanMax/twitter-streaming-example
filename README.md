# Twitter Streaming Example
Examples of Twitter streaming

## Tweepy

### Authentication

```python
import tweepy

client = tweepy.Client(
    consumer_key="API / Consumer Key here",
    consumer_secret="API / Consumer Secret here",
    access_token="Access Token here",
    access_token_secret="Access Token Secret here"
)
```

### Filter

```python
stream.filter(track=["python"])
```