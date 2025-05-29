# Thyroid_prediction
# Thyroid Disease Prediction using Ensemble Machine Learning

Welcome to our Mini Project repository! This project presents an ensemble machine learning approach to predict thyroid disease with high accuracy using hybrid feature selection techniques. Developed as part of the **INT300 – Mini Project** at **SASTRA Deemed to be University**, this solution is aimed at improving early diagnosis of thyroid-related disorders through data-driven methods.

---

# Contributors

- **Leena Sree S** – Reg. No: 126015050  
- **Vsha Gopika Pa** – Reg. No: 126015123  
- **Yazhini R** – Reg. No: 126015124  

Department of Information Technology, School of Computing  
SASTRA Deemed to be University, Tamil Nadu, India  

---

# Repository Contents

- `Final code.ipynb` – Jupyter Notebook with complete implementation.
- `MiniProject-Report.pdf` – Detailed academic report.

---

# Project Overview

# Objective

Thyroid dysfunction is often underdiagnosed due to its broad symptom spectrum. This project builds a reliable machine learning model to aid in the early diagnosis of thyroid disease.

# Methodology

- **Hybrid Feature Selection**: Combines `XGBoost` and `SelectKBest`.
- **Data Balancing**: Applies `SMOTE-Tomek` to address class imbalance.
- **Models Used**:
  - Random Forest
  - Decision Tree
  - Gradient Boosting
  - K-Nearest Neighbors
  - Multi-Layer Perceptron
- **Ensemble Learning**: Hard and Soft Voting Classifiers improve overall accuracy.
- **Hyperparameter Tuning**: Performed using `GridSearchCV`.

---

# Results

- **Accuracy (Hard Voting – RF + DT)**: 99.71%
- **Sensitivity**: 100%
- Strong performance across key metrics such as ROC AUC, precision, recall, and F1-score.
- Comprehensive visualizations including confusion matrices, ROC curves, and model comparisons.

---

# Setup & Usage

# Requirements

To get started, ensure you have Python 3.7 or later installed on your system. The following Python libraries are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `imbalanced-learn`

You can install all the dependencies using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
