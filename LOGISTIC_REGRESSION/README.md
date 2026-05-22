# 📈 Logistic Regression: From Binary Classification to Softmax

A structured machine learning project that explores **Logistic Regression** from core binary classification to advanced multi-class extensions.

This project focuses on understanding the **mathematical foundations, decision boundaries, and extensions of logistic regression**.

---

## 🚀 Project Overview

This project covers multiple aspects of logistic regression:

- Binary classification using sigmoid function  
- Non-linear classification using polynomial features  
- Multi-class classification using Softmax regression  

The goal is to move from:

> **Using Logistic Regression → Understanding its mathematical behavior and extensions**

---

## 🎯 Objectives

- Understand how logistic regression works mathematically  
- Build intuition for:
  - sigmoid function  
  - decision boundaries  
- Extend logistic regression to:
  - non-linear problems  
  - multi-class classification  

---

## 🧠 Core Concepts Covered

### Binary Classification

- Sigmoid function  
- Log-odds (logit function)  
- Decision boundary  

### Optimization

- Log loss function  
- Gradient-based learning  

### Feature Engineering

- Polynomial feature expansion  
- Non-linear separability  

### Multi-class Classification

- Softmax function  
- Probability distribution across classes  

---

## 📂 Project Structure

```
LOGISTIC_REGRESSION/
│
├── logistic_regression_session.ipynb       # Binary classification
├── polynomial_logistic_regression.ipynb   # Non-linear classification
├── softmax_demo.ipynb                     # Multi-class classification
│
├── ushape.csv                             # Non-linear dataset
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ Logistic Regression (Binary)

- Uses sigmoid function to model probabilities  
- Learns a linear decision boundary  

**Key Insight:**

- Outputs probabilities instead of direct class labels  

---

### 2️⃣ Polynomial Logistic Regression

- Applies feature transformation to capture non-linearity  

**Key Insight:**

- Linear model + feature engineering → non-linear decision boundary  

---

### 3️⃣ Softmax Regression

- Extends logistic regression to multi-class problems  

**Key Insight:**

- Produces probability distribution across multiple classes  

---

## 📊 Key Observations

### 📈 Linear vs Non-Linear

- Basic logistic regression struggles with non-linear data  
- Polynomial features improve performance significantly  

---

### ⚖️ Model Complexity

- Higher-degree polynomial → better fit  
- Increased risk of overfitting  

---

### 🔢 Multi-class Capability

- Softmax enables:
  - multi-class classification  
  - probabilistic interpretation  

---

## ⚠️ Limitations

- No regularization tuning (L1/L2)  
- No cross-validation  
- No comparison with:
  - Decision Trees  
  - SVM  
- Notebook-based (not modular pipeline)  

---

## 🔮 Future Improvements

- Add:
  - L1 (Lasso) and L2 (Ridge) regularization  
- Implement:
  - cross-validation  
  - hyperparameter tuning  
- Compare with:
  - SVM  
  - Random Forest  
- Convert into:
  - Scikit-learn Pipeline  
  - Modular training scripts  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/logistic_regression.git
cd logistic_regression
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

- `logistic_regression_session.ipynb`  
- `polynomial_logistic_regression.ipynb`  
- `softmax_demo.ipynb`  

---

## 📊 Outputs

- Binary classification decision boundaries  
- Non-linear classification results  
- Multi-class probability predictions  

---

## 🎯 What This Project Demonstrates

- Strong understanding of classification algorithms  
- Ability to extend models using feature engineering  
- Knowledge of probabilistic modeling  
- Understanding of multi-class learning techniques  

---

## 📌 Next Step

- Add regularization and model tuning  
- Integrate into full ML pipeline  
- Deploy classification model as API  
- Compare with advanced classification algorithms  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure