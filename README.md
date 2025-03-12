# music-recommendation-system
The music industry is huge and number of songs available or released daily is overwhelming. It is very difficult to do a ‘raw’ music search without the help of recommender system. Also, music exploration can be tedious and time consuming.

The objectives: The goal is to develop a music recommendation system that will propose top 10 songs for a user based on the likelihood of listening to those songs
The key questions: Can we develop a recommendation system based on the available data? What are the most popular songs listened by users? Is there underlying trend in the data? Can top performing model identify top ten songs for a user?

The problem formulation: The main objective is to develop a machine learning model that will recommend songs to the user based historical data that’s available. In this case we’ll focus on the user song preferences in the data. Proposing top 10 songs for a user can be automated and enhanced using Machine Learning (ML) models. Specifically in this case, we’ll try to test multiple ML models to get the best results. One of the main advantages of using data science and ML for this problem is speed and scalability especially given that music industry grows exponentially along with the data that’s been generated.

Data Dictionary
The core data is the Taste Profile Subset released by the Echo Nest as part of the Million Song Dataset. There are two files in this dataset. The first file contains the details about the song id, titles, release, artist name, and the year of release. The second file contains the user id, song id, and the play count of users.

song_data
song_id - A unique id given to every song
title - Title of the song
Release - Name of the released album
Artist_name - Name of the artist
year - Year of release
count_data
user _id - A unique id given to the user
song_id - A unique id given to the song
play_count - Number of times the song was played

Data Source
http://millionsongdataset.com/
