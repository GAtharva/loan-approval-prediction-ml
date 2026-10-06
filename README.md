@"

\# Loan Approval Prediction and Analysis Using Machine Learning and Power BI



\## Project Overview



This project focuses on predicting loan approval outcomes using Machine Learning and analyzing loan application data through an interactive Power BI dashboard.



The project uses supervised machine learning techniques for binary classification, where the target variable indicates whether a loan application was approved or rejected.



\### Domain

Finance / Banking



\### Project Type

Supervised Machine Learning — Binary Classification



\### Technologies Used

\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib

\- Seaborn

\- Jupyter Notebook

\- Power BI

\- DAX

\- Power Query



\## Dataset



The project uses the Kaggle Loan Prediction dataset containing \*\*614 loan application records\*\* and \*\*13 columns\*\*.



The target variable is:



\- `loan\_status` — Y = Approved, N = Rejected



The raw dataset is not included in this repository.



\## Machine Learning Workflow



The project follows these major steps:



1\. Data loading and exploration

2\. Data cleaning and preprocessing

3\. Handling missing values

4\. Encoding categorical variables

5\. Feature preparation

6\. Train-test split

7\. Model training

8\. Model evaluation

9\. Model comparison

10\. Loan approval prediction for a new applicant



\## Machine Learning Models



Two classification algorithms were implemented:



\### 1. Logistic Regression



Logistic Regression was used as the primary classification model for predicting loan approval.



\### 2. K-Nearest Neighbors (KNN)



KNN was implemented with \*\*K = 5\*\*.



\## Model Performance



| Model | Accuracy | Precision | Recall | F1 Score |

|---|---:|---:|---:|---:|

| Logistic Regression | \*\*86.18%\*\* | 84.00% | \*\*98.82%\*\* | \*\*90.81%\*\* |

| KNN (K=5) | 81.30% | 81.00% | 95.29% | 87.57% |



Based on the evaluation results, \*\*Logistic Regression performed better than KNN\*\* across the main evaluation metrics.



\## Power BI Dashboard



The project includes an interactive Power BI dashboard with two pages.



\### Page 1 — Loan Approval Overview



The dashboard provides:



\- Total Applications

\- Approved Loans

\- Rejected Loans

\- Approval Rate

\- Average Loan Amount

\- Loan approval status analysis

\- Loan status by property area

\- Loan status by credit history

\- Loan status by education

\- Loan status by gender

\- Interactive slicers



\### Page 2 — Applicant \& Financial Analysis



The second page provides:



\- Income vs Loan Amount analysis

\- Average Loan Amount by Education

\- Average Total Income by Loan Status

\- Loan Status by Loan Term

\- Self-Employment Distribution

\- Average Applicant Income

\- Interactive filters



\## Dashboard Preview



\### Loan Approval Overview



!\[Loan Approval Overview](screenshots/dashboard\_page\_1.png)



\### Applicant \& Financial Analysis



!\[Applicant \& Financial Analysis](screenshots/dashboard\_page\_2.png)



\## Machine Learning Results



\### Model Comparison



!\[Model Comparison](screenshots/model\_comparison.png)



\### Confusion Matrix — Logistic Regression



!\[Confusion Matrix](screenshots/confusion\_matrix.png)



\## Project Files



```text

Loan\_Approval\_Project/

│

├── data/

│   └── README.md

│

├── powerbi/

│   └── Loan\_Approval\_Dashboard.pbix

│

├── presentation/

│   └── Loan\_Approval\_Presentation.pptx

│

├── screenshots/

│   ├── dashboard\_page\_1.png

│   ├── dashboard\_page\_2.png

│   ├── model\_comparison.png

│   └── confusion\_matrix.png

│

├── Loan\_Approval\_Project.ipynb

├── model\_results.csv

├── requirements.txt

└── README.md

