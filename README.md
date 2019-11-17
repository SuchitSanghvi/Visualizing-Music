# Visualizing-Music

![alt text](https://media.tenor.com/images/cc0d2d9170144cfb79a6c8e2aa270aa0/tenor.gif "Logo Title Text 1")

## Project Description
Have you ever found yourself in a classroom or an office trying to concentrate on your work but can’t get rid of a song stuck in your head? Or maybe getting chills when you listen to a specific song? If not these, you would have definitely found yourself delving into memories of someone or something while listening to a particular song, What causes these phenomena? How does it work? Why does certain songs become popular?

With the increasing use of streaming services for listening to music, it has become possible to
collect large scale data and analyze it. This data includes data about tracks with parameters like
acousticness, energy, danceability. It can include data related to specific artist, album or
listener. One of the most wide use of the music data is using a prediction based analytical
techniques to build a recommendation system. These techniques use music features like genre,
acousticness, energy, etc. to predict the success of a song.

Spotify is the largest music streaming platform.With more than 35 million songs and 170 million
monthly active users. In this project, we will extract several types of data from Spotify and
analyze the data to find insights that will give us a better understanding of the phenomena
mentioned above and more. Some of the questions we plan to answer are as mentioned below.
Furthermore, we also plan to build our own recommendation system that will find songs similar
to those in a particular playlist.

### Questions of Interest
Our research questions are as below:
1) What are the audio features of popular songs?
2) Does popular songs share any similar characteristics?
3) How diverse are the popular songs of different eras?
4) What are the top performing songs from different ages in present-day?
5) Is there a specific genre for hit songs of different ages?
6) What is the trend of the hit songs from differet ages(70's - 00's) in past 3 years?

### Expected Findings:

1) Popular songs were more diverse earlied than that in current times.
2) Popular songs have a common high value for certain specific parameter(example: energy, danceability).
3) Country songs of 80s and jazz songs of 90s are most listened in present day.

## Dataset used
Most of the dataset used in the project would be extracted from Spotify using Spotify Web API,
python libraries and scraping data from spotify website(if required).
Some of the endpoints of interest that Spotify provides are: Albums, Artists, Playlists, Tracks,
User Profiles, and Library.

We will extract various segments of data as per need and as per the hypothesis we are trying to
test or questions we are trying to find insights for.
Some of the data that we will extract from these endpoints is as described below:
● Album: Attributes - album type, artists, available_markets, disc_number, label, name,
tracks, popularity, release date etc.
● Track: Attributes - acousticness, danceness, danceability, energy, instrumentalness,
liveness, loudness, etc.
● Artist: Attributes - follower, genres, name, popularity, type, etc.
● Playlists: Attributes - collaborative, followers, description, name, public, tracks, etc.
