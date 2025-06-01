# 🧠 Logistic Regression for Breast Cancer Classification

## 🎯 Project Overview

This project demonstrates the implementation of a **binary classification model using Logistic Regression** to classify tumors as **malignant** or **benign** based on features from the **Breast Cancer Wisconsin dataset**.

---

## 📁 Dataset

- **Name:** Breast Cancer Wisconsin Diagnostic Dataset  
- **Source:** [Scikit-learn Datasets](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)  
- **Target Classes:**
  - `0` = Malignant
  - `1` = Benign

---

## 🧰 Tools & Libraries

- **Python 3.x**
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---

## 🚀 Project Workflow

### 1. Load and Explore Data
- Use Scikit-learn’s `load_breast_cancer()` to access the dataset.
- Convert to a Pandas DataFrame for easy handling.

### 2. Preprocessing
- Split into **training and test sets**.
- Standardize the features using `StandardScaler`.

### 3. Model Training
- Fit a **Logistic Regression** model using the standardized training set.

### 4. Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve and AUC Score

### 5. Threshold Tuning
- Predict using **custom decision thresholds** (e.g., 0.3).
- Analyze the effect on confusion matrix and performance.

### 6. Sigmoid Function
- Discussed its role in converting linear outputs into class probabilities:
  \[
  \sigma(z) = \frac{1}{1 + e^{-z}}
  \]

---

## 📊 Results

- Achieved high accuracy with well-balanced precision and recall.
- ROC AUC score showed strong separability between classes.
- Threshold tuning allowed optimization based on specific use cases (e.g., prioritizing recall over precision in medical diagnosis).

---

## 📈 Visualizations

- ✅ Confusion Matrix (default & custom threshold)
- ✅ ROC Curve with AUC
- ✅ Feature Standardization Histogram (optional)

---



