# 🚀 KMeans Clustering: From Scratch to Real-World Applications

A structured machine learning project focused on **implementing KMeans from scratch**, validating it on synthetic data, and applying it to **real-world datasets (IPL and NYC Taxi)**.

This project demonstrates both **algorithm-level understanding** and **practical clustering workflows**, moving from fundamentals to scalable data analysis.

---

## 🚀 Project Overview

Most implementations rely directly on `sklearn.KMeans`.

This project focuses on:

- Building KMeans from scratch  
- Understanding clustering internals  
- Applying clustering to real-world datasets  
- Exploring scalability using MiniBatch KMeans  

---

## 🎯 Objectives

- Implement KMeans without external libraries  
- Understand:
  - centroid initialization  
  - distance computation  
  - convergence behavior  
- Apply clustering to:
  - synthetic data  
  - structured datasets  
  - large-scale real-world data  
- Explore performance trade-offs  

---

## 📂 Project Structure

```bash
KMEANS_CLUSTERING/
│
├── data/
│   ├── IPL_Ball_by_Ball_2008_2022.csv
│   ├── student_clustering.csv
│   └── yellow_tripdata_2016-01.csv #please download using the  link given in notebook
│
├── notebooks/
│   ├── 01_kmeans_basics.ipynb
│   ├── 02_kmeans_assignment.ipynb
│   ├── 03_kmeans_practical_demo.ipynb
│   ├── 04_ipl_clustering.ipynb
│   └── 05_minibatch_experiment.ipynb
│
├── kmeans.py
├── app.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Core Implementation

### Custom KMeans Algorithm

Implemented in:

```bash
kmeans.py
```

### Key Components:

- Random centroid initialization  
- Euclidean distance computation  
- Iterative centroid updates  
- Convergence detection  

### Core Methods:

```python
fit_predict()
assign_clusters()
move_centroids()
```

---

## 📊 Datasets Used

### 1️⃣ Student Dataset

- Small structured dataset  
- Used for visualization and validation  

---

### 2️⃣ IPL Dataset

- Player and match-level data  
- Used for clustering behavior analysis  

---

### 3️⃣ NYC Taxi Dataset

- Large-scale dataset  
- Used to test scalability with MiniBatch KMeans  

---

## 📘 Notebooks Overview

### 1️⃣ KMeans Basics

`01_kmeans_basics.ipynb`

- Synthetic data experiments  
- Clustering intuition  

---

### 2️⃣ Implementation Practice

`02_kmeans_assignment.ipynb`

- Step-by-step reinforcement of algorithm logic  

---

### 3️⃣ Practical Demo

`03_kmeans_practical_demo.ipynb`

- Applies custom KMeans on structured dataset  
- Visualization using Matplotlib / Plotly  

---

### 4️⃣ IPL Clustering

`04_ipl_clustering.ipynb`

- Real-world clustering use case  
- Behavioral pattern analysis  

---

### 5️⃣ MiniBatch Experiment

`05_minibatch_experiment.ipynb`

- Scalable clustering using sklearn  
- Performance comparison  

---

## 🧪 Workflow

```
Data → Feature Selection → Clustering → Visualization → Interpretation
```

---

## 📊 Key Observations

- KMeans is sensitive to centroid initialization  
- Real-world datasets require preprocessing  
- MiniBatch KMeans improves scalability  
- Cluster interpretation depends heavily on feature selection  

---

## 🛠️ Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Plotly  
- Scikit-learn (MiniBatch comparison only)  

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Run script

```bash
python app.py
```

### Run notebooks

```bash
jupyter notebook
```

---

## ⚠️ Limitations

- Uses random initialization (no KMeans++)  
- No evaluation metrics (silhouette score, inertia)  
- Limited preprocessing for real datasets  
- Convergence check can be improved  

---

## 🚀 Future Improvements (High Impact)

### 1️⃣ Algorithm Improvements

- KMeans++ initialization  
- Vectorized distance computation  
- Improved convergence criteria  

---

### 2️⃣ Evaluation Framework

- Silhouette Score  
- Inertia analysis  
- Cluster validation  

---

### 3️⃣ System Upgrade

- Build clustering pipeline (`src/`)  
- Add model persistence (save/load centroids)  
- Compare with sklearn KMeans  

---

## 🎯 What This Project Demonstrates

- Strong understanding of clustering algorithms  
- Ability to implement ML algorithms from scratch  
- Experience with real-world datasets  
- Awareness of scalability and performance trade-offs  

---

## 📌 Key Takeaway

Clustering is not just an algorithm — it requires **careful feature selection, initialization strategy, and evaluation** to produce meaningful results.

---

## 👤 Author

**Rudra Tyagi**  
ML Systems | MLOps | AI Infrastructure  
