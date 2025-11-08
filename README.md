# 🎌 Anime Recommendation Engine

A content-based anime recommender built with classical machine learning and feature engineering. No deep learning required—just clever use of genre encoding, popularity metrics, and cosine similarity. Designed for anime fans, data scientists, and ML learners who want to build something fun, visual, and portfolio-worthy.

---

## 🚀 Project Overview

This project recommends anime titles based on a user's favorite show using a content-based filtering approach. It leverages the [Anime Recommendation Database 2020](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020) and applies feature engineering to build a similarity-based recommendation system.

---

## 🧠 What You'll Learn

- Intermediate ML techniques: pipelines, scaling, similarity metrics  
- Feature engineering: genre encoding, interaction features, popularity bins  
- Visual storytelling: genre distributions, similarity scores, popularity analysis  
- Streamlit dashboarding: interactive UI for real-time recommendations

---

## 📊 Features

- 🔍 Select your favorite anime and get 5 similar recommendations  
- 🎭 Visualize top genres and popularity bins  
- 📈 See similarity scores in a bar chart  
- 🧪 Optional classifier to predict user preferences (Random Forest)

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, scikit-learn)  
- **Streamlit** for dashboard UI  
- **Matplotlib + Seaborn** for visualizations  
- **Kaggle Dataset**: [Anime Recommendation Database 2020](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020)

---

## 📁 File Structure
anime_recommender/ 
├── app.py         # Streamlit dashboard 
├── anime.csv      # Kaggle dataset 
├── recommender.py # Core logic (optional modularization) 
├── assets/        # Optional: anime posters, icons


---

## 🧪 How to Run Locally

1. Clone the repo  
2. Download the dataset from Kaggle and place `anime.csv` in the root folder  
3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   streamlit run app.py
Author
Travour — ML enthusiast, anime fan, and creative systems thinker. Building signature projects that blend technical depth with visual flair.
