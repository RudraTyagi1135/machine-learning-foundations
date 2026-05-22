# 🧠 Naive Bayes: From Probability Theory to Real-World Sentiment Analysis

A structured machine learning project that explores the **Naive Bayes algorithm** from fundamental probability theory to real-world **NLP-based sentiment analysis**.

This project focuses on understanding probabilistic modeling and applying it to **text classification problems using the IMDB dataset**.

---

## 🚀 Project Overview

This project provides an end-to-end understanding of Naive Bayes by covering:

- Probability fundamentals and Bayes Theorem  
- Naive Bayes algorithm implementation  
- Sentiment analysis using real-world text data  

The goal is to move from:

> **Using Naive Bayes → Understanding probabilistic modeling and applying it to NLP systems**

---

## 🎯 Objectives

- Understand Bayes Theorem and probabilistic reasoning  
- Implement Naive Bayes for classification  
- Apply Naive Bayes to:
  - text data  
  - sentiment classification  
- Build intuition for:
  - prior probabilities  
  - likelihood  
  - posterior probabilities  

---

## 🧠 Core Concepts Covered

- Probability fundamentals  
- Bayes Theorem  
- Conditional probability  
- Naive Bayes assumption (feature independence)  
- Likelihood estimation  
- Text preprocessing:
  - tokenization  
  - vectorization (Bag of Words / TF-IDF)  

---

## 📂 Project Structure

```
NAIVE_BAYES/
│
├── IMDB Dataset.csv                         # Real-world sentiment dataset
│
├── probability.ipynb                        # Probability and Bayes theorem fundamentals
├── naive_bayes.ipynb                        # Naive Bayes implementation
├── sentiment_analysis_using_naive_bayes.ipynb  # NLP pipeline for sentiment classification
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ Probability Fundamentals

- Implements:
  - conditional probability  
  - Bayes theorem  

**Key Insight:**

- Naive Bayes is grounded in probabilistic reasoning  

---

### 2️⃣ Naive Bayes Algorithm

- Computes:
  - prior probabilities  
  - likelihoods  
  - posterior probabilities  

**Key Insight:**

- Assumes feature independence  
- Efficient and scalable for high-dimensional data  

---

### 3️⃣ Sentiment Analysis (IMDB Dataset)

- Applies Naive Bayes to text classification  
- Pipeline includes:
  - text preprocessing  
  - feature extraction (vectorization)  
  - model training and prediction  

**Key Insight:**

- Naive Bayes performs well in NLP tasks despite independence assumption  

---

## 📊 Key Observations

### ⚡ Efficiency

- Fast training and inference  
- Works well with large text datasets  

---

### 📉 Independence Assumption

- Assumes features are independent  
- Not always true in real-world data  

---

### 📈 NLP Performance

- Performs strongly in:
  - sentiment analysis  
  - spam detection  
  - document classification  

---

## ⚠️ Limitations

- Strong independence assumption  
- No comparison with other models (Logistic Regression, SVM)  
- No hyperparameter tuning  
- No cross-validation evaluation  
- Notebook-based (not modular pipeline)  

---

## 🔮 Future Improvements

- Compare with:
  - Logistic Regression  
  - SVM  
- Add TF-IDF vs Bag-of-Words comparison  
- Implement cross-validation  
- Add confusion matrix and evaluation metrics  
- Improve preprocessing:
  - stopword removal  
  - stemming / lemmatization  
- Convert into modular pipeline  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/RudrTyagi1135/NAIVE_BAYES.git
cd NAIVE_BAYES
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

- `probability.ipynb`  
- `naive_bayes.ipynb`  
- `sentiment_analysis_using_naive_bayes.ipynb`  

---

## 📊 Outputs

- Probability and Bayes theorem demonstrations  
- Naive Bayes classification results  
- Sentiment analysis predictions on IMDB dataset  

---

## 🎯 What This Project Demonstrates

- Strong understanding of probabilistic machine learning  
- Ability to apply theory to real-world NLP problems  
- Knowledge of text preprocessing and feature extraction  
- Understanding of model assumptions and limitations  

---

## 📌 Next Step

- Build full NLP pipeline with multiple models  
- Integrate evaluation metrics (F1, ROC-AUC)  
- Deploy sentiment analysis as API  
- Extend to deep learning models (LSTM / Transformers)  

---

## 👤 Author

**Rudra Tyagi**

ML Systems | MLOps | AI Infrastructure