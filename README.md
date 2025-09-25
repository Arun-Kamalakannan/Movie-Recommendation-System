# 🎬 Movie Recommender System

This project builds a **Movie Recommender System** using the **TMDB 5000 Movie Dataset**.  
The notebook demonstrates how to preprocess movie and credits data, extract meaningful features, and implement a recommendation algorithm.

---

## 📌 Project Overview
The goal is to recommend movies based on similarity in content such as **genres, keywords, cast, and crew**.  
This is achieved by combining data from two datasets:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`
- Dataset link- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## ⚙️ Steps in the Notebook

1. **Data Exploration**
   - Load movies and credits datasets.
   - Explore dataset structure and contents.

2. **Data Preprocessing**
   - Merge datasets on the `title` column.
   - Select only relevant columns for building the recommender.
   - Clean and normalize text data (genres, keywords, cast, crew, overview).

3. **Feature Engineering**
   - Convert textual data into structured lists.
   - Combine features into a single column (`tags`).
   - Vectorize `tags` using `CountVectorizer`.

4. **Similarity Calculation**
   - Compute **cosine similarity** between movies.
   - Build a similarity matrix.

5. **Recommendation Function**
   - Given a movie title, retrieve top similar movies.
   - Fetch and display posters from **TMDB API**.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Requests  
- Pickle  

---

## ▶️ How to Run

1. Clone this repository or download the notebook.

2. Install the required libraries:

3. Download the **TMDB 5000 dataset** and place the files in the project directory:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

4. Run the Jupyter Notebook step by step to build the recommender system.

5. Test the recommender by passing a movie title: Avatar

