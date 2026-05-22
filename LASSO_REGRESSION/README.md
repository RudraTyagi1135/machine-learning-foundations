# 🔍 Lasso Regression: Sparse Modeling and Feature Selection with L1 Regularization

A structured machine learning project that explores **Lasso Regression (L1 Regularization)** with a focus on sparse modeling, automatic feature selection, and regularization-driven optimization.

This project demonstrates how L1 regularization enables **feature elimination**, making models simpler, interpretable, and robust.

---

## 🚀 Project Overview

This project analyzes Lasso Regression from a **practical ML systems perspective**, focusing on:

- Sparse model learning  
- Automatic feature selection  
- Impact of regularization strength (λ)  
- Comparison with traditional linear regression behavior  

The goal is to understand:

> **Overfitting → Regularization → Sparsity → Feature Selection**

---

## 🎯 Objectives

- Understand limitations of Linear Regression (overfitting, high variance)  
- Implement Lasso Regression using L1 regularization  
- Analyze how L1 penalty drives coefficients to zero  
- Study impact of λ (lambda) on:
  - model sparsity  
  - feature selection  
  - generalization  

---

## 🧠 Core Concepts Covered

- Linear Regression (OLS)  
- Overfitting and model complexity  
- L1 Regularization (Lasso)  
- Loss Function:

```
Loss = MSE + λ * Σ|w_i|
```

- Sparse solutions and feature selection  
- Bias–Variance Tradeoff  
- Coefficient shrinkage vs elimination  

---

## 📂 Project Structure

```
LASSO_REGRESSION/
│
├── lasso_regression.ipynb              # Core implementation and experimentation
├── lasso_regression_key_points.ipynb   # Conceptual insights and summary
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ Lasso Regression Implementation

- Applies L1 regularization to penalize model complexity  
- Computes model coefficients under L1 constraint  

**Key Behavior:**

- Coefficients are **shrunk toward zero**  
- Some coefficients become **exactly zero → feature elimination**  

---

### 2️⃣ Feature Selection via Lasso

- Automatically selects relevant features  
- Removes:
  - noisy features  
  - redundant variables  

**Key Insight:**

- Lasso performs **embedded feature selection during training**  

---

### 3️⃣ Effect of Regularization Strength (λ)

- Increasing λ:
  - More coefficients → 0  
  - Simpler model  
  - Risk of underfitting  

- Decreasing λ:
  - More features retained  
  - Risk of overfitting  

---

### 4️⃣ Conceptual Understanding

- Comparison:
  - Lasso vs Ridge  
  - Shrinkage vs sparsity  
- When to use Lasso in real-world scenarios  

---

## 📊 Key Observations

### 📉 Sparsity Behavior

| λ Value | Effect |
|--------|--------|
| 0 | Equivalent to Linear Regression |
| Small | Minor shrinkage |
| Medium | Feature selection begins |
| Large | Aggressive sparsity (underfitting risk) |

---

### ⚖️ Lasso vs Ridge

| Aspect | Lasso (L1) | Ridge (L2) |
|------|------------|------------|
| Feature Selection | ✅ Yes | ❌ No |
| Coefficient Shrinkage | Yes | Yes |
| Zero Coefficients | ✅ Possible | ❌ Never |
| Stability | ⚠️ Less stable | ✅ More stable |

---

## ⚠️ Limitations

- No feature scaling pipeline (important for Lasso)  
- No λ tuning (no cross-validation)  
- No direct comparison with Ridge/OLS  
- No performance benchmarking (R², MSE)  
- Notebook-based (not modular pipeline)  

---

## 🔮 Future Improvements

- Add StandardScaler before Lasso  
- Implement LassoCV for automatic λ tuning  
- Compare:
  - OLS vs Ridge vs Lasso  
- Plot:
  - λ vs number of selected features  
  - λ vs error  
- Use real-world high-dimensional dataset  
- Build feature selection pipeline integration  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/LASSO_REGRESSION.git
cd LASSO_REGRESSION
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

- `lasso_regression.ipynb`
- `lasso_regression_key_points.ipynb`

---

## 📊 Outputs

- Lasso regression implementation  
- Visualization of coefficient shrinkage  
- Feature selection behavior analysis  
- Understanding of sparsity and regularization effects  

---

## 🎯 What This Project Demonstrates

- Strong understanding of L1 regularization  
- Ability to build sparse ML models  
- Knowledge of embedded feature selection techniques  
- Understanding of bias-variance tradeoff in practice  

---

## 📌 Next Step

- Integrate into full ML pipeline  
- Add automated hyperparameter tuning  
- Extend to ElasticNet  
- Build production-ready feature selection module  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure