# 📊 Regression Analysis: From Assumptions to Model Behavior

A structured machine learning project focused on **understanding Linear Regression beyond implementation**, covering:

- Statistical assumptions  
- Model diagnostics  
- Feature relationships  
- Failure modes (multicollinearity, overfitting)  

This project shifts focus from:

> **Model fitting → Model reliability, interpretability, and failure analysis**

---

## 🚀 Project Overview

This project explores regression from a **system and analytical perspective**, emphasizing:

- Assumption validation  
- Residual analysis  
- Feature interaction behavior  
- Model stability and generalization  

It provides a deeper understanding of **when and why regression models fail**.

---

## 🎯 Objectives

- Understand the **complete regression workflow**  
- Validate **core assumptions of linear regression**  
- Diagnose **multicollinearity and instability**  
- Explore **non-linear relationships using polynomial regression**  
- Analyze **bias–variance tradeoff and generalization behavior**  

---

## 🧠 Core Concepts Covered

- Linear Regression (OLS)  
- Residual analysis  
- Assumptions of Linear Regression:
  - Linearity  
  - Independence  
  - Homoscedasticity  
  - Normality of residuals  
- Multicollinearity  
- Polynomial Regression  
- Bias–Variance tradeoff  

---

## 📂 Project Structure

```
REGRESSION_ANALYSIS/
│
├── regression_analysis.ipynb               # End-to-end regression workflow
├── assumptions_of_linear_regression.ipynb  # Assumption validation + residual analysis
├── multicollinearity.ipynb                # Feature correlation analysis
├── polynomial_regression.ipynb            # Non-linear modeling
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ Regression Analysis

- Basic regression pipeline:
  - Data loading / generation  
  - Model fitting  
  - Prediction and evaluation  

Establishes baseline behavior for further diagnostics.

---

### 2️⃣ Assumptions of Linear Regression

Validates core assumptions:

#### ✔ Linearity
- Scatter plots between features and target  

#### ✔ Normality of Residuals
- Histogram and distribution analysis  

#### ✔ Homoscedasticity
- Residuals vs predictions  

#### ✔ Independence
- Observational assumption (or visual inspection)  

**Insight:** Violating these assumptions leads to unreliable coefficients and poor generalization.

---

### 3️⃣ Multicollinearity Analysis

- Correlation matrix and heatmaps  
- Identifies relationships between input features  

**Key Insight:**

- Highly correlated features cause:
  - Unstable coefficients  
  - Reduced interpretability  

---

### 4️⃣ Polynomial Regression

- Extends linear regression to capture non-linear patterns  
- Uses polynomial feature transformation  

**Key Insight:**

- Higher degree:
  - Reduces bias  
  - Increases variance (overfitting risk)  

---

## 📊 Key Observations

### 📉 Residual Behavior

- Residual patterns indicate model quality  
- Non-random distribution → assumption violation  

---

### ⚠️ Multicollinearity

- Strong feature correlation destabilizes model coefficients  
- Model becomes sensitive to small data variations  

---

### 📈 Model Complexity

- Increasing polynomial degree:
  - ↓ Bias  
  - ↑ Variance  

---

## ⚠️ Limitations

- No Variance Inflation Factor (VIF) implemented  
- No statistical tests (Durbin-Watson, Shapiro-Wilk)  
- No train vs test error comparison  
- No feature scaling  
- Notebook-based (not modular pipeline)  

---

## 🔮 Future Improvements

- Add VIF for multicollinearity detection  
- Implement train vs test error comparison  
- Add residual diagnostic plots (QQ plot, residual vs fitted)  
- Include regularization (Ridge, Lasso)  
- Build modular pipeline (fit → evaluate → diagnose)  
- Add experiment tracking (MLflow or logging)  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/REGRESSION_ANALYSIS.git
cd REGRESSION_ANALYSIS
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

- `regression_analysis.ipynb`  
- `assumptions_of_linear_regression.ipynb`  
- `multicollinearity.ipynb`  
- `polynomial_regression.ipynb`  

---

## 📊 Outputs

- Residual analysis plots  
- Correlation heatmaps  
- Polynomial regression visualizations  
- Model behavior comparisons  

---

## 🎯 What This Project Demonstrates

- Understanding of regression assumptions and diagnostics  
- Ability to analyze model stability and failure modes  
- Strong foundation in statistical modeling  
- Insight into bias–variance tradeoff  
- Analytical thinking for real-world ML systems  

---

## 📌 Next Step

- Integrate into full ML pipeline  
- Add model evaluation frameworks  
- Extend with regularization and feature engineering  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure