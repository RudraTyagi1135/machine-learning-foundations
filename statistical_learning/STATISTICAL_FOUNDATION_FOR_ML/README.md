# 📊 Statistical Foundations for Machine Learning Systems

A structured, experiment-driven repository focused on **statistical concepts that directly influence machine learning system behavior**.

This project emphasizes **data behavior, transformations, and model impact**, using simulations, visualizations, and controlled experiments.

---

## 🚀 Project Overview

Machine learning systems are highly sensitive to:

- Data distribution  
- Feature relationships  
- Statistical assumptions  

This repository explores these factors through experiments, focusing on:

> Understanding how **data transformations affect model performance and reliability**

---

## 🎯 Objectives

- Analyze **probability distributions and cumulative behavior**
- Understand **covariance vs correlation under scaling**
- Evaluate **impact of feature transformations on models**
- Connect statistical concepts to **real ML system decisions**

---

## 📂 Project Structure

```bash
STATISTICAL_FOUNDATION_FOR_ML/
│
├── 00_data/
│   ├── concrete_data.csv
│   └── train.csv
│
├── 01_probability_and_simulation/
│   └── probability-distribution-simulation-and-kde.ipynb
│
├── 02_distribution_analysis/
│   ├── covariance-vs-correlation-scale-invariance-analysis.ipynb
│   └── qq-plots-and-statistical-distribution-fitting.ipynb
│
├── 03_feature_engineering/
│   ├── log-transformation-impact-on-classification-models.ipynb
│   └── power-transformations-for-linear-regression.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Module Breakdown

### 1️⃣ Probability & Simulation

- Empirical PMF and CDF construction  
- Distribution simulation (dice, normal sampling)  
- Kernel Density Estimation (KDE)  

**System Insight:**

- Probability distributions emerge from repeated sampling  
- CDF is critical for threshold-based decision systems  

---

### 2️⃣ Distribution Analysis

#### a) QQ Plots & Distribution Fitting

- Distribution diagnostics using QQ plots  
- Comparison across multiple distributions  

**System Insight:**

- Model assumptions depend on data distribution  
- Misaligned assumptions → unstable models  

---

#### b) Covariance vs Correlation

- Scaling impact on covariance  
- Scale invariance of correlation  

**System Insight:**

- Correlation is reliable for feature comparison  
- Covariance is not stable across transformations  

---

### 3️⃣ Feature Engineering (Statistical Transformations)

#### a) Log Transformation (Classification)

- Skewness reduction using `log1p`  
- Model comparison:

  - Logistic Regression  
  - Decision Tree  

**System Insight:**

- Scale-sensitive models improve with normalization  
- Tree-based models remain mostly unaffected  

---

#### b) Power Transformations (Regression)

- Box-Cox and Yeo-Johnson transformations  
- Regression performance improvement  

**System Insight:**

- Aligning data with model assumptions improves performance  
- Transformation choice directly impacts linear models  

---

## 🧪 Workflow

```
Data → Distribution Analysis → Transformation → Model Training → Evaluation → Interpretation
```

---

## 📊 Key Observations

- Data distribution strongly affects model behavior  
- Transformations improve performance for linear models  
- Correlation is more robust than covariance for feature analysis  
- Statistical diagnostics prevent incorrect modeling assumptions  

---

## 🛠️ Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- SciPy  
- Statsmodels  

---

## ▶️ How to Run

```bash
git clone https://github.com/RudrTyagi1135/STATISTICAL_FOUNDATION_FOR_ML.git
cd STATISTICAL_FOUNDATION_FOR_ML

pip install -r requirements.txt
jupyter notebook
```

---

## ⚠️ Limitations

- Notebook-based implementation (no modular pipeline)  
- Limited evaluation metrics  
- No integration with production ML workflows  

---

## 🚀 Future Improvements (High Impact)

### 1️⃣ Evaluation Upgrade

- Add R², ROC-AUC, F1-score  
- Compare model performance before vs after transformations  

---

### 2️⃣ Pipeline Integration

- Build preprocessing + model pipelines  
- Ensure reproducibility  

---

### 3️⃣ System-Level Extension

- Apply on real-world datasets  
- Integrate into end-to-end ML workflows  

---

## 🎯 What This Project Demonstrates

- Strong statistical intuition for ML systems  
- Understanding of **data → transformation → model behavior**  
- Ability to analyze feature distributions and relationships  
- Awareness of how preprocessing impacts model reliability  

---

## 📌 Key Takeaway

Statistical understanding is not theoretical —  
it directly determines how **ML systems behave, generalize, and fail**.

---

## 👤 Author

**Rudra Tyagi**  
ML Systems | MLOps | AI Infrastructure