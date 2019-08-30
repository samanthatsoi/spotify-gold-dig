# Do I Have A "Good Music Taste"?
#### Began in: December 2018 
_Author: Sam Tsoi_ <br>
samanthatsoi@gmail.com <br>

**Summary** <br>
I explored my own music and the audio features associated to the tracks I listen to and made some analysis on my music taste, how Spotify reacts to what I listen to, and how my music compare with that of the rest of the world. Context, Visualizations, Data Exploration, Statistical methods, Analysis, and Conclusion are some of the topics that the project will cover. <br> <br>

**Instructions, and some things to note** <br>
Spotify Gold Digging.ipynb exports topsongs.csv and playlists.csv from the API, so those aren't needed to run the notebook. Features.csv is a .csv from https://www.kaggle.com/nadintamer/top-tracks-of-2017/data that I compare my dataset to. I use the Spotify API that requires a id, a secret code, and a token. The ID and secret code is unique to each account, and the token must be fetched every once an hour or so or it will expire.  <br> <br>


**Citation** <br> This is also included this in the Jupyter Notebook.
<br>
-I got features.csv from https://www.kaggle.com/nadintamer/top-tracks-of-2017/data
<br>
-Spotipy package and documentation from https://github.com/plamere/spotipy
<br>
-Spotify developer, also where I need to get my token from https://beta.developer.spotify.com/dashboard/applications/b0ccdb01b69844b3af068c4fec4c8dc5
<br>
-Direct link to get token from https://beta.developer.spotify.com/console/get-current-user-top-artists-and-tracks/?type=artists&time_range=medium_term&limit=10&offset=5