# 👋 Hi, I'm Melanie!
 
M.Sc. Electrical Engineering & Information Technology

I enjoy uncovering patterns in data, shaping them through feature engineering, and exploring how small algorithmic changes influence how models learn.

---

## 🚀 Projects
- **Automated Hyperparameter Optimization Framework (Master’s Thesis, implementation is not publicly available)**  
  Designed and implemented a modular hyperparameter optimization framework in Julia from scratch supporting:
  - Grid Search
  - Random Search
  - Hyperband
  - Bayesian Optimization
  - BOHB
  
  The framework supported configurable and nested hyperparameter search spaces as well as custom training loop integration, enabling flexible benchmarking across different neural network architectures and evaluation metrics. Used Flux.jl for training neural networks and evaluating different architectures as part of the optimization pipeline.
  
  Implemented checkpoint-based training continuation for Hyperband and BOHB to avoid redundant retraining during successive optimization rounds.
  
  Conducted reproducible large-scale experiments using 50 random seeds per optimization algorithm.
  
  Additionally developed a benchmarking suite for generating synthetic training datasets based on network topologies and demand allocation scenarios using a custom K-Shortest-Path First-Fit implementation.
  
  Hyperband achieved the best efficiency/performance tradeoff, requiring on average only 8% of the training epochs used by Grid Search while still reaching 99.6% of the best achievable performance within the defined search space.
  

- **Financial Phrase Sentiment Analysis**  
  Performed exploratory data analysis, preprocessing, and TF-IDF feature extraction on financial text data.

  Trained and evaluated:
  - Logistic Regression
  - Linear SVM
  - Naive Bayes
  for sentiment classification.

  Linear SVM achieved the best performance with an accuracy of 89.8% and a Macro-F1 score of 0.85.

---

## 🛠️ Tech Stack
Python, Julia
NumPy, Pandas, Scikit‑Learn  
PyTorch (deep learning, model training & evaluation)  
Flux.jl (neural network experimentation in thesis context)  
Git, Linux

EDA, Feature Engineering  
Model Training & Evaluation
Hyperparameter Optimization  
NLP (TF‑IDF, classical ML)  

---

## 🎯 Interests
Pattern Discovery  
Feature Engineering  
Hyperparameter Optimization   
Reproducible ML Workflows 