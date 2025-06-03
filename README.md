
# 🎬 Movie Recommendation System

This is a Movie Recommendation Web App built using **Streamlit** and **Machine Learning** techniques. The app suggests movies similar to the one selected by the user, based on content-based filtering using scikit-learn.

## 🚀 Features

- Recommend similar movies using **cosine similarity**
- Search and select a movie from a dropdown
- Display **movie posters** using TMDB API (optional)
- Fast and interactive web UI built with **Streamlit**
- Lightweight and easy to run locally

## 🧰 Tech Stack

- 🐍 Python 3.x
- 📦 Streamlit
- 📘 scikit-learn
- 🐼 pandas
- 🌐 requests (for API calls)
- 🔢 numpy
- 📊 matplotlib / seaborn (optional for visualizations)

## 📂 Project Structure


## 🧪 How It Works

1. **Data Preprocessing**: Movie data is cleaned and vectorized using TF-IDF or CountVectorizer.
2. **Model**: Cosine similarity is used to find similar movies based on genres, cast, keywords, etc.
3. **User Interface**: Users select a movie, and the app displays 5 similar recommendations with optional posters and info.
