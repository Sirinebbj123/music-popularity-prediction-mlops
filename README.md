# 🎵 Music Popularity Prediction – MLOps Project

## 📌 Project Description
This project aims to predict the popularity of a music track using Spotify audio features.  
The objective is to build an end-to-end Machine Learning pipeline, from data exploration to deployment, following MLOps best practices.

The popularity score ranges from **0 to 100** and represents how popular a song is on Spotify.

---

## 🎯 Problem Statement
Can we predict the popularity of a song based on its audio characteristics such as danceability, energy, tempo, and valence?

- **Task**: Supervised Machine Learning  
- **Type**: Regression (popularity score prediction)  

---

## 📊 Dataset

### 🔗 Dataset Source
- **Name**: Spotify Tracks Dataset  
- **Platform**: Hugging Face  
- **Link**:  
  https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset

### 📁 Dataset Description
- Format: CSV  
- Each row represents a Spotify track  
- The dataset contains audio features extracted using Spotify’s audio analysis system.

### 🎯 Target Variable
- `popularity`  
  - Integer value between **0 and 100**

---

## 🧠 Features

### 🎚️ Audio Features
These numerical features describe the musical characteristics of each track:

- `danceability` – How suitable a track is for dancing
- `energy` – Intensity and activity level
- `loudness` – Overall loudness in decibels (dB)
- `speechiness` – Presence of spoken words
- `acousticness` – Acoustic sound probability
- `instrumentalness` – Absence of vocals
- `liveness` – Presence of a live audience
- `valence` – Musical positiveness
- `tempo` – Beats per minute (BPM)

### 🏷️ Metadata Features
- `track_name`
- `artist_name`
- `album_name`
- `duration_ms`
- `explicit`
- `release_date`
- `genre`

### 🛠️ Engineered Features (Planned)
- `release_year`
- `track_age`
- `energy_danceability_ratio`
- `tempo_category`
- `is_long_track`

---

## 🏗️ Project Architecture

