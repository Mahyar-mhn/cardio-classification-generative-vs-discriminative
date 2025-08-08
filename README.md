# Cardio Classification — Generative vs. Discriminative

Compare classic **generative** and **discriminative** models for cardiovascular disease prediction, end-to-end: data prep → modeling → evaluation → takeaway. Built to be a compact, reproducible notebook you can run locally or in Colab.

> Repo layout: `heart_disease_assignment.ipynb`, `data/`, `requirements.txt`.

---

## 📌 Why this project?

- Show, not tell: how assumptions differ between **generative** (e.g., Naive Bayes/QDA) and **discriminative** (e.g., Logistic Regression/SVM) approaches.
- Provide a minimal, well-documented baseline for heart-disease classification that students can extend.

---

## 📊 Dataset

- A tabular **cardio/heart-disease** dataset (loaded from `data/`).  
  > If you’re using a specific public dataset (UCI Heart Disease, Kaggle Cardio, etc.), add a link and brief variable glossary here.

---

## 🧠 Models

- **Generative**: Gaussian Naive Bayes (and optionally QDA/LDA)
- **Discriminative**: Logistic Regression, SVM (linear/RBF), and/or tree-based baselines

> If your notebook includes additional models (e.g., kNN, Random Forest), list them here.

---

## ⚙️ Features & Pipeline

- **Preprocessing**: missing values, scaling/standardization, train/validation/test split
- **Training**: scikit-learn pipelines for apples-to-apples comparison
- **Evaluation**: accuracy, precision/recall, F1, ROC-AUC, confusion matrix
- **Reporting**: side-by-side metrics and quick interpretation notes

---

