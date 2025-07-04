# 🎬 Movie Recommender System

A content-based movie recommendation system built to suggest similar movies based on a user's choice using natural language processing and machine learning techniques.

## 🚀 Overview

This project uses a **content-based filtering approach** to recommend movies by analyzing textual metadata like genres, cast, director, keywords, and more. It is designed as an interactive web application for users to explore and discover movies similar to their favorites.

## 🛠️ Tech Stack

- **Python** – Core programming language
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn** – Feature extraction and similarity calculations
- **NLTK** – Text preprocessing (optional)
- **Streamlit** – For building the interactive web UI
- **Jupyter Notebook** – Model prototyping and exploration
- **TMDb Dataset** – Contains movie metadata (title, genres, cast, etc.)

## 📦 Features

- 🔍 Recommend top similar movies based on selected title
- 🧠 Content-based filtering using:
  - TF-IDF / Count Vectorizer
  - Cosine Similarity
- 🗃️ Uses combined metadata (genres, keywords, overview, cast, crew)
- 📺 Simple and clean Streamlit UI for recommendations
