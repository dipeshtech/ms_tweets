# MS Historical Tweets dump

#### Example import statement
```
twitterscraper "morganstanley" -bd 2018-01-01 -ed 2020-03-26 -o ms_tweets.json -l 10000
```

```
python -m json.tool ms_tweets.json > pretty_ms_tweets.json 
```

#### References:
[1] https://github.com/taspinar/twitterscraper
