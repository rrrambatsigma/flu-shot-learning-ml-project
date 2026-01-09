
---

# Flu Shot Learning – Predict H1N1 & Seasonal Flu Vaccines

## 📌 Project Overview

This project aims to predict the probability that an individual received the **H1N1 vaccine** and the **seasonal flu vaccine** using survey-based public health data.
The project is part of a machine learning challenge from **DrivenData** and is intended as a portfolio project for Data Science practice.

The task is formulated as a **multi-label binary classification problem**, where two independent probabilities are predicted for each respondent.

---

## 🎯 Objectives

* Build machine learning models to estimate the probability of:

  * `h1n1_vaccine`
  * `seasonal_vaccine`
* Perform data preprocessing, feature encoding, and model evaluation.
* Evaluate performance using the **ROC AUC** metric.

---
---

## 🧠 Dataset Description

The dataset contains responses to health-related surveys including:

* Behavioral patterns (mask usage, hand washing, etc.)
* Opinions about flu risks and vaccine effectiveness
* Demographic information

**Important:**
The original dataset is **not included** in this repository due to licensing restrictions.
You must download it manually from DrivenData.

---

## ⬇️ Download Dataset

Download the dataset from:

> DrivenData – Flu Shot Learning Competition
> [https://www.drivendata.org/competitions/66/flu-shot-learning/](https://www.drivendata.org/competitions/66/flu-shot-learning/)

After downloading, place the files inside a local folder named `DATA/`.

---

## 🛠️ Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 🔁 Workflow

1. Data loading & exploration
2. Missing value handling
3. Categorical feature encoding
4. Train–validation split
5. Model training (Logistic Regression, Random Forest, etc.)
6. Model evaluation using ROC AUC
7. Probability prediction for submission format

---

## 📈 Evaluation Metric

Performance is evaluated using the **mean ROC AUC score** across both targets:

* `h1n1_vaccine`
* `seasonal_vaccine`

---

## ⚠️ Data Usage Notice

The dataset is governed by the DrivenData competition rules and **must not be redistributed**.
Only code, documentation, and visualizations are shared in this repository.

---

## 📚 Reference

DrivenData. (2020). *Flu Shot Learning: Predict H1N1 and Seasonal Flu Vaccines*.
Retrieved January 9, 2026, from
[https://www.drivendata.org/competitions/66/flu-shot-learning/](https://www.drivendata.org/competitions/66/flu-shot-learning/)

---

## 👤 Author

**Rambat Ungu Aryati**
Data Science Student – Universitas Sebelas Maret
Portfolio Project – 2026
