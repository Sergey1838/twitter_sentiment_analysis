# twitter sentiment analysis

If you want to collect your own data:
1. To be able to use the Twitter APIs, you need to register as a Twitter app developer and obtain keys and access tokens. You need to fill-in the keys and tokens in code/config.cfg with your keys and tokens.
2. Sign in on https://apps.twitter.com/ using your Twitter account.
3. Click on “create new app”.
4. Click on your app name.
5. Click on “Keys and Access Tokens”.
6. In this page, you’ll find a consumer_key, consumer_secret, access_token, and access_token_secret.
7. Copy your keys and tokens into code/config.cfg (watch for extra empty space while copy and paste).
8. Open your working directory in terminal and type "python tweetering.py any_key_word" (replace any_key_word with any word you prefer).
9. The command above will start to collect tweets with your key word. To stop it press control + c. Output will be saved in the same directory as any_key_word.txt

Under data directory, there is some data that I collected using approach described above and lists of positive/negative/stop words. These lists can be easily found in Google.
Under code directory, there are twitter configuration file, code to collect tweets from twitter and code with sentiment analysis.
