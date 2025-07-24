# Heart Disease Prediction (ML Project)

Heart disease is the leading cause of death in the U.S. According to the AHA (2019):

* 46% of U.S. adults have hypertension
* One death every 38 seconds from CVD
* One death every 3.7 minutes from stroke

---

## Project Overview

This project uses a heart disease dataset to build a Soft Voting Ensemble model combining top-performing machine learning algorithms.

**Key steps:**

1. Data Exploration & Preprocessing
2. Outlier Removal
3. Feature Selection
4. Model Building & Comparison
5. Final Evaluation

---

## Dataset Features

* 11 features (6 nominal, 5 numeric)
* Target: `1` = heart disease, `0` = normal

Example features:

* age, sex, chest pain type, resting bp, cholesterol, fasting blood sugar, ECG results, max heart rate, oldpeak, ST slope

---

## Requirements

Install with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

Or use Anaconda for a pre-configured environment.

---

## Running the Project

Navigate to the project directory and run:

```bash
jupyter notebook heart-disease-classification.ipynb
```

---

## Model Evaluation

Evaluation metrics used:

* Cross Validation Score
* Confusion Matrix
* ROC-AUC Curve
* Precision-Recall Curve
* Sensitivity & Specificity
* Log Loss
* Matthews Correlation Coefficient
