🎵 MGC-Based Music Recommendation System

An intelligent music recommendation system built using Machine Learning, Clustering, and Spotify’s Audio Features. This project groups similar songs using PCA and K-Means and provides personalized music recommendations with real-time Spotify links and previews.

📌 Project Overview

This project implements a music recommendation system using Spotify song features and machine learning techniques. It analyzes musical attributes such as tempo, energy, danceability, loudness, and mood to group similar songs into clusters. Based on a user’s music preference, the system identifies the most suitable cluster and recommends songs that closely match their taste. The system also integrates with the Spotify API to provide live song details, preview links, and Spotify URLs.

🎯 Motivation

With millions of songs available on music streaming platforms, finding the right music that matches a user’s mood and taste has become challenging. Traditional playlists and genre-based systems are limited in personalization. This project was developed to explore how machine learning and data-driven clustering can be used to create smarter and more personalized music recommendations.

🧠 How It Works

Spotify song features such as BPM, Energy, Danceability, Valence, Loudness, Acousticness, and Speechiness are used.

Data is normalized using Min-Max Scaling.

PCA reduces dimensions for visualization and better clustering.

K-Means groups songs into 5 clusters based on similarity.

A user’s music preference is mapped to the closest cluster.

The most similar songs inside that cluster are selected.

Dynamic feature weighting allows personalized tuning.

Spotify API fetches real song information and preview links.

📊 Features Used

Beats Per Minute (BPM)

Energy

Danceability

Loudness

Valence (Mood)

Acousticness

Speechiness

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-Learn

Plotly

Matplotlib

Spotify Web API (Spotipy)

Jupyter Notebook / Google Colab

📦 Dependencies

Install all required libraries using:

pip install pandas numpy scikit-learn plotly spotipy matplotlib

▶️ How to Run

Clone the repository

git clone https://github.com/SHASHAWNK/MGC-and-recommendation-model.git


Open p2.ipynb in Jupyter Notebook or Google Colab

Upload the dataset Spotify-2000.csv

Add your Spotify API credentials

Run all cells

🎧 Example Input
user_input = [120, 0.8, 0.7, -5, 0.9, 0.2, 0.1]


This represents a preference for energetic, happy, danceable music.

📤 Output

The system returns:

Song name

Artist

Album

Preview audio

Spotify streaming link

This makes the recommendations fully interactive and real-world usable.
