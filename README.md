# wsb_reddit_data
ENGR 195E project

There are 4 data files used in this notebook:
- comments_2021-1-1_2021-11-29_new.csv
- reddit_wsb.csv
- reddit.csv
- submissions_reddit.csv

The link to my Google Drive folder for files is here:
https://drive.google.com/drive/folders/1JbPT3QqRBhzYt_vDyXN0p4ybmlMeePPp?usp=sharing

The link to my Colab file is here if you like to make a copy:
https://colab.research.google.com/drive/1fCezE9f3S-tLwFeqAEj98nZ45r60s96j?usp=sharing

At the end of the file, I've created two different dataframes. One is the shortened version of the other.
- "wsb_df" includes: title, body, timestamp, title_word_count, body_word_count, title_lower, body_lower, hashtags, & tickers
- "wsb_simple_df" only includes: title, body, & timestamp

As of 4/9/21: I'm still trying to figure out to clean tickers because it still captures dollar amounts.
