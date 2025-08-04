# 🎬 Netflix Data Science Analysis

An exploratory data analysis project on Netflix's content. This project analyzes genre distribution, content ratings, release trends, and more using Python and data visualization tools.

---

## 🔗 Quick Links

- 🔙 [Back to All Data Science Projects](../README.md)
- 📄 [View this Project on GitHub](https://github.com/your-username/Data-Science-Projects/tree/main/Netflix-Data-Science-Analysis)
- 📥 [Download the Dataset (mymoviedb.csv)](https://your-link-to-dataset.com/mymoviedb.csv)

---

## 📁 Dataset Overview

- **Rows:** 9,827  
- **Columns:** 9  
- **File:** `mymoviedb.csv`  
- **Includes:** Title, Release Date, Genre, Popularity, Vote Average, etc.

---

## 🧪 Data Exploration Summary

- Clean dataset: no nulls or duplicate entries.
- Dropped less useful fields (overview, language, poster).
- Extracted year from release date.
- Cleaned and exploded multi-genre data.
- Detected outliers in `Popularity`.
- Categorized `vote_average` into four rating bins.

---

## 🛠️ Key Analysis Steps

- Data cleaning & formatting
- Genre parsing using `.explode()`
- Feature engineering with `Categorize_col()`
- Visualization using Seaborn & Matplotlib
- Trend and correlation analysis

---

## 📊 Technologies Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- Jupyter Notebook

---

## 📌 Insights

- **Drama** and **Comedy** are dominant genres.
- Content peaked in certain years (e.g., 2017–2020).
- High popularity ≠ High rating
- Categorizing ratings improves storytelling

---

## 🚀 Future Work

- Add IMDb/TMDb integration
- Deploy with Streamlit for interactivity
- Build a recommendation engine based on genre & rating

---

## ▶️ How to Run

1. Clone the repo or download this folder.
2. Make sure required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
