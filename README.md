# YBI_Project
# 🎬 Movie Recommendation System using TF-IDF & Cosine Similarity

This is a content-based movie recommendation system built using machine learning and natural language processing techniques. The system suggests similar movies based on the user’s favorite movie input by analyzing text features like genre, keywords, tagline, cast, and director.



## 📌 Project Overview

This system helps users discover movies similar to their preferences using a content-based approach. It relies on textual information of the movies, converts it into numeric form using **TF-IDF vectorization**, and measures similarity using **cosine similarity**.



## 🚀 Features

- Input your favorite movie and get a list of recommended movies.
- Uses combined features like genre, keywords, tagline, cast, and director.
- Employs **TF-IDF Vectorizer** for text feature extraction.
- Uses **Cosine Similarity** for finding similar movies.
- Based on a real-world dataset from YBI Foundation.



## 🧰 Technologies Used

- Python
- Pandas
- Scikit-learn
- Difflib
- TF-IDF Vectorizer
- Cosine Similarity



## 📂 Dataset

The dataset used for this project was sourced from [YBI Foundation](https://github.com/YBI-Foundation/Dataset) and includes metadata of various movies.



## 🧠 How It Works

1. Load and clean the dataset.
2. Merge selected text-based features into a single string.
3. Vectorize text using **TF-IDF**.
4. Compute similarity scores using **Cosine Similarity**.
5. Match user input with closest movie title using `difflib`.
6. Recommend top 10–30 similar movies based on similarity score.



## 📥 Installation

```bash
git clone https://github.com/kunal-10-02/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt
