# 💳 Credit Card Fraud Detection using XGBoost

This project uses the powerful XGBoost machine learning algorithm to detect fraudulent transactions in credit card data. The model is trained and evaluated using the popular Kaggle Credit Card Fraud Detection dataset.

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions
- **Features**: 30 (V1 to V28, Time, Amount)
- **Target**: `Class` (0 = legitimate, 1 = fraud)

> The dataset is highly imbalanced, with frauds accounting for only 0.17% of transactions.

---

## 🔧 Tech Stack

- **Python**
- **XGBoost**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** for preprocessing and evaluation

---

## 🚀 Workflow

1. **Data Loading**: Load and explore the dataset
2. **Preprocessing**:
   - Feature scaling (`StandardScaler`)
   - Train-test split
3. **Model Training**:
   - XGBoost Classifier
   - Hyperparameters tuned for better performance
4. **Evaluation**:
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC Curve

---
