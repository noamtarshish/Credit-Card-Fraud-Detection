# 💳 Credit Card Fraud Detection using Predictive Models

This project investigates the detection of fraudulent credit card transactions using multiple machine learning models. It addresses challenges related to imbalanced data, real-world transaction behavior, and model performance trade-offs.
---

## 📌 Project Overview

- **Goal:** Detect fraudulent transactions using machine learning  
- **Dataset:** Simulated transaction dataset from Kaggle (2019–2020)  
- **Team Members:**  Noam Tarshish, Kathy Agafonov, Niv Sampson, Mor Barzilay  
- **Techniques Used:**  
  - Feature engineering (log-transformed amount, distance features, temporal patterns)  
  - Downsampling for class balance  
  - ML Models: Random Forest, XGBoost, ANN, and an Ensemble model

---

## 🔍 Notebooks & Report

- 📓 `Credit Card Fraud Detection Predictive Models.ipynb`:  
  Includes the full pipeline: data loading, cleaning, feature engineering, model training & evaluation.

- 📄 `Credit Card Fraud Detection Predictive Models - Latex.pdf`:  
  Formal academic report with detailed explanations, results, evaluation metrics, and future directions.

---

## 🧠 Models Implemented

| Model            | Accuracy | Precision | Recall | F1-Score | Training Time |
|------------------|----------|-----------|--------|----------|----------------|
| Random Forest    | 97.0%    | 0.98      | 0.96   | 0.97     | 5 sec          |
| XGBoost          | 98.0%    | 0.98      | 0.98   | 0.98     | 1 sec          |
| ANN              | 96.0%    | 0.95      | 0.96   | 0.96     | 43 sec         |
| Ensemble Model   | 98.0%    | 0.98      | 0.98   | 0.98     | -              |

> 📈 XGBoost and Ensemble models demonstrated the best overall performance.

---

## 🧩 Key Features Engineered

- **Temporal patterns**: Hour, day, month of transaction  
- **Distance-based**: Between transaction and home location  
- **Velocity-based**: Number of recent transactions per card  
- **Category encoding**: One-hot encoding of merchant types  
- **Log-transformed amounts**: Reduced skewness in monetary values

---

## 📈 Visual Analysis

The notebook and report include:  
- 📊 Time series of fraud activity  
- 🗺️ Geographical heatmaps  
- 📉 ROC and Precision-Recall curves  
- 💡 Insights from anomaly patterns

---

## 🚀 Future Work

- Real-time fraud detection mechanisms  
- Graph-based detection and user/merchant network analysis  
- Explainability via SHAP/LIME  
- Larger-scale deployment and streaming model evaluation
