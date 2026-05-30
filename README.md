# PracticalStatistics_forDataScientists

# 📊 Practical Statistics for Data Scientists

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive, code-driven companion to the book ***Practical Statistics for Data Scientists (2nd Edition)*** by Peter Bruce, Andrew Bruce, and Peter Gedeck. 

This repository bridges the gap between classical statistical theory and modern machine learning practice by providing highly detailed, reproducible, and interactive Jupyter Notebooks for every major concept in the book.

---

## 📖 About This Repository

While many data science resources focus purely on machine learning algorithms or coding syntax, they often gloss over the foundational statistical mechanics that make those algorithms work. 

This repository serves as a **practical translation** of statistical concepts into actionable Python code. Instead of relying on external, hard-to-find CSV files, **every notebook in this repository generates its own highly realistic synthetic datasets**. This guarantees that the code is 100% reproducible on any machine, at any time, with zero configuration.

### What's Inside?
- **Detailed Markdown Explanations:** Deep dives into the "Why" and "How" of statistics, contrasting the perspectives of traditional statisticians and modern data scientists.
- **Reproducible Python Code:** Extensive use of `pandas`, `numpy`, `scipy`, `statsmodels`, and `scikit-learn`.
- **Vanilla JSON Architecture:** The notebooks are built with a clean JSON structure, ensuring maximum compatibility across JupyterLab, VS Code, and Google Colab environments.

---

## 📂 Table of Contents

| Chapter | Topic | Description | Link |
| :--- | :--- | :--- | :--- |
| **Chapter 1** | Exploratory Data Analysis | Central tendency, dispersion, percentiles, correlation, and multivariate distributions. | [View Notebook](./Chapter_1_Exploratory_Data_Analysis.ipynb) |
| **Chapter 2** | Data & Sampling Distributions | The Central Limit Theorem, the Bootstrap method, and theoretical probability distributions (Normal, Binomial, Poisson). | [View Notebook](./Chapter_2_Data_and_Sampling_Distributions.ipynb) |
| **Chapter 3** | Statistical Experiments | A/B Testing, Permutation Tests, p-values, ANOVA, Chi-Square, and Power Analysis. | [View Notebook](./Chapter_3_Statistical_Experiments.ipynb) |
| **Chapter 4** | Regression & Prediction | Simple/Multiple Linear Regression, dummy variable traps, multicollinearity, and regression diagnostics. | [View Notebook](./Chapter_4_Regression_and_Prediction.ipynb) |
| **Chapter 5** | Classification | Naive Bayes, Linear Discriminant Analysis (LDA), Logistic Regression, Confusion Matrices, AUC/ROC, and handling imbalanced data (SMOTE). | [View Notebook](./Chapter_5_Classification.ipynb) |
| **Chapter 6** | Statistical Machine Learning | K-Nearest Neighbors (KNN), Decision Trees, Random Forests, and Gradient Boosting algorithms. | [View Notebook](./Chapter_6_Statistical_MachineLearning.ipynb) |
| **Chapter 7** | Unsupervised Learning | Principal Component Analysis (PCA), K-Means Clustering, Hierarchical Clustering, and Gaussian Mixture Models (GMM). | [View Notebook](./Chapter_7_UnsupervisedLearning.ipynb) |

---

## 🚀 Getting Started

### Prerequisites
To run these notebooks locally, you will need Python 3.8+ and the following core libraries:

```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn
