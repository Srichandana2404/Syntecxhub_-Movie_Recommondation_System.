# Syntecxhub_-Movie_Recommondation_System.
# 🎬 Movie Recommendation System

Dataset: https://drive.google.com/file/d/1LTqUF8b1ZUuF8a5ELyLYL7fktrAN4GpI/view?usp=sharing

This project implements a Content-Based Movie Recommendation System using TF-IDF Vectorization and Cosine Similarity. The system recommends movies similar to a given movie based on its genre and overview.

## 📌 Project Overview

The recommendation system analyzes movie metadata and suggests similar movies based on textual similarity. It combines the genre and overview of movies to create a feature set and uses machine learning techniques to compute similarity between movies.

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset

The dataset contains information about movies including:

- id – Movie ID  
- title – Movie name  
- genre – Movie genre  
- overview – Movie description  
- release_date – Release date  
- vote_average – Movie rating  

## 🧹 Data Preprocessing

Steps performed during preprocessing:

- Loaded dataset using Pandas
- Handled missing values in genre and overview
- Extracted year from release_date
- Created a tags column by combining genre and overview

Example:

```python
tags = genre + overview
