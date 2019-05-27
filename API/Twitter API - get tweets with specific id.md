**link:** (https://stackoverflow.com/questions/28384588/twitter-api-get-tweets-with-specific-id)


#### Get API <br>
import tweepy <br>
auth = tweepy.OAuthHandler(CONSUMER_KEY, CONSUMER_SECRET) <br>
auth.set_access_token(OAUTH_TOKEN, OAUTH_TOKEN_SECRET)   <br>
api = tweepy.API(auth)  <br>

#### Get tweet data  <br>
tweet = api.get_status(id_of_tweet)  <br>
print(tweet.text)  <br>
