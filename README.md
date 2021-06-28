# Artist Recommendation Based on Association Rule Mining and Community Detection

In this work we proposed a graph-based approach that utilizes association rules extracted from Spotify playlists. We constructed several artist networks and identified related artist clusters using Louvain and Label Propagation community detection algorithms

Dataset:

We used sample from RecSys challenge in 2018. It contains approximately 663,000 tracks in 9999 playlists with 172,000 unique tracks and 36,000 unique artists.
<a href="https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge"> Spotify Million Playlist Dataset  </a>


## Reproduce Results

Step 1) Execute each step in graph construction folder with ConstructionOfAssociationRules&Graph notebook. These notebook create association rules and construct weighted graph in neo4j. It also retrieve 20 ground truth for each artist.

Step 2) Execute each step in experiments folder with Experiments notebook. These notebook help to examine each clustering results taken from neo4j with external and internal validations.

Step 3) Execute each step in visualization folder with Visualization notebook. These notebook visualize clusters according to cluster labels.


