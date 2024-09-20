# Spotify Song Recommender System

## Overview

This project analyzes the LFM-2b dataset and song audio features data, retrieved using the Spotify API, in Python to build a song recommender system.

## Key Feautures 

- Feature Selection: Applies mutual information-based feature selection to identify the song audio features most associated with song genre
- Recommender System Building: Develops a content-based recommender that takes a Spotify playlist as input, and using cosine similarity, generates five song recommendations with audio features similar to that of the input playlist
- Recommender System Evaluation: Uses Spotify-generated playlists and current Spotify user playlists, retrieved using the Spotify API, to evaluate the recommender’s performance

## Contents

- data/: Folder containing the Kaggle dataset
  - *Note: Some data files have been omitted from this repository due to size constraints; for more details, see **Omitted Files** below.*
- spotify_song_recommender_system.ipynb: Jupyter notebook containing all code for analysis

## Omitted Files

Certain data files are omitted from this repository due to their large size. These omitted files either come from the LFM-2b dataset directly or are generated via Spotify API calls. The data files omitted include:

- tags-micro-genres.json
- spotify_uris.tsv
- data_w_audio_features_new2.csv
- input_data.csv
