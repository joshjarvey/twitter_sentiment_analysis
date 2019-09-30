# twitter_sentiment_analysis
This project uses the Tweepy wrapper package to pull Twitter data on a given subject using the Twitter API, "cleans" the tweets by removing any URLs using a regular expression function, and finally conducts sentiment analysis using the TextBlob package which is loaded into a dataframe. Neutral sentiment values of 0 are "filtered out", and then a histogram of the data is plotted to display distribution visually so the summary can be easily interpreted. Generally followed the blog linked below. I parameterized the search string, hardcoded the date to today, and removed the hardcoded API credentials into a .json file to learn how to work with .json data. 

Note: Twitter API credentials must be loaded in via a .json file in order to connect to the Twitter API. 

Credit goes to Martha Morrissey, Leah Wasser, Jeremey Diaz, and Jenny Palomino.
https://www.earthdatascience.org/courses/earth-analytics-python/using-apis-natural-language-processing-twitter/analyze-tweet-sentiments-in-python/
