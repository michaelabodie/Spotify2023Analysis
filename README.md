An analysis will be performed on the different factors and variables that are associated with the top streamed songs on Spotify in 2023. Kaggle maintains records of the most famous songs of 2023 as listed on Spotify. This dataset shares various attributes/insights regarding the songs listed. Each record is as follows:

Track_name: Name of the song
Artist(s)_name: Name of the artist(s) of the song
Artist_count: Number of artists contributing to the song
Released_year: Year when the song was released
Released_day: Day of the month when the song was released
In_spotify_playlists: Number of Spotify playlists the song is included in
In_spotify_charts: Presence and rank of the song on Spotify charts
Streams: Total number of streams on Spotify
Bpm: Beats per minute, a measure of song tempo
Key: Key of the song
Mode: Mode of the song (major or minor)
Danceability_%: Percentage indicating how suitable the song is for dancing
Valence_%: Positivity of the song’s musical content
Energy_%: Perceived energy level of the song
Acousticness_%: Amount of acoustic sound in the song
Instrumentalness_%: Amount of instrumental content in the song
Liveness_%: Presence of live performance elements
Speechiness_%: Amount of spoken words in the song

Analysis Use Case

What is Being Analyzed?
We will be analyzing the different features and characteristics that are associated with ‘popular’ songs on Spotify in 2023. When comparing these attributes to streams, does any single one impact the amount of streams a song receives? In addition, what is the most popular level/percentage of these attributes within the top 50 streamed songs of 2023?

Presentation Facts
Our targeted audience will be the Spotify stakeholders. Therefore our presentation will revolve around the analysis we perform and how our results were obtained. Our presentation will include a slide conveying the business task, slides displaying our visualizations/analyses, and a slide communicating our results.

Analysis Procedures
Popularity will be defined by the number of streams the songs in the dataset have. We will first create a subset of the data, and only analyze the top 50 most streamed songs within the dataset. Once we have narrowed the data down to 50 songs, we will create visualizations that display the relationship between Streams and the chosen attribute. For instance, one of the visualizations will show a scatterplot displaying the relationship between number of streams vs. BPM. From there, a trendline will be visualized within the plot indicating the general trend and relationship between number of streams and BPM. In addition, the R^2 value will be calculated utilizing Tableau or another analysis tool such as R to measure the degree to which the two values correlate with each other. This procedure will be carried out for the other musical characteristics listed in the dataset; analysis/visualizations will be done on streams vs. mode, streams vs. danceability, streams vs. valence, etc. 

