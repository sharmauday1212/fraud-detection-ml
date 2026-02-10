# 🚨 Fraud Detection Analysis & Risk Interpretation

## 📌 Project Overview
Financial fraud causes significant losses to organizations every year.  
This project focuses on detecting **fraudulent credit card transactions** using **machine learning techniques**, with special emphasis on **imbalanced data handling** and **risk interpretation**.

The model is designed to **minimize missed fraud cases (False Negatives)**, which represent high financial risk.

---

## 🎯 Objectives
- Analyze transaction behavior to identify fraud patterns  
- Handle highly imbalanced fraud data effectively  
- Build and compare machine learning models for fraud detection  
- Interpret results from a **risk management perspective**

---

## 📂 Dataset
**Credit Card Fraud Detection Dataset (Kaggle)**  
- Anonymized transaction features  
- Highly imbalanced (fraud cases are very rare)  
- Binary target variable:  
  - `0` → Normal transaction  
  - `1` → Fraudulent transaction  

🔗 Dataset Source:  
https://www.kaggle.com/mlg-ulb/creditcardfraud

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- SMOTE (Imbalanced-learn)

---

## ⚙️ Methodology
1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling (StandardScaler)  
4. Handling class imbalance using **SMOTE**  
5. Model training:
   - Logistic Regression  
   - Random Forest Classifier  
6. Model evaluation using:
   - Confusion Matrix  
   - Classification Report  
   - ROC Curve & ROC-AUC Score  
7. Fraud risk interpretation  

---

## 🔁 Fraud Detection Pipeline
Start
→ Load Transaction Data
→ Exploratory Data Analysis
→ Feature Scaling
→ Handle Imbalanced Data (SMOTE)
→ Train ML Models
→ Evaluate (Confusion Matrix & ROC Curve)
→ Flag High-Risk Transactions
→ End


---

## 📊 Experimental Results
- **Fraud vs Normal Transaction Distribution**
- **Fraud Transaction Amount Distribution**
- **ROC Curve (Random Forest)**

📄 Detailed results with real screenshots are available in the project report.

---

## 📄 Project Report (NAAC / Award Level)
👉 **Fraud_Detection_FINAL_NAAC_With_Results_Uday_Sharma.pdf**

This report includes:
- Academic formatting  
- Real output screenshots  
- Risk interpretation  
- Future scope & limitations  

---

## ⚠️ Model Evaluation & Risk Interpretation
- Accuracy is **not suitable** for fraud detection due to class imbalance  
- **Confusion Matrix** and **ROC-AUC** are used instead  
- **False Negatives (missed frauds)** pose the highest financial risk  
- The model prioritizes **fraud recall** to ensure suspicious transactions are flagged for investigation  

---

## 🚀 Future Scope
- Real-time fraud detection systems  
- Deep learning models (LSTM for sequential transaction data)  
- Cloud-based deployment for live risk monitoring  

---

## 👤 Author
**Uday Sharma**  
BCA (Data Science)  
Aspiring Data Scientist  



