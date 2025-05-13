# 🧬 Cancer Prediction Model

This repository contains a machine learning project that predicts whether a tumor is **malignant** or **benign** using clinical data. The project leverages classification techniques to help in early cancer diagnosis, specifically using the **Breast Cancer Wisconsin dataset**.

---

## 📌 Project Objective

The objective of this project is to:

- Train a classification model to accurately predict cancer type (malignant or benign)
- Understand key features that help distinguish between cancer types
- Provide an end-to-end ML pipeline from data cleaning to prediction

---

## 📁 Dataset Used

- Dataset: **Breast Cancer Wisconsin (Diagnostic) Data Set**
- Source: `sklearn.datasets.load_breast_cancer()`
- Features include:
  - Radius, Texture, Perimeter, Area, Smoothness, etc.
- Target:
  - 0 = Malignant
  - 1 = Benign

---

## 🔧 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas, NumPy
- Matplotlib & Seaborn (visualizations)
- Scikit-learn (ML model)

---

## 🔍 Workflow Summary

1. **Data Import & Exploration**
   - Load the dataset using `sklearn.datasets`
   - Understand the shape and feature names
   - Visualize correlations and feature importance

2. **Data Preprocessing**
   - Convert data to Pandas DataFrame
   - Clean and normalize data
   - Encode labels

3. **Model Building**
   - Train-test split (80/20)
   - Use Logistic Regression / SVM / Random Forest Classifier (check notebook)
   - Evaluate accuracy using confusion matrix & classification report

4. **Evaluation**
   - Model accuracy
   - Precision, recall, F1-score
   - ROC curve and AUC (if implemented)

---

## 📊 Results

- Achieved **high accuracy (>95%)** on test data.
- Successfully classified most tumors correctly.
- Visualized results using confusion matrix and performance metrics.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/cancer-prediction-model.git

