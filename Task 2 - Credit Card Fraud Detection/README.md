# 💳 Credit Card Fraud Detection

This project is part of my internship at **CODSOFT**. It focuses on detecting fraudulent credit card transactions using machine learning models. The solution is built using a real-world anonymized dataset and demonstrates proper handling of imbalanced classes and feature engineering techniques.

---

## 📌 Objective

To build a supervised machine learning model that can accurately classify credit card transactions as **fraudulent** or **legitimate** based on transaction patterns and user behavior.

---

## 🧠 Algorithms Used

- ✅ Logistic Regression (Balanced)
- ✅ Decision Tree Classifier (Balanced)
- 📉 Evaluation using Accuracy, Precision, Recall, F1-score
- 📊 Confusion Matrix and Feature Importance Visualizations

---

## 🛠️ Technologies & Libraries

- **Python** (Google Colab)
- **Pandas** & **NumPy** – Data handling
- **Scikit-learn** – ML models and metrics
- **Matplotlib** & **Seaborn** – Data visualization

---

## 📊 Dataset Info

- Source: Provided via Google Drive
- Files used:
  - `fraudTrain.csv` – Training data  
  - `fraudTest.csv` – Testing data
- Features include:
  - `amt`, `gender`, `category`, `lat`, `long`, and more
- Highly **imbalanced dataset**:
  - Class 0: Non-Fraud  
  - Class 1: Fraud

---

## 🧹 Preprocessing Steps

- Dropped high-cardinality and identity-leak columns (`cc_num`, `name`, `merchant`, `dob`, etc.)
- One-Hot Encoding applied to:
  - `category`
  - `gender`
- Feature scaling using `StandardScaler`
- Combined training and test data for consistent preprocessing

---

## ✅ Model Training & Evaluation

Two models were trained:

### 🔹 Logistic Regression
- Handles class imbalance with `class_weight='balanced'`
- Suitable for high-dimensional sparse features

### 🔸 Decision Tree Classifier
- Interpretable model with feature importance extraction
- Also balanced using class weights

### 🔍 Evaluation Metrics Used

- **Accuracy**
- **Precision / Recall / F1-score**
- **Confusion Matrix (Visualized)**
- **Top Feature Importance (Decision Tree)**

---

## 📈 Visualizations

- 🔥 Confusion Matrix heatmaps for each model  
- 🎯 Top 15 Feature Importances from Decision Tree


---

## ▶️ How to Run

1. Upload the dataset to Google Drive (`/MyDrive/credit_card_fraud/`)
2. Mount Google Drive in your Colab notebook
3. Run each cell step-by-step in `credit_card_fraud_detection.ipynb`
4. Outputs will include model reports and charts

---

## 📬 Contact

**Arnab Chakrobarty**  
📧 Email: arnab.bca04@gmail.com  
🔗 LinkedIn: [Arnab Chakrobarty](https://www.linkedin.com/in/arnab-chakrobarty/)

---

## 📌 Folder Structure (Recommended)

