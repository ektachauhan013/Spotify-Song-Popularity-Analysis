# Spotify Songs — Exploratory Data Analysis

## Overview
This project dives into a dataset of **114,000 Spotify tracks** to explore what makes a song popular on Spotify — uncovering patterns across audio features, genres, artists, and more.

## Tools & Libraries
- **Python**
- **Pandas** — data manipulation
- **Matplotlib** — data visualization

## Dataset
- **Source:** Kaggle
- **Size:** ~114,000 tracks
- **Key Features:** popularity, duration, danceability,
  energy, loudness, speechiness, acousticness,
  instrumentalness, liveness, valence, tempo,
  key, mode, explicit, artists, track_genre
- Description
  A comprehensive collection of Spotify tracks spanning multiple genres, capturing both audio features and metadata to help analyze what drives a song's popularity on the platform.

## Data Cleaning
- Removed missing values
- Removed duplicate tracks

## Key Insights

- Popularity on Spotify is rare — most tracks receive little to no engagement, with only a few breaking into high scores.

- Musical key has negligible influence on popularity, with differences across keys being too minor to matter.

- A small group of artists consistently dominates high popularity, proving that recognition and fan loyalty outweigh any audio feature.

- Certain genres consistently attract stronger engagement, reflecting that cultural context matters as much as the music itself.

- Explicit content shows only a marginal difference in popularity, making it an unlikely driver of success.

- Minor mode songs hold a slight edge over major, possibly reflecting a subtle listener preference for emotional depth.

- Loudness and danceability show the highest positive correlation with popularity, while instrumentalness pulls it down — yet all  correlations remain too weak to be reliable predictors.

- Popular songs cluster between 2.9–4.4 minutes, with very long tracks being rare and consistently less popular.

- Energy shows no strong link to popularity, though moderately high-energy songs appear slightly more often at higher popularity levels.

- Danceability is the most consistent audio feature positively associated with popularity — but even it alone cannot guarantee success.

---

## Final Conclusion
There is no single formula for a hit song on Spotify.Popularity emerges from a combination of factors — songs that are short, danceable, loud, and vocal-driven tend to have a slight edge, while artist recognition and genre preferences play an arguably larger role than any audio feature. The data ultimately tells us that while certain musical patterns increase the *likelihood* of popularity, listener engagement is shaped just as much by external forces like trends, timing, and artist exposure as it is by the music itself.