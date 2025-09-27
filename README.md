# 🎬 Movie Recommendation System

A **content-based movie recommendation system** built with **Python, Pandas, scikit-learn, and TF-IDF**.  
It recommends movies similar to the one you like by analyzing **genres, keywords, tagline, cast, and director**.  

---

## 🚀 Features
- Recommend top 30 similar movies based on user input  
- Uses **TF-IDF Vectorization** for feature extraction  
- Measures similarity using **cosine similarity**  
- Handles approximate user input with `difflib` for close matches  

---

## 📂 Dataset
The system requires a movies dataset with the following columns:
- `index` – unique movie index  
- `title` – movie title  
- `genres`, `keywords`, `tagline`, `cast`, `director`  


## 🛠️ Tech Stack
- **Python** 3.x  
- **Numpy**  
- **Pandas**  
- **scikit-learn** (TF-IDF, cosine similarity)  


