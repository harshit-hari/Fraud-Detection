Fraud Detection Using Hybrid Machine Learning Approach

## 📌 Project Overview

This project focuses on detecting fraudulent financial transactions using a Hybrid Machine Learning Model. Fraud detection is an important challenge in banking, e-commerce, and digital payment systems due to increasing online transaction volume.

The proposed system combines traditional Machine Learning algorithms with Deep Learning techniques to improve fraud detection accuracy and reduce false predictions.

## 🎯 Objective

The main objective of this project is to build an intelligent fraud detection system that can identify suspicious transactions in real-time using transaction behavior patterns such as amount, balance changes, transaction type, and account activity.

This project also aims to:

- Detect fraudulent transactions accurately  
- Handle imbalanced datasets using SMOTE  
- Compare multiple machine learning models  
- Improve performance using Hybrid Autoencoder + XGBoost model  
- Reduce financial losses and increase security  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  
- TensorFlow / Keras  
- Google Colab / Jupyter Notebook  

---

## 📂 Dataset Features

The dataset contains transaction-related features such as:

- step  
- type  
- amount  
- nameOrig  
- oldbalanceOrg  
- newbalanceOrig  
- nameDest  
- oldbalanceDest  
- newbalanceDest  
- isFraud  
- isFlaggedFraud  

### Engineered Features:

- balanceDiffOriginal  
- balanceDiffDest  

---

## 🤖 Models Implemented

1. Logistic Regression  
2. Random Forest  
3. XGBoost  
4. Hybrid Autoencoder + XGBoost  

---

## 🔥 Hybrid Model Approach

The proposed hybrid model works in two stages:

### Stage 1: Autoencoder

- Learns normal transaction behavior  
- Detects anomalies in transactions  

### Stage 2: XGBoost

- Uses extracted features from Autoencoder  
- Performs final fraud classification  

This combination improves fraud detection performance.

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC AUC Score  
- Confusion Matrix  

---

## 📈 Expected Results

The Hybrid Autoencoder + XGBoost model gives better fraud detection performance compared to traditional models.

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow imbalanced-learnraud-Detection
