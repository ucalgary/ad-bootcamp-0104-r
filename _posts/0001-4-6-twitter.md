---
layout: default
published: true
classes:
 - slide
data:
  x: 3000
  y: 4000

title: "Twitter"
---
* [Get an OAuth token](https://dev.twitter.com/docs/auth/tokens-devtwittercom)
* to authenticate
		library(twitteR)
		cred = OAuthFactory$new(consumerKey="", consumerSecret="", requestURL="https://api.twitter.com/oauth/request_token", accessURL="https://api.twitter.com/oauth/access_token", authURL="https://api.twitter.com/oauth/authorize")
		cred$handshake()
		registerTwitterOAuth(cred)
* get tweets
		userTimeline("kinghuang", n=20)
* see [Text Mining](http://www.rdatamining.com/examples/text-mining)