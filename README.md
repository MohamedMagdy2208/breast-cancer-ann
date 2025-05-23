# 🧠 Breast Cancer Detection with Artificial Neural Network (ANN)

This project uses an Artificial Neural Network (ANN) built in TensorFlow to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

---

## 📌 Project Overview

- **Goal**: Predict whether a tumor is benign or malignant.
- **Approach**: Data preprocessing, ANN training, evaluation, and visualization.
- **Frameworks**: TensorFlow, Keras, Pandas, Matplotlib, Seaborn.

---

## 📊 Dataset

- **Source**: [Kaggle – Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- 569 instances with 30 numeric features and 1 target variable (`diagnosis`).

---

## 🏗️ Model Summary

- ANN built with:
  - Input layer for 30 features
  - Three hidden layers with ReLU
  - Dropout layers for regularization
  - Output layer with sigmoid activation
- **Loss**: Binary Crossentropy  
- **Optimizer**: Adam  
- **Evaluation Metric**: Accuracy

---

## 🧪 Results

<p align="center">
  <img src="images/accuracy_loss_plot.png" alt="Accuracy and Loss Plot" width="600">
</p>

- **Validation Accuracy**: ~97%
- Balanced performance across classes
- Good generalization with minimal overfitting

---

## 🚀 Getting Started

### Clone the repository:
```bash
git clone https://github.com/MohamedMagdy2208/breast-cancer-ann.git
cd breast-cancer-ann
