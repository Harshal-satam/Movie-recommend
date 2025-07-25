# Movie-recommend
A Python-based movie recommendation system using IMDb datasets and content-based filtering. Built with pandas, scikit-learn, and BeautifulSoup for data extraction and similarity analysis.

# 🎬 Movie Recommendation System

This project is a simple **Content-Based Movie Recommendation System** developed in Python. It scrapes movie data from IMDb, processes it, and provides recommendations based on genre similarity using cosine similarity.

---

## 📌 Features

- 📊 Uses IMDb as the primary movie data source
- 🔍 Content-based filtering using genres
- 🧠 Cosine similarity for matching user input to similar movies
- 🌐 Scraping with BeautifulSoup
- 🐼 Data handling with pandas

---

## 🛠️ Tech Stack

- Python 🐍
- pandas
- scikit-learn
- BeautifulSoup
- requests

---

## 🚀 How it Works

1. Scrapes movie metadata (title, genre) from IMDb.
2. Cleans and organizes the data using pandas.
3. Converts genres into vectors using `CountVectorizer`.
4. Computes cosine similarity between movies.
5. Takes user input for a movie and recommends similar titles.

---

