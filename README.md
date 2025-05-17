# 🧪 Soft Computing for Molecular Classification

This repository presents a comparative study on the effectiveness of soft computing techniques — **Genetic Algorithm (GA)** and **Particle Swarm Optimization (PSO)** — in optimizing machine learning classifiers (**Random Forest** and **Support Vector Machine**) for high-dimensional molecular data.

## 📌 Project Title
**Enhancing Molecular Classification Using Soft Computing Algorithms: A Comparative Study of RF and SVM with GA and PSO**



## 📁 Dataset

- **Name:** Musk Version 2  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/75/musk+version+2)  
- **Instances:** 6598  
- **Features:** 168 molecular descriptors  
- **Task:** Binary classification (Musk vs Non-Musk)



## 🎯 Objectives

- Apply feature selection using GA and PSO to reduce dimensionality.
- Compare the classification performance of RF and SVM before and after optimization.
- Analyze model performance using comprehensive evaluation metrics.


## 🛠️ Tools & Libraries

- Python 3.x  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn  
- DEAP (for GA), Pyswarms (for PSO)



## 🧬 Methodology

### Models Used
- Random Forest (RF)
- Support Vector Machine (SVM)

### Optimization Techniques
- **Genetic Algorithm (GA)**
- **Particle Swarm Optimization (PSO)**

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report


## 📊 Results Summary

| Model              | Accuracy | Precision | Recall | F1-score |
|--------------------|----------|-----------|--------|----------|
| RF - All Features  | 94%      | 0.93      | 0.94   | 0.94     |
| RF - GA Optimized  | 96%      | 0.95      | 0.96   | 0.96     |
| RF - PSO Optimized | 95%      | 0.94      | 0.95   | 0.95     |
| SVM - All Features | 94%      | 0.93      | 0.94   | 0.94     |
| SVM - GA Optimized | 96.15%   | 0.95      | 0.96   | 0.96     |
| SVM - PSO Optimized| 92.44%   | 0.89      | 0.94   | 0.92     |
