# Twitter Stream listener with output to KafkaClient


Original readme from insight:

This directory containes a data generator that connects to the live Twitter stream, collects tweets and saves them to a file as described in the coding challenge directions.

In order to use it, you will need to have a Twitter account, then obtain Twitter OAuth credentials from apps.twitter.com as described here. Then place these credentials in a file named '.twitter', matching the JSON format of the included '.twitter-example'. This '.twitter' file must be placed in the same directory as the 'tweet-cleaner.py' script. If you do post your project to Github, make sure you tell git to ignore this credentials file by using a '.gitignore' file as shown in this repo. Otherwise, your private credentials will be visible to the public forever!

To begin collecting data, simply 'cd' to the directory containing the 'data-gen' directory from the Terminal, and run the command 'python data-gen/get-tweets.py'. This will begin collecting data and storing it in a newly created file named 'tweets.txt'. If you want to, you can then copy this to the tweet_input directory to test your solution.

This data generator should work "out of the box" on most Unix and Linux systems, but you may need to adjust a few parameters or install modules (such as Tweepy) to get it to work on your system. Alternatively, we have included a sample with 10,000 tweets for testing your solution. You do not need to use this generator for the challenge, so do not spend ample time on it - but please email cc@insightdataengineering.com if you have any questions.


# Will add my part -> Kafka and so on
