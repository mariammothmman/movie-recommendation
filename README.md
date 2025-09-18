# 🎬 Movie Recommendation System

This project implements a **movie recommendation system** using the MovieLens 100K dataset.  
It explores **collaborative filtering methods** (user-based, item-based, and matrix factorization)  
and evaluates performance using **precision@K**.

---

## 📂 Project Structure
- `movie-recommendation.ipynb` → Jupyter Notebook with code and experiments
- `ml-100k/` → Dataset folder (ignored in GitHub; download from [MovieLens](https://grouplens.org/datasets/movielens/100k/))
- `README.md` → Project description

---

## ⚙️ Features
- Build a **user-item matrix** from ratings
- Compute **cosine similarity** between users and items
- Generate movie recommendations:
  - ✅ User-based collaborative filtering
  - ✅ Item-based collaborative filtering
  - ✅ Matrix factorization (SVD)
- Evaluate models using **precision@K**

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/mariammothmman/movie-recommendation.git
   cd movie-recommendation
