# 🤖 K-Nearest Neighbors (KNN): From Scratch to Real-World Decision Boundaries

A structured machine learning project that explores the **K-Nearest Neighbors (KNN)** algorithm through from-scratch implementation, decision boundary visualization, and real-world dataset evaluation.

This project focuses on understanding how **distance-based models behave under different data conditions and parameter settings**.

---

## 🚀 Project Overview

This project analyzes KNN from a **geometric and data-driven perspective**, focusing on:

- Distance-based learning  
- Effect of number of neighbors (k)  
- Decision boundary behavior  
- Performance across different data distributions  

The goal is to move from:

> **Using KNN → Understanding how instance-based models behave in different scenarios**

---

## 🎯 Objectives

- Implement KNN from scratch using NumPy  
- Understand impact of:
  - distance metrics  
  - number of neighbors (k)  
- Visualize decision boundaries  
- Analyze behavior on:
  - synthetic datasets  
  - real-world datasets  
- Evaluate performance in practical scenarios  

---

## 🧠 Core Concepts Covered

- K-Nearest Neighbors algorithm  
- Distance metrics (Euclidean)  
- Instance-based (lazy) learning  
- Decision boundaries  
- Effect of k (bias vs variance)  
- Sensitivity to noise and outliers  
- Importance of feature scaling  

---

## 📂 Project Structure

```
KNN/
│
├── data/
│   ├── data.csv
│   ├── Social_Network_Ads.csv
│
├── toy_datasets/
│   ├── concentriccir2.csv
│   ├── linearsep.csv
│   ├── outlier.csv
│   ├── twoSpirals.csv
│   ├── ushape.csv
│   └── xor.csv
│
├── knn_from_scratch.ipynb                 # Core implementation
├── knn_classifier_decision_boundary.ipynb # Decision boundary visualization
├── knn_on_breast_cancer_dataset.ipynb     # Real-world evaluation
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ KNN from Scratch

- Implemented using NumPy  
- Core steps:
  - Compute distances  
  - Select k nearest neighbors  
  - Majority voting  

**Key Insight:**

- KNN is a **lazy learning algorithm (no training phase)**  

---

### 2️⃣ Decision Boundary Visualization

- Applied KNN on multiple synthetic datasets  
- Visualized how boundaries change with:
  - different values of k  
  - different data distributions  

**Datasets Used:**

- Linear separable  
- XOR (non-linear)  
- Two spirals  
- U-shape  
- Outlier dataset  

**Key Insight:**

- KNN can model highly non-linear boundaries  
- Increasing k smooths decision boundaries  

---

### 3️⃣ Real-World Dataset (Breast Cancer)

- Applied KNN on a medical dataset  
- Evaluated classification performance  

**Key Insight:**

- Highlights importance of:
  - feature scaling  
  - proper k selection  

---

## 📊 Key Observations

### 📉 Effect of k (Neighbors)

| k Value | Behavior |
|--------|----------|
| Small k | Overfitting (high variance) |
| Large k | Underfitting (high bias) |

---

### 📈 Decision Boundary Behavior

- Small k → highly irregular boundaries  
- Large k → smoother boundaries  

---

### ⚠️ Sensitivity

KNN is sensitive to:

- Feature scaling  
- Noise  
- Outliers  

---

## ⚠️ Limitations

- No feature scaling pipeline applied  
- No hyperparameter tuning (k optimization)  
- Computationally expensive for large datasets  
- No KD-tree / Ball-tree optimization  
- No comparison with other classifiers  

---

## 🔮 Future Improvements

- Add StandardScaler (important for KNN)  
- Implement GridSearch for optimal k selection  
- Add distance metric comparison (Manhattan, Minkowski)  
- Use KD-Tree / Ball-Tree for faster computation  
- Compare with:
  - Logistic Regression  
  - SVM  
- Add cross-validation  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/KNN.git
cd KNN
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
jupyter notebook
```

Open:

- `knn_from_scratch.ipynb`
- `knn_classifier_decision_boundary.ipynb`
- `knn_on_breast_cancer_dataset.ipynb`

---

## 📊 Outputs

- KNN implementation from scratch  
- Decision boundary visualizations  
- Performance evaluation on real dataset  
- Understanding of k impact on model behavior  

---

## 🎯 What This Project Demonstrates

- Strong understanding of instance-based learning  
- Ability to implement ML algorithms from scratch  
- Knowledge of geometric interpretation of models  
- Understanding of bias-variance tradeoff in non-parametric models  

---

## 📌 Next Step

- Integrate into full ML pipeline  
- Add hyperparameter tuning  
- Optimize for large-scale datasets  
- Build production-ready classification system  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure