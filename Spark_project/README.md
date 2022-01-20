# Popular tweets

The objective is to build a Spark Streaming application that shows popular hashtags on Twitter. 

In the first notebook (First_part.ipynb), we wrote a python application that can stream live tweets from TwitterAPI.

Then in the second notebook (Second_part.ipynb), I wrote a Spark Streaming application that connects to the first part, extracts
hashtags, and displays the 10 most popular among them in the last 10 minutes. 
