# ⚖️ Elastic Net Regression: Balancing Sparsity and Stability in Linear Models

A structured machine learning project that implements **Elastic Net Regression**, combining L1 (Lasso) and L2 (Ridge) regularization to balance sparsity and stability in linear models.

This project demonstrates how Elastic Net addresses limitations of both Ridge and Lasso, especially in scenarios involving correlated features and high-dimensional datasets.

---

## 🚀 Project Overview

This project explores Elastic Net from a **practical ML systems perspective**, focusing on:

- Hybrid regularization (L1 + L2)  
- Feature selection vs coefficient stability  
- Impact of hyperparameters (λ and α)  
- Behavior in correlated feature spaces  

The goal is to move from:

> **Choosing between Ridge or Lasso → Designing optimal regularization strategies**

---

## 🎯 Objectives

- Understand why Elastic Net is required beyond Ridge and Lasso  
- Implement Elastic Net using a regularized loss function  
- Analyze impact of:
  - λ (regularization strength)  
  - α (mixing parameter)  
- Study how sparsity and stability interact in model behavior  

---

## 🧠 Core Concepts Covered

- Linear Regression (OLS)  
- Ridge Regression (L2)  
- Lasso Regression (L1)  
- Elastic Net (L1 + L2)  

### Loss Function

```
Loss = MSE + λ * (α * Σ|w_i| + (1 - α) * Σ(w_i²))
```

- Sparsity vs stability tradeoff  
- Feature selection vs coefficient shrinkage  
- Regularization tuning  

---

## 📂 Project Structure

```
ELASTICNET_REGRESSION/
│
├── elasti_net_regression.ipynb   # Core implementation and experiments
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ Elastic Net Formulation

- Combines L1 and L2 penalties into a unified loss function  
- Introduces two hyperparameters:

  - λ → overall regularization strength  
  - α → balance between L1 and L2  

---

### 2️⃣ Model Behavior Analysis

- Varying α:

  - α = 1 → Lasso  
  - α = 0 → Ridge  
  - 0 < α < 1 → Elastic Net  

**Key Insight:**

- Elastic Net interpolates between sparsity and stability  

---

### 3️⃣ Coefficient Behavior

- Some coefficients shrink to zero (L1 effect)  
- Others are reduced but retained (L2 effect)  

**Result:**

- Handles multicollinearity better than Lasso  
- Produces more stable models  

---

### 4️⃣ Practical Observations

- Effective in high-dimensional datasets  
- Performs well when features are correlated  
- Balances bias and variance effectively  

---

## 📊 Key Observations

### ⚖️ Ridge vs Lasso vs Elastic Net

| Model | Feature Selection | Stability | Best Use Case |
|------|------------------|----------|---------------|
| Ridge | ❌ No | ✅ High | Multicollinearity |
| Lasso | ✅ Yes | ⚠️ Low | Sparse models |
| Elastic Net | ✅ Partial | ✅ Balanced | Correlated features |

---

### 📉 Effect of α

| α Value | Behavior |
|--------|----------|
| 0 | Ridge behavior |
| 1 | Lasso behavior |
| 0.5 | Balanced regularization |

---

## ⚠️ Limitations

- No feature scaling applied (important for Elastic Net)  
- No cross-validation for λ and α tuning  
- No comparison with Ridge/Lasso in same pipeline  
- No performance benchmarking (MSE, R²)  
- Notebook-based implementation (not modular pipeline)  

---

## 🔮 Future Improvements

- Add StandardScaler + ElasticNet pipeline  
- Implement ElasticNetCV for hyperparameter tuning  
- Compare:
  - OLS vs Ridge vs Lasso vs Elastic Net  
- Plot:
  - α vs number of selected features  
  - λ vs error  
- Use real-world high-dimensional dataset  
- Add automated model selection pipeline  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/ELASTICNET_REGRESSION.git
cd ELASTICNET_REGRESSION
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

- `elasti_net_regression.ipynb`

---

## 📊 Outputs

- Elastic Net model implementation  
- Visualization of regularization effects  
- Understanding of sparsity vs stability tradeoff  
- Hyperparameter impact analysis (λ, α)  

---

## 🎯 What This Project Demonstrates

- Strong understanding of advanced regularization techniques  
- Ability to combine L1 and L2 strategies effectively  
- Knowledge of handling multicollinearity  
- Understanding of bias-variance tradeoff in practice  

---

## 📌 Next Step

- Integrate into full ML pipeline  
- Add automated hyperparameter tuning  
- Extend to model selection systems  
- Build production-ready regression service  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure