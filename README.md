# 💳 Financial Fraud Detection – Exploratory Data Analysis

> A comprehensive exploratory analysis of synthetic financial transaction data to uncover fraud patterns, behavioral anomalies, and high-risk indicators.

---

## 📌 Executive Summary

Financial fraud remains a major challenge in digital transactions. This project performs an in-depth Exploratory Data Analysis (EDA) on a synthetic financial fraud dataset to identify trends, risk factors, and feature relationships that can inform fraud detection systems.

The analysis combines statistical profiling, feature engineering, and both static and interactive visualizations to generate actionable insights that can support machine learning model development.

---

## 🎯 Project Objectives

* Understand transaction distribution and behavioral patterns
* Identify characteristics associated with fraudulent transactions
* Analyze correlations between features
* Prepare categorical features for modeling
* Detect anomalies in transaction amounts, timing, and geography
* Lay groundwork for predictive fraud detection models

---

## 🗂 Dataset Overview

The dataset simulates real-world financial transactions and includes:

* Transaction details
* User identifiers
* Transaction amount
* Transaction type
* Merchant category
* Country
* Transaction hour
* Fraud indicator (`is_fraud`)

The dataset reflects structured fraud patterns embedded within legitimate activity.

---

## 🛠 Tech Stack

* **Python**
* **pandas & numpy** – Data processing
* **matplotlib & seaborn** – Statistical visualization
* **plotly.express** – Interactive dashboards
* **scikit-learn** – Feature encoding

---

## 🔎 Analysis Workflow

### 1️⃣ Data Preparation

* Imported necessary libraries
* Loaded dataset
* Inspected structure, data types, and summary statistics
* Checked for missing values

### 2️⃣ Feature Engineering

* Encoded categorical variables:

  * `transaction_type`
  * `merchant_category`
  * `country`
* Prepared dataset for correlation and modeling readiness

### 3️⃣ Exploratory Analysis

#### 📊 Descriptive Statistics

* Distribution of transaction amounts
* Fraud vs non-fraud comparison
* Transaction timing analysis

#### 🔗 Correlation Analysis

* Interactive correlation heatmap
* Identification of strongly related variables

#### 📈 Fraud Pattern Insights

* Transaction amounts by merchant category
* Fraud activity by hour of day
* Country-level fraud distribution
* Boxplot comparison of fraudulent vs legitimate amounts

---

## 🔍 Key Insights

* Fraudulent transactions show distinct amount distributions
* Certain merchant categories exhibit higher fraud exposure
* Time-of-day patterns indicate risk concentration
* Correlation analysis highlights predictive feature potential

---

## 📊 Sample Visualizations

* Pairwise feature relationships colored by fraud status
* Interactive correlation heatmap
* Merchant category vs transaction amount comparisons
* Fraud distribution by country and hour

---

## 🚀 Business Value

This analysis provides:

* Foundational insights for fraud detection systems
* Feature-level understanding for machine learning modeling
* Risk segmentation insights
* Data-driven approach to anomaly detection

---

## 🏗 Future Enhancements

* Train classification models (Logistic Regression, Random Forest, XGBoost)
* Implement anomaly detection techniques
* Feature importance analysis
* Model explainability with SHAP
* Deployment as an interactive fraud monitoring dashboard

---

## ⚙️ Installation & Usage

```bash
# Clone repository
git clone https://github.com/JamesMungai254/Financial-Fraud-Analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn

# Run the notebook
```

Ensure the dataset file is placed in the project directory before execution.

---

## 📁 Project Structure
Download [synthetic_fraud_dataset.csv](https://www.kaggle.com/datasets/ealaxi/paysim1)

```
├── synthetic_fraud_dataset.csv
├── fraud_eda_notebook.ipynb
└── README.md
```

---

## 👨‍💻 About This Project

This project demonstrates:

* Strong data exploration skills
* Analytical thinking in fraud detection
* Effective visualization techniques
* Clean feature engineering practices
* Structured analytical workflow

It is designed to showcase practical data science capabilities applicable to fintech, banking, risk analytics, and fraud detection domains.


