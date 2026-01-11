# Breast Cancer Classification using KNN

## 📌 Overview
This project focuses on **breast cancer classification** using the **K-Nearest Neighbors (KNN)** algorithm.  
KNN is a **distance-based supervised learning algorithm** that classifies a data point based on the majority class of its nearest neighbors.

The goal of this project is to predict whether a tumor is **Benign** or **Malignant** using clinical features.

---

## 🧠 Why KNN?
- Simple and intuitive distance-based approach
- No explicit training phase
- Effective when class boundaries are well separated
- Suitable for small to medium-sized datasets

---

## 📊 Dataset
- Dataset: Breast Cancer dataset
- Target Variable:
  - `0` → Benign
  - `1` → Malignant
- Features include measurements like:
  - Radius
  - Texture
  - Perimeter
  - Area
  - Smoothness

---

## ⚙️ Workflow
1. Load and explore the dataset
2. Data preprocessing and normalization
3. Split data into training and testing sets
4. Train KNN model with optimal `K`
5. Evaluate model performance
6. Predict cancer type for unseen data

---

## 🧮 Distance Metric Used
- **Euclidean Distance**

This measures the straight-line distance between feature vectors and determines the nearest neighbors.

---

## 📈 Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics help evaluate how well the model distinguishes between benign and malignant cases.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

