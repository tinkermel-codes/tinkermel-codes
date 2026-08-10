# Hi, I'm Melanie!

**M.Sc. Electrical Engineering & Information Technology**

I enjoy finding patterns in messy and complex data and exploring how algorithms learn from data.

## Projects

### HPOFramework.jl(https://github.com/tinkermel-codes/HPOFramework)

**Hyperparameter Optimization Framework | Julia | Flux.jl**

As part of my Master's thesis, I developed a modular hyperparameter optimization framework in Julia from scratch supporting:

* Grid Search
* Random Search
* Hyperband
* Bayesian Optimization
* BOHB

The main goal was to make different optimization strategies comparable while keeping the model, training procedure, and data pipeline independent of the optimizer.

Some of the main parts I worked on:

* Hierarchical and configurable hyperparameter search spaces
* A Julia-native architecture using multiple dispatch
* User-defined model construction and training functions
* Checkpoint-based continued training for Hyperband and BOHB
* Experiment history and result tracking
* Reproducible optimization using configurable random seeds

For the thesis experiments, I ran each optimization algorithm with **50 random seeds**. Hyperband achieved the best efficiency/performance tradeoff, using on average only **8% of the training epochs used by Grid Search** while reaching **99.6% of the best achievable performance** within the defined search space. The original thesis datasets cannot be published.

### Financial Phrase Sentiment Analysis(https://github.com/tinkermel-codes/financial-phrase-sentiment-analysis)

**Python | Scikit-Learn | NLP**

Built a classical machine learning pipeline for sentiment classification using financial text data.

The project included:

* Exploratory data analysis
* Text preprocessing
* TF-IDF feature extraction
* Model training and evaluation

I compared Logistic Regression, Linear SVM, and Naive Bayes. Linear SVM achieved the best result with an **accuracy of 89.8%** and a **Macro-F1 score of 0.85**.

## Skills
**Programming:**
Python (Pandas, NumPy, Scikit-Learn, PyTorch, Seaborn), PySpark, SQL (PostgreSQL), Julia (Flux.jl)

**Tools:**
Git, Linux, VS Code, Docker, Jupyter, Pluto

**Data Analysis**:
Exploratory and statistical data analysis, Data cleaning, Feature engineering, Data visualization

**Machine Learning**:
Classification, Regression, Clustering, Model validation, Neural networks, Hyperparameter optimization