# 🌸 K-Means Clustering on Iris Dataset – CS 5163 Project 4

This repository contains **Project 4** for the course **CS 5163: Data Science (Spring 2025)** at UTSA, guided by **Dr. Mohammad Imran Chowdhury**. The project focuses on unsupervised learning using the **k-means clustering algorithm** on the classic **Iris flower dataset**.

> 🗓️ Due: April 10, 2025  
> 🎯 Total Points: 65  

---

## 📚 Project Description

You will:
1. Import and prepare the Iris dataset.
2. Apply k-means clustering.
3. Visualize the clustering results alongside actual class labels.

---

## 🚀 Tasks Summary

### ✅ Task 1: Load and Prepare the Dataset (15 points)
- Load `data/iris.csv` into a pandas DataFrame (`df`).
- Extract class labels into `y`.
- Remove the class column from `df`.
- Standardize the feature columns using `StandardScaler`.

### ✅ Task 2: Apply K-Means Clustering (25 points)
- Use `KMeans` with:
  - `n_clusters=3`
  - `random_state=1`
  - `init='k-means++'`
  - `n_init=10`
- Fit the model and print clustering results and centroids.

### ✅ Task 3: Visualize the Clusters (25 points)
- Create a 2D scatter plot using the first two features.
- Color each point by its true class (`y`).
- Use a different **marker style** to indicate the predicted cluster label.

---

## 🛠️ Technologies Used

- Python 3.6+
- pandas
- scikit-learn
- matplotlib / seaborn

Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn

