# 📈 Linear Regression: From Scratch to Scikit-Learn

A structured machine learning project that implements **Linear Regression in two approaches**:

1. **From Scratch (Mathematical Implementation)**
2. **Using Scikit-Learn (Industry Standard Library)**

The goal is to build both **deep conceptual understanding** and **practical implementation skills** by comparing low-level algorithm design with production-grade tools.

---

## 🚀 Project Overview

This project focuses on:

- Understanding the mathematical foundation of Linear Regression  
- Implementing Gradient Descent manually  
- Comparing results with Scikit-learn’s optimized implementation  
- Building intuition around model training and evaluation  

---

## 🎯 Objectives

- Understand Linear Regression mathematically  
- Implement Gradient Descent from scratch  
- Analyze model convergence behavior  
- Compare manual vs library-based approaches  
- Evaluate performance using standard metrics  

---

## 📂 Project Structure

```
SIMPLE_LINEAR_REGRESSION/
│
├── simple_linear_regression_model.ipynb        # Scikit-learn implementation
├── simple_linear_regression_scratch.ipynb      # From-scratch implementation
├── placement.csv                               # Dataset
├── requirements.txt                            # Dependencies
├── README.md
└── .gitignore
```

---

## ⚙️ Tech Stack

| Technology        | Purpose                         |
|------------------|---------------------------------|
| Python           | Core programming language       |
| NumPy            | Mathematical computations       |
| Pandas           | Data handling                  |
| Matplotlib       | Visualization                  |
| Seaborn          | Statistical plots              |
| Scikit-learn     | ML model implementation        |
| Jupyter Notebook | Development environment        |

---

## 📊 Dataset Overview

**File:** `placement.csv`

The dataset contains student-related features used to predict placement outcomes.

Typical features include:

- Academic performance (e.g., CGPA)  
- Experience / skill indicators (if present)  
- Target variable: placement salary  

---

## 🧠 Model Approaches

### 1️⃣ Linear Regression from Scratch

Implemented using core mathematical principles.

#### Hypothesis Function

```
y = w*x + b
```

#### Loss Function (Mean Squared Error)

```
MSE = (1/n) * Σ (y_true - y_pred)^2
```

#### Optimization Technique

- Gradient Descent  
- Iterative weight and bias updates  

#### Key Learnings

- How coefficients (w, b) are updated  
- Effect of learning rate  
- Convergence behavior of model  

---

### 2️⃣ Scikit-Learn Implementation

Used:

```
sklearn.linear_model.LinearRegression
```

#### Steps

- Data preprocessing  
- Train-test split  
- Model fitting  
- Prediction  
- Evaluation  

#### Advantages

- Optimized performance  
- Clean and simple API  
- Production-ready  

---

## 📈 Evaluation Metrics

- **Mean Squared Error (MSE)**  
- **R² Score (Coefficient of Determination)**  

---

## 🔍 Key Comparison

| Aspect            | From Scratch        | Scikit-Learn        |
|------------------|--------------------|--------------------|
| Control          | Full               | Limited            |
| Speed            | Slower             | Optimized          |
| Learning Value   | High               | Moderate           |
| Production Use   | No                 | Yes                |

---

## 📊 Outputs

- Regression line visualization  
- Predictions vs actual comparison  
- Error metrics (MSE, R²)  
- Convergence behavior (for scratch model)  

---

## 🛠️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/RudrTyagi1135/SIMPLE_LINEAR_REGRESSION.git
cd SIMPLE_LINEAR_REGRESSION
```

---

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

---

### 3. Activate Environment

**Windows**
```bash
.venv\Scripts\activate
```

**Mac/Linux**
```bash
source .venv/bin/activate
```

---

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
jupyter notebook
```

Open:

- `simple_linear_regression_scratch.ipynb`  
- `simple_linear_regression_model.ipynb`  

---

## ⚠️ Limitations

- Assumes linear relationship between variables  
- Sensitive to outliers  
- Limited to simple regression (single feature)  
- No regularization applied  

---

## 🔮 Future Improvements

- Extend to Multiple Linear Regression  
- Add Regularization (Ridge, Lasso)  
- Implement feature scaling  
- Build Sklearn Pipeline  
- Convert into API (Flask / FastAPI)  
- Integrate into ML pipeline  

---

## 🎯 What This Project Demonstrates

- Strong understanding of ML fundamentals  
- Ability to implement algorithms from scratch  
- Knowledge of optimization techniques (Gradient Descent)  
- Comparison between theory and production tools  
- Structured ML experimentation workflow  

---

## 📌 Next Step

Recommended progression:

- End-to-end ML pipeline  
- Model deployment (API)  
- MLOps integration  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure
