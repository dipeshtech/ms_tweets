# MS Historical Tweets dump

#### Example import statement
```
twitterscraper "morganstanley" -bd 2018-01-01 -ed 2020-03-26 -o ms_tweets.json -l 10000
```

```
python -m json.tool ms_tweets.json > pretty_ms_tweets.json 
```

#### Sample Record:
```
{
	"has_media": false,
	"hashtags": [],
	"img_urls": [],
	"is_replied": false,
	"is_reply_to": false,
	"likes": 0,
	"links": [
		"http://www.morganstanley.com/ideas/salesforce-capital-creates-new-ways-to-connect"
	],
	"parent_tweet_id": "",
	"replies": 0,
	"reply_to_users": [],
	"retweets": 0,
	"screen_name": "KyleCBoos",
	"text": "Salesforce used capital to help institutions serve their users & customers better. See how @MorganStanley helped http://www.morganstanley.com/ideas/salesforce-capital-creates-new-ways-to-connect\u00a0\u2026",
	"text_html": "<p class=\"TweetTextSize js-tweet-text tweet-text\" data-aria-label-part=\"0\" lang=\"en\">Salesforce used capital to help institutions serve their users &amp; customers better. See how <a class=\"twitter-atreply pretty-link js-nav\" data-mentioned-user-id=\"426159377\" dir=\"ltr\" href=\"/MorganStanley\"><s>@</s><b><strong>MorganStanley</strong></b></a> helped <a class=\"twitter-timeline-link\" data-expanded-url=\"http://www.morganstanley.com/ideas/salesforce-capital-creates-new-ways-to-connect\" dir=\"ltr\" href=\"https://t.co/40fjX0zf1P\" rel=\"nofollow noopener\" target=\"_blank\" title=\"http://www.morganstanley.com/ideas/salesforce-capital-creates-new-ways-to-connect\"><span class=\"tco-ellipsis\"></span><span class=\"invisible\">http://www.</span><span class=\"js-display-url\">morganstanley.com/ideas/salesfor</span><span class=\"invisible\">ce-capital-creates-new-ways-to-connect</span><span class=\"tco-ellipsis\"><span class=\"invisible\">\u00a0</span>\u2026</span></a></p>",
	"timestamp": "2018-03-21T21:15:12",
	"timestamp_epochs": 1521666912,
	"tweet_id": "976567927259332608",
	"tweet_url": "/KyleCBoos/status/976567927259332608",
	"user_id": "2239781473",
	"username": "FtLauderdaleGrp",
	"video_url": ""
}
```


#### References:
[1] https://github.com/taspinar/twitterscraper
