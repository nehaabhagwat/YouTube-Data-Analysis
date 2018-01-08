# YouTube-Data-Analysis
Kaggle provides a set of statistics for trending videos on YouTube. This project analyses the statistics and uses a Hadoop MapReduce program that provides the most liked, most viewed and most disliked video in each category on YouTube.

The data can be found at the following link:
https://www.kaggle.com/datasnaek/youtube

A large number of records of YouTube videos currently trending are obtained using the above link.
The Mapper program removes all the bad records from this set of records.
The Reducer program finds the most liked, viewed and disliked videos in each category and sends them to the driver with a key.
