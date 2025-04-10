# 🧬 Breast Cancer Classification – CS 5163 Project 5

This repository contains Project 5 for **CS 5163: Data Science (Spring 2025)**, under the instruction of **Dr. Mohammad Imran Chowdhury**. In this project, we perform binary classification on a breast cancer dataset using the **k-Nearest Neighbors (kNN)** algorithm with optimization and evaluation techniques.

> 🗓️ Due: April 24, 2025 at 11:59 PM  
> 🎯 Total Points: 100

---

## 📚 Project Description

The project focuses on:
- Loading and exploring breast cancer training and testing datasets.
- Training a **kNN classifier**.
- Performing **hyperparameter tuning** with GridSearchCV.
- **Visualizing performance** through accuracy plots and confusion matrix.
- Evaluating final **model accuracy** on both training and test data.

---

## 🚀 Tasks Summary

### ✅ Task 1: Load the Dataset
- Load:
  - `data/BreastCancer_trn.csv`
  - `data/BreastCancer_tst.csv`
- Inspect structure and sample rows.

### ✅ Task 2: Apply the kNN Model
- Use `KNeighborsClassifier(n_neighbors=5)` from `sklearn`.
- Split into `X_trn`, `y_trn`, `X_tst`, `y_tst`.

### ✅ Task 3: Optimize kNN with GridSearchCV
- Search for the best number of neighbors.
- Evaluate accuracy using cross-validation.

### ✅ Task 4: Plot Parameter Accuracy
- Plot accuracy vs. `k` (number of neighbors).
- Use `cv_results_` from GridSearchCV.

### ✅ Task 5: Plot the Confusion Matrix
- Visualize prediction quality.
- Show TP, TN, FP, FN using `confusion_matrix` and `seaborn.heatmap`.

### ✅ Task 6: Report Accuracy
- Calculate:
  - Accuracy on training data with non-optimized kNN
  - Accuracy on test data with optimized kNN

---

## 🛠️ Tools & Libraries

- Python 3.6+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

Install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

