# ML_song_clustering
This is the 7th project of the wbs coding school bootcamp in data science.

## The project
The topic is unsupervised ML. The use case is clustering a dataset of 5000 songs by their audio features from Spotify. The aim was to create playlists with 50-200 songs per playlist. The data was cleaned, checked for feature correlation, scaled, explored and analyzed. Clustering was explored using hierarchical clustering. Different scaling methods, numbers of k and clustering methods were compared. The playlists were created with KMeans, k was chosen via the elbow method and the silhouette score.
In the end, the project was presented in a [presentation](https://www.canva.com/design/DAFr-LwU_fo/a5MrLObZxHtS8LydSiKioQ/edit?utm_content=DAFr-LwU_fo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

### included audio features
- danceability
- duration_ms
- energy
- instrumentalness
- key
- liveness
- loudness
- mode
- speechiness
- tempo
- time_signature
- valence
