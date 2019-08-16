# RedditScience
Analyzing moderated comments in r/science


Project Overview:
A huge number of hours go into moderating online forums, and with the rise of trolls many sites are even throwing up their hands and removing comment sections all together. Here I will see if it is possible to use NLP to identify which comments were flagged for moderation based on their content. The data set contains popular comments that have both stayed on Reddit and were removed by moderators. 

Data Sources:
Kaggle Reddit Popular Science Comments (Dataset Link)[https://github.com/RWJohns/RedditScience.git]

Methodology:
EDA of dataset and identify key words and phrases that appear often throughout the comments
Use tokenization to process data into wordsoup for analysis
perform feature reduction to aid in analysis 
use unsupervized learning to identiy commonalities between threads, as well as in specificed bins of removed and unremoved comments
see how getting flagged for removal correlates with differences in text


MVP: Compare clusters between comments deleted and not deleted

Target
Flagged for removal

Features:
tagged for removal (boolean)
comment text (string)
score (integer)
identfying IDs




