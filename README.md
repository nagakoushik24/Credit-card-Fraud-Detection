# 💳 Credit Card Fraud Detection using Decision Tree & Gaussian Naive Bayes

This repository presents a machine learning-based solution for **credit card fraud detection**, using two powerful classifiers:

- **Gaussian Naive Bayes**
- **Decision Tree Classifier**

It is a part of the coursework for **22AIE301 - Probabilistic Reasoning**.

---

## 📌 Project Objective

Fraud detection in credit card transactions is a major challenge due to:

- Highly **imbalanced datasets** (fraud cases are <0.2%)
- Evolving fraudulent behavior patterns
- Need for **real-time** and **accurate** detection systems

**Objective**:  
To compare the effectiveness of Gaussian Naive Bayes and Decision Tree classifiers in identifying fraudulent credit card transactions with high precision and recall.

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraudulent Cases**: 492 (0.172%)
- **Features**:  
  - `Time`, `Amount`, `Class` (0: Non-Fraud, 1: Fraud)  
  - `V1` to `V28` - PCA-transformed features for anonymity

---

## 🧠 Models Implemented

### 🔹 Gaussian Naive Bayes
- Assumes normal distribution of features
- Uses Bayes’ Theorem for probabilistic classification
- Simple and effective for large-scale problems

### 🔸 Decision Tree Classifier
- A supervised learning model for classification
- Uses metrics like **Entropy** and **Information Gain**
- Tree-pruning to avoid overfitting

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**
- **Macro Avg** and **Weighted Avg**

---

## 📂 Repository Structure

```bash
📦 CreditCard-Fraud-Detection
├── DecisionTree.ipynb           # Jupyter notebook for Decision Tree Classifier
├── GaussianNaiveBayes.ipynb     # Jupyter notebook for Gaussian Naive Bayes
├── PPT.pdf                      # Project presentation slides
└── README.md                    # Project overview and documentation
