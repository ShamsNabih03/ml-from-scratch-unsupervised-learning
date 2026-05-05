# 🧠 Unsupervised Learning from Scratch

This project implements core machine learning algorithms **from scratch using NumPy**, without relying on libraries like scikit-learn for model logic.

It focuses on **dimensionality reduction** and **clustering techniques**, along with full experimental evaluation and comparisons.

---

## 🚀 Features

### 📉 Dimensionality Reduction

* Principal Component Analysis (PCA)

  * Eigenvalue decomposition
  * Explained variance ratio
  * Reconstruction error
* Autoencoder (Neural Network)

  * Fully connected architecture
  * Backpropagation from scratch
  * Mini-batch gradient descent
  * Learning rate decay & L2 regularization

---

### 📊 Clustering Algorithms

* K-Means

  * K-Means++ initialization
  * Random initialization
  * Convergence tracking
  * Inertia history

* Gaussian Mixture Models (GMM)

  * Full EM Algorithm
  * Supports covariance types:

    * Full
    * Tied
    * Diagonal
    * Spherical
  * Log-likelihood tracking
  * AIC & BIC model selection

---

## 🧪 Experiments

The project includes **comprehensive experiments and comparisons**:

1. K-Means on original data
2. GMM on original data
3. K-Means after PCA
4. GMM after PCA
5. K-Means after Autoencoder
6. GMM after Autoencoder

---

## 📈 Evaluation Metrics

### Internal Metrics:

* Silhouette Score
* Davies-Bouldin Index
* Calinski-Harabasz Index
* WCSS (Inertia)

### External Metrics:

* Adjusted Rand Index (ARI)
* Normalized Mutual Information (NMI)
* Purity Score

---

## 📊 Model Selection Techniques

* Elbow Method
* Silhouette Analysis
* Gap Statistic
* AIC / BIC (for GMM)

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## 📂 Dataset

The project uses a dataset loaded from:

```
data.csv
```

Example preprocessing steps:

* Handling missing values
* Feature normalization
* Label encoding (Benign vs Malignant)

---

## ▶️ How to Run

```bash
git clone https://github.com/ShamsNabih03/ml-from-scratch-unsupervised-learning.git
cd ml-from-scratch-unsupervised-learning
python unsupervised_learning_from_scratch.py
```

---

## 📌 Key Insights

* Autoencoders outperform PCA in capturing nonlinear structures
* K-Means is faster but assumes spherical clusters
* GMM provides more flexible clustering but is computationally heavier
* Best results achieved using:

  * Autoencoder + GMM (bottleneck ≈ 10–15)

---

## ⭐ Notes

This project is designed for:

* Learning machine learning fundamentals deeply
* Understanding algorithms beyond libraries
* Building strong AI/ML foundations

---
