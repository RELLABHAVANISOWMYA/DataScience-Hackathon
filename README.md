# 🎧 Spotify Podcast: 2023 Hits Dataset 🎶

Welcome to the **Spotify Podcast** project! This dataset offers a deep dive into the **most famous songs of 2023** on Spotify, along with insights into their performance across platforms like Apple Music, Deezer, and Shazam. Perfect for exploring music trends, artist impact, and audio attributes, this dataset brings the pulse of the music industry to your fingertips! 🎤🎵

---

# 🌟 Project Overview

Spotify, one of the largest music streaming platforms with **24M+ subscribers** and a library of nearly **20M songs**, leverages **big data** and **machine learning** to create personalized experiences for its users. 🎶

Here’s how Spotify taps into **big data** to deliver a high-quality user experience:
- **Discover Weekly**: A personalized playlist of fresh songs every week! 🗓️
- **Spotify Wrapped**: Your musical year in review, featuring your most-listened-to songs in December. 📅✨
- **Targeted Ads**: Spotify runs ads based on your music preferences to enhance your experience and boost their business. 📊

---

## 🎼 Dataset Features

The dataset contains detailed information about the top tracks of 2023, providing a wealth of data for analysis:

- **track_name**: Name of the song
- **artist(s)_name**: Name of the contributing artist(s) 🎤
- **artist_count**: Number of artists contributing to the song
- **released_year**: Year the song was released 📅
- **released_month**: Month the song was released 🗓️
- **released_day**: Day of the month the song was released 🌞
- **in_spotify_playlists**: Number of Spotify playlists the song is included in 📚
- **in_spotify_charts**: Presence and rank of the song on Spotify charts 📈
- **streams**: Total number of streams on Spotify 💽
- **in_apple_playlists**: Number of Apple Music playlists the song is featured in 🍏
- **in_apple_charts**: Presence and rank of the song on Apple Music charts 🏆
- **in_deezer_playlists**: Number of Deezer playlists that include the song 🎧
- **in_deezer_charts**: Presence and rank of the song on Deezer charts 📊
- **in_shazam_charts**: Presence and rank of the song on Shazam charts 🎶
- **bpm**: Beats per minute (song tempo) 🎵
- **key**: Key of the song 🎹
- **mode**: Major or minor mode of the song 🎼
- **danceability_%**: Suitability for dancing 💃
- **valence_%**: Positivity of the song’s sound 🎉
- **energy_%**: Perceived energy level ⚡
- **acousticness_%**: Acoustic sound percentage 🎻

---

## 🔍 Key Questions Addressed

Our analysis tackles the following exciting questions:

1. **Highest Streams**: Which song dominated Spotify with the most total streams? 💽
2. **Chart Ruler**: Identify the song that ranked the highest across Spotify, Apple Music, Deezer, and Shazam charts. 🏆
3. **Predicting Energy**: Develop a linear regression model to predict the energy level of a song based on its beats per minute (BPM). ⚡
4. **Valence Prediction**: Create a regression model to predict the valence (positivity) of a song based on its energy and danceability. 🎉
5. **Artist Impact**: Analyze how artist involvement and attributes relate to a song's success. 🎤
6. **Temporal Trends**: Discover shifts in music preferences and attributes over time. ⏳
7. **Cross-Platform Performance**: Investigate how songs perform across different streaming platforms. 📊
8. **Top Artists**: List the top 10 artists who had the most hits in 2023. 🌟
9. **Correlation Insights**: Identify which audio features are highly correlated and which are independent. 🔗
10. **Song Length**: Understand if longer or shorter songs tend to perform better and how their attributes differ. ⏰

---

## 🎯 Bonus Feature: Predicting the Listener's Mood!

In addition to answering the questions above, we've added a unique feature—**mood prediction**! Using machine learning, we predict the mood of a listener based on the song's audio features like tempo, energy, and valence. Whether it's a chill Sunday morning or a Friday night party, we’ve got you covered! 😊🎶

---

## 🚀 How to Get Started

1. **Download the dataset** from the repository.
2. Load the dataset in Python:
   ```python
   import pandas as pd
   data = pd.read_csv('path_to_dataset/spotify_2023.csv', encoding='ISO-8859-1')
   ```
3. **Analyze** and explore the data using tools like `pandas`, `matplotlib`, and `seaborn`. 📊

---

## 🛠️ Technologies

This dataset can be used with:
- **Python** (pandas, NumPy, Matplotlib, Seaborn)
- **R** (dplyr, ggplot2)
- **SQL** for querying and filtering data

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 📬 Contact

Feel free to reach out if you have any questions or want to collaborate on exciting projects! 😊
