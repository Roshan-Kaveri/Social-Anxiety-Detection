# Social Anxiety Detection System

## Description

This project implements a **machine learning–based Social Anxiety Disorder (SAD) detection system** using clinical, emotional, and physical symptom data. The goal is to predict whether an individual has Social Anxiety Disorder based on questionnaire and symptom-level features.

The project is developed for **academic and research purposes**.

---

## Tech Stack

* Python
* Scikit-learn
* Pandas, NumPy
* Matplotlib, Seaborn
* TensorFlow / Keras (Neural Network)

---

## Dataset

* Dataset contains **demographic, emotional, and physical symptoms**
* Target column: `hasSAD` (0 = No, 1 = Yes)
* Features are normalized using Min-Max scaling

---

## Models Used

* Random Forest (with hyperparameter tuning)
* Logistic Regression
* Decision Tree
* K-Nearest Neighbors (KNN)
* Stacking Ensemble Model
* Neural Network (Dense layers)

---

## Methodology

* Data preprocessing and normalization
* Feature selection (Top 15 features)
* Model training with cross-validation
* Performance evaluation using standard metrics

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* AUC-ROC
* Confusion Matrix

---
