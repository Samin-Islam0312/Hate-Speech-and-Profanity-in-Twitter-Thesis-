# Hate-Speech-and-Profanity-in-Twitter-Thesis-

This repository contains our collected dataset from Twitter with the help of Tweepy library and our predefined set of keywords specifying negative words. Moreover, our final report that had been submitted to the panel, along with the IEEE format file have been attached. Dataset has been private, but snippets of the dataset can be found inside the manuscripts. 

## Dataset Preparation
To filter the tweets; a predefined array(keywords) has been used
<br>
<br>
_keywords_ = [‘food’, ‘election’, ‘media’, ‘competition’, ‘vlog’, ‘travel’, ‘USA’, ‘US’, ‘economy’, ‘politics’, ‘programming’, ‘social’, ‘climate’, ‘game’, ‘tournament’, ‘movie’, ‘culture’, ‘torture’, ‘trump’, ‘biden’, ‘show’, ‘finance’, ‘stories’, ‘marketing’, ‘media’, ‘twitter’, ‘facebook’, ‘research’, ‘disaster’, ‘weather’, ‘life’, ‘motivation’, ‘fitness’, ‘science’, ‘goals’, ‘technology’, ‘festival’, ‘concert’, ‘song’, ‘review’, ‘hate’, ‘love’, ‘romance’, ‘beautiful’, ‘scenario’, ‘place’, ‘football’, ‘cricket’, ‘com- puter’, ‘religion’, ‘feminism’, ‘job’, ‘study’, ‘worst’, ‘shut’, ‘racism’, ‘kill’, ‘slang’, ‘gun’, ‘murder’, ‘suicide’, ‘racist’, ‘shit’].

<img src="https://github.com/Samin-Islam0312/Hate-Speech-and-Profanity-in-Twitter-Thesis-/assets/69072084/aa32db8e-4fde-428f-bb80-acfdd7ab2119" width="500" height="600">

## Data Preprocessing 
The tweets have been cleaned initially by removing all the non-English Tweets. Then tweets containing only urls, emojis, mentions, numbers, punctuation and other special characters have been removed, along with all the retweets. 
> Finally, the tweets have been tagged separately on the basis of
> 1. If they contain hate speech or not
> 2. if they contain any profanity or not.


After cleaning and removing all the duplicate tweets, 1.5k tweets are remained in the dataset.

<img src="https://github.com/Samin-Islam0312/Hate-Speech-and-Profanity-in-Twitter-Thesis-/assets/69072084/e0cf4f35-2624-43eb-a63f-557dd428315f" width="600" height="900">

## Data Analysis
The entire dataset has been analysed based on 4 categories; hate speech, profanity, combined(hate speech + profanity) and regular texts. 
> * Hate Speech : The tweets that can be considered a hatespeech but did not contain any
> * Profanity : The tweets that contained profane language, but cannot be considered as a hatespeech.
> * Combined (hate speech + profanity) : The tweets which had both hatespeech and profanity are categorized as ”Both”
> * None : The tweets which had no profanities and cannot be considered.
<br>


| Categories | Labels |
| -----------|--------| 
| Both (Hatespeech + Profanity) | Bully, Racism, Belief, Politics, Sexual, Self Hatred and Criticism |  
| Hate Speech | Bully, Racism, Belief, Politics, Sexual, Self Hatred and Criticism |
| Profanity | Bully, Racism, Belief, Politics, Sexual, Self Hatred and Criticism | 
| None | Thoughts, Grateful, Inspiring, Praising and Wishes |


<img src="https://github.com/Samin-Islam0312/Hate-Speech-and-Profanity-in-Twitter-Thesis-/assets/69072084/35f68505-fc49-4af9-a717-f9ce59ea069a" width="1000" height="700">

## Experiment & Results 

