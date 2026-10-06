# 🏦 Loan Approval Prediction & Analysis

### Machine Learning + Power BI | Finance & Banking

A complete data science project that predicts **loan approval outcomes using Machine Learning** and analyzes applicant and loan data through an **interactive Power BI dashboard**.

---

## 📌 Project Overview

Loan approval decisions depend on multiple factors such as income, credit history, education, employment status, loan amount, and property area.

This project uses historical loan application data to:

- 🔍 Explore and clean loan application data
- 🤖 Build Machine Learning classification models
- 📊 Compare Logistic Regression and KNN
- 🎯 Predict loan approval for new applicants
- 📈 Analyze loan trends using Power BI
- 💡 Extract meaningful business insights from the data

**Domain:** Finance / Banking  
**Project Type:** Supervised Machine Learning — Binary Classification

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Data processing & Machine Learning |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical operations |
| 🤖 Scikit-learn | Machine Learning |
| 📊 Matplotlib | Data visualization |
| 📈 Seaborn | Statistical visualization |
| 📓 Jupyter Notebook | Model development |
| ⚡ Power BI | Interactive dashboard |
| 🔄 Power Query | Data transformation |
| 📐 DAX | Dashboard calculations |

---

## 📂 Dataset

The project uses the **Kaggle Loan Prediction dataset**.

### Dataset Information

- **614** loan application records
- **13** original columns
- Target variable: `loan_status`

### Target Variable

| Value | Meaning |
|---|---|
| `Y` | ✅ Loan Approved |
| `N` | ❌ Loan Rejected |

The original CSV dataset is **not included in this repository**.

See [`data/README.md`](data/README.md) for dataset documentation.

---

# 🤖 Machine Learning

## Workflow

```text
Raw Dataset
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Categorical Encoding
     ↓
Feature Preparation
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Comparison
     ↓
New Applicant Prediction
```

---

## 🧠 Models Used

### 1. Logistic Regression

Logistic Regression was used to predict whether a loan application would be approved or rejected.

### 2. K-Nearest Neighbors (KNN)

KNN was implemented with:

**K = 5**

---

# 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| 🥇 **Logistic Regression** | **86.18%** | 84.00% | **98.82%** | **90.81%** |
| KNN (K=5) | 81.30% | 81.00% | 95.29% | 87.57% |

### 🏆 Best Model

**Logistic Regression** achieved the best overall performance.

It achieved:

- **86.18% Accuracy**
- **84.00% Precision**
- **98.82% Recall**
- **90.81% F1 Score**

---

# 📈 Power BI Dashboard

The project includes a two-page interactive Power BI dashboard.

## Page 1 — Loan Approval Overview

The first page provides an overview of loan approval patterns.

### Key Metrics

- Total Applications
- Approved Loans
- Rejected Loans
-