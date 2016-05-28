# IPLTweetsCollector

Follow the tutorial on http://iag.me/socialmedia/how-to-create-a-twitter-app-in-8-easy-steps/ to create your own twitter app and add the tokens to the get_tweets.py file.


    **How to run get_tweets**

      python get_tweets.py > tweets.txt

````
**How to use Exporter**

Get tweets by username
    python Exporter.py --username 'barackobama' --maxtweets 1
Get tweets by query search
    python Exporter.py --querysearch 'europe refugees' --maxtweets 1
Get tweets by username and bound dates
    python Exporter.py --username 'barackobama' --since 2015-09-10 --until 2015-09-12 --maxtweets 1