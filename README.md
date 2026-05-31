# 🛡️ FraudShield – Credit Card Fraud Detection System

## 📌 Overview

FraudShield is an AI-powered Credit Card Fraud Detection System developed using Machine Learning and Data Science techniques. The project identifies potentially fraudulent credit card transactions in real time and provides an interactive dashboard for transaction analysis and batch prediction.

The system was trained on an imbalanced credit card transaction dataset and utilizes advanced preprocessing techniques, including feature scaling and SMOTE oversampling, to improve fraud detection performance.

---

## 🚀 Features

* Real-time fraud prediction
* Batch transaction analysis via CSV upload
* Interactive Streamlit dashboard
* Fraud probability estimation
* Data visualization and analytics
* Model comparison and evaluation
* Random Forest-based fraud detection pipeline

---

## 🛠️ Tech Stack

### Data Science & Machine Learning

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* XGBoost

### Visualization

* Plotly
* Matplotlib
* Seaborn

### Deployment & Application

* Streamlit
* GitHub

---

## 📂 Project Structure

```text
credit_card_fraud_detection_model/
│
├── app/
│   └── streamlit_app.py
│
├── data/
│   └── raw/
│
├── models/
│   ├── fraud_detection_rf.pkl
│   └── scaler.pkl
│
├── notebooks/
│   ├── eda.ipynb
│   └── model_training.ipynb
│
├── source/
│   ├── preprocessing.py
│   ├── train.py
│   ├── predict.py
│   └── evaluate.py
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses the publicly available Credit Card Fraud Detection dataset containing anonymized transaction features (V1–V28), transaction time, amount, and class labels.

* Class 0 → Legitimate Transaction
* Class 1 → Fraudulent Transaction

---

## 🤖 Models Evaluated

| Model               | Precision | Recall | ROC-AUC |
| ------------------- | --------- | ------ | ------- |
| Logistic Regression | 0.06      | 0.92   | 0.97    |
| Random Forest       | 0.87      | 0.83   | 0.96    |
| XGBoost             | 0.73      | 0.85   | 0.97    |

### Selected Model

✅ Random Forest Classifier

Reason:

* High precision
* Strong recall
* Low false-positive rate
* Reliable fraud detection performance

---

## 📈 Model Performance

* Accuracy: 97.41%
* Precision: 87%
* Recall: 83%
* ROC-AUC: 96%
* Fraud Detection Rate: 91.84%

---

## 🌐 Live Demo

FraudShield Dashboard:

https://fraudshield-007.streamlit.app/

---

## 🔮 Future Improvements

* REST API integration using FastAPI
* Real-time transaction monitoring
* Model retraining pipeline
* Advanced explainability with SHAP
* Cloud deployment and monitoring

---

## 👨‍💻 Authors

Pranav Sahu
Data Science & Machine Learning Enthusiast

Contributors:

* Muskan
* Pranav Sahu
