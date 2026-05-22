# 📊 Statistical Inference Pipeline for Structured Data

### Hypothesis Testing & Distribution Analysis on Titanic Dataset

---

## 🔷 Project Overview

This project implements a **statistical inference pipeline on structured data**, using the Titanic dataset as a case study.

Rather than isolated statistical experiments, the repository is structured to demonstrate how **statistical validation, distribution analysis, and hypothesis testing integrate into machine learning workflows**.

The focus is on:

- Validating data assumptions before modeling  
- Quantifying relationships between variables  
- Supporting data-driven decisions using statistical evidence  

---

## 🎯 Objectives

- Apply statistical inference techniques on real-world tabular data  
- Validate assumptions required for downstream modeling  
- Analyze feature relationships using hypothesis testing  
- Build a structured, reproducible statistical workflow  

---

## 📂 Project Structure

```
STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING/
│
├── notebooks/
│   ├── probability_distributions_and_clt_simulation.ipynb
│   ├── central_limit_theorem_titanic_sampling_distribution.ipynb
│   ├── statistical_assumption_testing_normality_variance_checks.ipynb
│   ├── one_sample_t_test_titanic_population_mean_analysis.ipynb
│   ├── two_sample_t_test_titanic_group_comparison.ipynb
│   ├── anova_and_posthoc_analysis_titanic_age_vs_class.ipynb
│   ├── chi_square_test_titanic_distribution_analysis.ipynb
│
├── data/
│   ├── train.csv
│   ├── test.csv
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Implementation Breakdown

### 1. Distribution Analysis
- Simulates and analyzes probability distributions  
- Examines sampling behavior and variance characteristics  

### 2. Sampling & CLT
- Demonstrates convergence of sample means  
- Validates applicability of normal approximation  

### 3. Assumption Validation
- Tests for:
  - Normality (Shapiro-Wilk)  
  - Homogeneity of variance (Levene)  
- Determines suitability of statistical tests  

### 4. Hypothesis Testing
Implements:

- One-sample t-test → population comparison  
- Two-sample t-test → group comparison  
- ANOVA → multi-group variance analysis  
- Chi-square → categorical independence testing  

### 5. Interpretation Layer
- Converts statistical outputs into actionable conclusions  
- Focuses on significance thresholds and decision boundaries  

---

## 🔁 Workflow

The system follows a structured statistical pipeline:

1. **Data Ingestion**  
   Load dataset from local or remote source  

2. **Distribution Analysis**  
   Understand feature distributions and sampling behavior  

3. **Assumption Validation**  
   Verify normality and variance conditions  

4. **Hypothesis Formulation**  
   Define null and alternative hypotheses  

5. **Statistical Testing**  
   Apply appropriate test based on data characteristics  

6. **Result Interpretation**  
   Evaluate significance and derive insights  

---

## 📊 Key Observations

- Survival shows strong statistical dependence on gender  
- Passenger class significantly impacts age distribution  
- Real-world data often only approximately satisfies statistical assumptions  
- Parametric tests remain usable under mild assumption violations  

---

## 🧰 Tech Stack

- Python  
- Pandas, NumPy  
- SciPy, Statsmodels  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## ▶️ How to Run

### 1. Clone Repository
```bash
git clone <repo-link>
cd STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Load Dataset
```python
import pandas as pd

url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
df = pd.read_csv(url)
```

### 4. Run Notebooks
```bash
jupyter notebook
```

---

## ⚠️ Limitations

- Small dataset limits statistical power  
- Assumptions (normality, equal variance) are only approximately satisfied  
- Notebook-based structure limits reusability in production systems  
- No integration with downstream ML pipelines  

---

## 🚀 Future Improvements

- Convert notebooks into modular Python components  
- Integrate statistical validation into ML preprocessing pipelines  
- Add non-parametric tests for robustness  
- Automate statistical testing workflows  
- Extend to larger, real-world datasets  

---

## 🧠 What This Project Demonstrates

- Ability to design a **structured statistical validation pipeline**  
- Understanding of **data assumptions before model training**  
- Application of **hypothesis-driven analysis on real data**  
- Awareness of **limitations and real-world data behavior**  

---

## 📌 Key Takeaway

Statistical validation is a critical upstream component of ML systems.  
This project demonstrates how **data assumptions, distribution behavior, and hypothesis testing directly impact model reliability and decision quality**.

---

## 👤 Author

**Rudra**  
ML Systems / AI Infrastructure Engineer 