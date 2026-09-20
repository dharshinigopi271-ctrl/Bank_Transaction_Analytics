# 🏦 Bank Transaction Analytics and Anomaly Detection Using Machine Learning

## 📌 Project Overview

This project applies Machine Learning techniques to analyze bank transaction data and detect anomalous (unusual) transactions. It demonstrates a complete data analytics workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, feature scaling, anomaly detection using the Isolation Forest algorithm, and business insights.

The project is designed as an end-to-end Machine Learning project suitable for academic submission and portfolio demonstration.

---

## 🎯 Problem Statement

Financial institutions process thousands of transactions every day. Detecting unusual or suspicious transactions manually is difficult and time-consuming.

This project uses the Isolation Forest algorithm to automatically identify anomalous transactions that may require further investigation.

---

## 🎯 Objectives

- Analyze bank transaction data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Engineer meaningful features.
- Scale numerical features.
- Detect anomalous transactions using Isolation Forest.
- Generate business insights from transaction data.
- Save the trained machine learning model for future use.

---

## 📂 Project Structure

```
Bank_Transaction_Analytics/
│
├── Dataset/
│   ├── Original_Bank_Statement.xlsx
│   ├── Bank_Transaction_Analytics_Final.csv
│   └── Bank_Transaction_Analytics_Final.xlsx
│
├── Notebook/
│   └── Bank_Transaction_Analytics_and_Anomaly_Detection_ML.ipynb
│
├── Model/
│   ├── IsolationForest_BankTransaction_Model.pkl
│   └── StandardScaler.pkl
│
├── Graphs/
│
├── Reports/
│   ├── README.md
│   ├── Project_Report.docx
│   └── Project_Presentation.pptx
│
└──
```

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Machine Learning Algorithm

### Isolation Forest

Isolation Forest is an unsupervised anomaly detection algorithm that identifies unusual observations by isolating them using random decision trees.

Advantages:

- No labeled data required
- Fast and efficient
- Suitable for fraud detection
- Handles large datasets effectively

---

## 🔄 Project Workflow

```
Bank Transaction Dataset
        │
        ▼
Data Understanding
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Engineering
        │
        ▼
Feature Selection
        │
        ▼
Data Scaling
        │
        ▼
Isolation Forest Model
        │
        ▼
Anomaly Detection
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
```

---

## 📈 Exploratory Data Analysis

The project includes:

- Missing Value Analysis
- Duplicate Record Detection
- Transaction Type Distribution
- Monthly Transaction Analysis
- Withdrawal Analysis
- Deposit Analysis
- Balance Analysis
- Correlation Heatmap
- High-Value Transaction Analysis

---

## 🤖 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Clean Data
4. Feature Engineering
5. Feature Selection
6. StandardScaler
7. Train Isolation Forest
8. Predict Anomalies
9. Visualize Results
10. Save Model

---

## 📌 Features Created

- Transaction Amount
- Transaction Type
- Month
- Month Name
- Day
- Weekday
- Quarter
- High Value Transaction Flag
- Weekend Indicator
- Balance Difference
- Amount Category

---

## 📊 Results

The project successfully:

- Cleaned and prepared bank transaction data.
- Engineered useful financial features.
- Scaled numerical variables.
- Trained an Isolation Forest model.
- Detected anomalous transactions.
- Generated business insights using visualizations.
- Saved the trained model and scaler.

---

## 📁 Output Files

The project generates:

- Bank_Transaction_Analytics_Final.csv
- Bank_Transaction_Analytics_Final.xlsx
- IsolationForest_BankTransaction_Model.pkl
- StandardScaler.pkl

---

## 🚀 Future Scope

- Real-time anomaly detection
- Fraud risk scoring
- Deep Learning models
- Autoencoder-based anomaly detection
- Streamlit deployment
- Power BI dashboard integration
- API deployment using Flask or FastAPI

---

## 📚 References

- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Scikit-learn Documentation
- Isolation Forest Research Papers

---

## 👩‍💻 Author

**Dharshini G**

**PGA 38 **

**Data Science With Gen AI**
---

## ⭐ Acknowledgement

This project was developed as part of the M.Sc. Data Analytics curriculum to demonstrate practical applications of data analytics and machine learning techniques for financial transaction analysis and anomaly detection.