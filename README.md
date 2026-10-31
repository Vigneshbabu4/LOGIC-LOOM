# 🔍 LOGIC LOOM – UPI Fraud Intelligence Dashboard

<p align="center">

  **AI-Powered UPI Fraud Detection, Analytics & Risk Intelligence**

  An interactive fraud intelligence platform designed to analyze UPI transactions, uncover suspicious patterns, evaluate machine learning models, and support data-driven financial risk decisions.

  [🚀 Live Dashboard](https://vigneshbabu4.github.io/LOGIC-LOOM/)

</p>

---

## 📌 Project Overview

**LOGIC LOOM** is an interactive UPI Fraud Intelligence Dashboard developed to analyze transaction behavior and identify potential fraudulent activities using data analytics and machine learning.

The platform explores a dataset containing **250,000 UPI transactions from January to December 2024**, including 480 fraud-labelled transactions.

It provides an integrated analytical workspace to understand transaction patterns, investigate fraud indicators, compare predictive models, and evaluate risk-based decisions.

The primary objective is to transform raw transaction data into meaningful insights that can help improve fraud monitoring and financial security.

## 🎯 Key Objectives

- Analyze large-scale UPI transaction data.
- Identify fraudulent transaction patterns and suspicious activities.
- Understand fraud distribution across time, amount, merchant categories, and transaction types.
- Investigate fraud patterns across banks, states, devices, and network types.
- Evaluate machine learning models using appropriate classification metrics.
- Translate fraud probabilities into actionable risk decisions.
- Support data-driven fraud investigation and financial risk management.

## ✨ Dashboard Features

### 1. Executive Overview
- Total transaction count.
- Fraud and genuine transaction distribution.
- Overall fraud percentage.
- Total transaction value.
- Monthly transaction activity.
- Fraud distribution by transaction type.
- Transaction status analysis.
- Key fraud indicators and portfolio-level insights.

### 2. Fraud Pattern Analysis
- Fraud distribution by hour of the day.
- Fraud analysis by transaction amount.
- Merchant category-based fraud analysis.
- Fraud rate comparison across transaction types.
- Amount-band fraud rate analysis.
- Day-of-week and hour-based fraud heatmap.
- Identification of unusual transaction patterns.

### 3. Transaction Intelligence
- Sender bank fraud analysis.
- Receiver bank fraud analysis.
- Device-type analysis.
- Network-type analysis.
- Sender age-group analysis.
- State-level transaction and fraud summaries.
- Fraud count and fraud rate comparisons.

### 4. Machine Learning Model Performance

Compare machine learning models trained using transaction data.

Models included:
- Logistic Regression
- Random Forest
- Gradient Boosting

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- PR-AUC

Additional visualizations:
- Model performance comparison.
- Precision-Recall curves.
- PR-AUC comparison.
- Expected cost versus classification threshold.

### 5. Risk Decisions

Convert predicted fraud probabilities into three actionable risk categories:

| Decision | Description |
|---|---|
| APPROVE | Low-risk transactions |
| STEP-UP OTP | Transactions requiring additional verification |
| BLOCK | High-risk transactions |

Includes decision distribution, fraud versus genuine analysis, and expected financial cost evaluation.

## 📊 Dataset Information

| Attribute | Details |
|---|---|
| Dataset | UPI Transactions 2024 |
| Total Records | 250,000 |
| Fraud Transactions | 480 |
| Genuine Transactions | 249,520 |
| Fraud Prevalence | 0.192% |
| Time Period | January – December 2024 |

**Important:** The dataset contains a highly imbalanced target variable. Therefore, accuracy alone is insufficient for evaluating fraud detection performance. Precision, recall, F1-score, PR-AUC, and financial cost are also considered.

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **UI Framework:** Bootstrap
- **Data Visualization:** JavaScript charting and analytical visualizations
- **Machine Learning:** Python, Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Model Evaluation:** Scikit-learn Metrics
- **Deployment:** GitHub Pages
- **Version Control:** Git and GitHub

## 📁 Project Structure

```text
LOGIC-LOOM/
│
├── index.html
├── README.md
│
├── dataset/
│   └── UPI_transactions.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── models/
│   └── model_comparison.csv
│
└── assets/
    ├── css/
    ├── js/
    └── images/
```

*The structure above represents the suggested organization; adjust filenames to match the actual repository.*

## 🚀 Live Demo

Explore the interactive dashboard:

**https://vigneshbabu4.github.io/LOGIC-LOOM/**

The dashboard includes an embedded dataset and supports uploading compatible CSV files for additional analysis.

### Supported CSV Inputs

- Transaction dataset
- `model_comparison.csv` – Machine learning model evaluation results.
- `risk_decisions.csv` – Risk classification and decision results.

## 🧠 Important Analytical Insight

Fraud detection is a rare-event classification problem.

For example, a model that predicts every transaction as genuine could achieve approximately **99.81% accuracy** on this dataset while detecting zero fraudulent transactions.

This demonstrates why a fraud detection system must prioritize the ability to identify fraudulent transactions rather than relying only on overall accuracy.

## ⚠️ Limitations & Considerations

- Fraud patterns represent observed associations, not proof of causation.
- Model performance depends on dataset quality and class distribution.
- Financial cost calculations use illustrative assumptions unless official values are supplied.
- Predictions should be validated before being used in real-world financial systems.
- The dashboard is an analytical and educational prototype, not a live banking fraud prevention system.

## 🔮 Future Enhancements

- Real-time UPI transaction monitoring.
- Advanced anomaly detection using Isolation Forest and other unsupervised algorithms.
- Deep learning-based fraud classification.
- Explainable AI using SHAP and feature importance.
- Real-time fraud alerts and notifications.
- Integration with secure financial data pipelines.
- Advanced user-level behavioral analysis.

## 👨‍💻 Developer

**Vignesh Guthi**

- Portfolio: https://gvignesh.in/
- GitHub: https://github.com/Vigneshbabu4
- LinkedIn: https://www.linkedin.com/in/guthi-vignesh-babu/

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub.

---

**LOGIC LOOM – Turning UPI Transaction Data into Fraud Intelligence.**
