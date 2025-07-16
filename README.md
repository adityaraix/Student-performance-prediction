# 🎓 Student Performance Prediction

This repository contains a Jupyter Notebook that predicts student performance using machine learning techniques.  
The project explores how different features impact model accuracy and visualizes the results through various plots.

## 📦 Files

- `student_pred.ipynb` — Main notebook for data preprocessing, model training, and evaluation.
- `accuracy.png` — Accuracy visualization of the trained model.
- `confusion_matrix.png` — Confusion matrix showing model predictions vs actual classes.
- `feature_importance.png` — Feature importance plot to see which features influence predictions most.

## 🧠 Project Overview

The goal is to predict students' final grades or pass/fail status based on factors like study time, past failures, absences, etc.

Key steps:
- Load and clean the dataset.
- Split data into training and testing sets.
- Train machine learning models (e.g., Random Forest).
- Evaluate model accuracy and visualize performance.

## 📊 Visualizations

### ✅ Model Accuracy
![Model Accuracy](accuracy.png)

This plot shows how accurately the trained model predicts student performance on the test set.

---

### 🧩 Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

The confusion matrix illustrates the number of correct and incorrect predictions, helping identify where the model performs well and where it misclassifies.

---

### ⭐ Feature Importance
![Feature Importance](feature_importance.png)

This chart ranks the input features by their importance to the model’s predictions, helping understand what factors most strongly influence student outcomes.

## ⚙️ Requirements

Install required Python packages:

```bash
pip install -r requirements.txt
