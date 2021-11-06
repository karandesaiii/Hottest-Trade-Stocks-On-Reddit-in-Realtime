# Find & analyze popular stocks on reddit in real-time

Helps the trader to pick stocks sooner, that is, when the stock's momentum is picking up. 

This notebook finds the most popular stocks (tickers) on any reddit discussion

Similar to www.wsbdaily.com but wsbdaily.com analyzes last 24 hours, this code analyzes user-specified number of hours. (Example: last 8 hours, last 6 hours and so on). 


It also enables the user to view comments which talk about a particular stock sorted by the 'Best' comments first. (Reddit's BEST category evaluates comments based on upvotes, downvotes and replies - It's an overall quality score of the comment) 

# Requirements
Python 3.7+ should work ideally.

Jupyter Notebook

Reddit API credentials - Follow this blog post to get them: https://www.jcchouinard.com/get-reddit-api-credentials-with-praw/

praw 

pandas 

time

datetime

spacy
