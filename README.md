# 🫀 Heart Disease Prediction (ML Project)

Heart disease is the **leading cause of death** in the U.S. According to the AHA (2019):

* **46%** of U.S. adults have hypertension
* **One death every 38 seconds** from CVD
* **One death every 3.7 minutes** from stroke

---

## 📌 Project Overview

This project uses a heart disease dataset to build a **Soft Voting Ensemble model** combining top machine learning algorithms. Key steps include:

1. Data Exploration & Preprocessing
2. Outlier Removal
3. Feature Selection
4. Model Building & Comparison
5. Final Evaluation

---

## 🗂️ Dataset Features

* **11 features** (6 nominal, 5 numeric)
* **Target:** `1` = heart disease, `0` = normal

Examples:

* `age`, `sex`, `chest pain`, `bp`, `cholesterol`, `ecg`, `max heart rate`, `oldpeak`, `ST slope`, etc.

---

## 💻 Requirements

Install with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

Or use **Anaconda** for all-in-one setup.

---

## ▶️ Run the Project

```bash
jupyter notebook heart-disease-classification.ipynb
```

---

## 📊 Evaluation Metrics

* Cross Validation Score
* Confusion Matrix
* ROC-AUC & PR Curves
* Sensitivity, Specificity
* Log Loss, MCC


