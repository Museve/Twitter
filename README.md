# Twitter
Twitter analysis report
#Aim/Objectives
The aim of the analysis is to build a sytem that will map a particular tweet to a given trending topic in Nairobi kenya at the time of analysis. The response variable is categorical with three levels.
# Data collection and cleaning
the analysis collects the data from twitter API via the tweepy library and add the tweets from trending topics to a SQLite database. Thereafter, the collected is cleaned by removing punctuations and other string character associated with the tweets. Tweets were also tokenize (finding the roots words for easier understanding). Features like location were not taken into consideration.
# Data Analysis/visualization
data collected is analyzed via two vizualisations: Word Cloud and Line graphs. Visualization help in giving faster insight at a glance by showing variation and trend used by a particular visualization tool.
three topics are selected from the hashtags : politics, social and media

# Machine Learning Model
the model selected is a gradient boosting model that achieves an accuracy score of 80%. This indicates that for any predition made by this model is that the chance of right prediction is always 80%.
