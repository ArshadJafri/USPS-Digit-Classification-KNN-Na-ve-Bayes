# 🔢 USPS Digit Classification | KNN & Naïve Bayes

This project involves preprocessing, dimensionality reduction, and classification of handwritten digits from the USPS dataset using classical machine learning techniques—**K-Nearest Neighbors (KNN)** and **Naïve Bayes**.

## 🗂️ Dataset Overview

- **Training Set:** 7,291 samples × 256 features  
- **Test Set:** 2,007 samples  
- **Classes:** Digits 0–9  

## 🛠️ Preprocessing

- Applied **Principal Component Analysis (PCA)** to reduce dimensionality to 50 components.
- Standardized features using **StandardScaler**.
- Visualized sample images for inspection.

## 🧠 Models Implemented

### ✅ K-Nearest Neighbors (KNN)
- Cross-validated with k = 1 to 10.
- Best performance with **k = 3**:
  - **Test Accuracy:** 94.87%
  - **Precision:** 94.84%
  - **Recall:** 94.35%

### 🔍 Naïve Bayes
- Used GaussianNB from `sklearn`.
- **Test Accuracy:** 86.70%
- **Precision:** 86.03%
- **Recall:** 85.68%

## 📊 Evaluation

- Computed precision, recall, and confusion matrices.
- Plotted accuracy curves across different `k` values for KNN.
- Compared model performance across key metrics.

## 📌 Key Takeaways

- KNN significantly outperformed Naïve Bayes for this dataset.
- PCA effectively reduced feature size while retaining classification accuracy.
- Naïve Bayes, though computationally efficient, was less accurate due to feature independence assumptions.

---

Feel free to explore, run, or adapt the notebook for further experimentation!
