# Wrangle and Analyze Data
> Data Source: Twitter API @WeRateDogs

## Introduction
The project focuses mainly data wrangling - one of the most important processes during the data analytics. 
The final file `twitter_archive_master.csv` collects 1961 original tweet data with dog images posted by the twitter account @WeRateDogs from 11 November 2015 to 1 August 2017. This dataset contains the basic information, including tweet id, the posted time and source (iPhone, Web, or TweetDeck), the URLs of the tweet and also the tweet image, the name and the stage of the dog(s) in the tweet (if applicable), the rating, and the “like” and retweet counts

## Table of contents
### Data Gathering
+ `twitter-archive-enhanced.csv`: an on-hand csv file including some raw information about the tweets, downloaded from udacity.com - Data Analytics Nanodegree Program
+ `image_predictions.tsv`: a tsv file containg the `tweet_id`, `jpg.url`, etc., acquired by `requests.get(url)`*(URL provided by udacity.com)*
+ `tweet_json.text`: Twitter API data, acquired by `tweepy`; <br>
*(Note: some of the data might be deleted from the orignial tweet archive and was hence not retrieved successfully, more info shown in `wrangle_act.ipynb`)*
+ `tweet_count.csv`: a dataset containing the `tweet_id`, `favorite_count`, and `retweet_count`; acquired by the previous `tweet_json.text'
### Data Assessing
+ `wrangle_report.pdf`: a file records the process of data wrangling, including the quality and tidiness issues I detected from the gathered files, and my guideline to clean the dataset
### Data Cleaning
+ `wrangle_act.ipynb`: the Notebook that records the whole process of this project
+ `twitter_archive_master.csv`: the cleaned csv file

