<div align="center">

# 🏦 Loan Approval Prediction using Machine Learning

### An End-to-End Machine Learning Classification Project for Predicting Loan Approval Status

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-4C72B0?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📖 Overview

Loan approval is one of the most important tasks in the banking industry. Financial institutions receive thousands of applications every day, making manual verification slow and error-prone.

This project uses **Machine Learning Classification** to predict whether a loan application will be **Approved** or **Rejected** based on customer details such as income, education, employment, credit score, marital status, property area, and loan purpose.

The project demonstrates the **complete Machine Learning workflow**, including:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Encoding
- Feature Scaling
- Model Training
- Model Evaluation
- Model Comparison

---

# 🎯 Problem Statement

Build a Machine Learning model that predicts whether a customer is eligible for loan approval using historical banking data.

Target Variable:

- ✅ Approved
- ❌ Rejected

---

# 📂 Dataset

The dataset contains customer financial and demographic information.

### Features

| Feature | Description |
|----------|-------------|
| Applicant Income | Monthly income of applicant |
| Coapplicant Income | Monthly income of co-applicant |
| Credit Score | Customer credit score |
| Education Level | Graduate / Non-Graduate |
| Employment Status | Employment information |
| Employer Category | Type of employer |
| Marital Status | Married / Single |
| Property Area | Urban / Semiurban / Rural |
| Loan Purpose | Reason for loan |
| Loan Approved | Target Variable |

---

# 🛠️ Technologies Used

| Category | Technologies |
|-----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Development | Jupyter Notebook |

---

# 🏗️ Project Architecture

```
Loan Dataset
      │
      ▼
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Imputation
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Encoding Categorical Features
      │
      ▼
Correlation Analysis
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling
      │
      ▼
 ┌────────────┬────────────┬─────────────┐
 │            │            │
 ▼            ▼            ▼
Logistic     KNN      Gaussian NB
Regression
 │            │            │
 └────────────┴────────────┘
             │
             ▼
      Performance Evaluation
```

---

# 🔄 Machine Learning Workflow

```
Dataset
   │
   ▼
Load Data
   │
   ▼
Understand Dataset
   │
   ▼
Handle Missing Values
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Encoding
   │
   ▼
Correlation Analysis
   │
   ▼
Train Test Split
   │
   ▼
Feature Scaling
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Evaluation
```

---


---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied before training the models.

### Missing Value Handling

- Numerical Features → Mean Imputation
- Categorical Features → Most Frequent Imputation

### Label Encoding

Applied on:

- Education Level
- Loan Approved

### One Hot Encoding

Applied on:

- Employment Status
- Marital Status
- Loan Purpose
- Property Area
- Gender
- Employer Category

### Feature Scaling

StandardScaler was used to normalize numerical features before training.

---

# 🤖 Machine Learning Models

Three classification algorithms were trained and evaluated.

| Model | Description |
|--------|-------------|
| Logistic Regression | Linear Classification Algorithm |
| K-Nearest Neighbors | Distance-Based Learning |
| Gaussian Naive Bayes | Probabilistic Classification |

---

# 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| 🥇 Logistic Regression | **87.00%** | **78.69%** | **78.69%** | **78.69%** |
| 🥈 Gaussian Naive Bayes | 86.50% | 80.36% | 73.77% | 76.92% |
| 🥉 K-Nearest Neighbors | 75.50% | 71.43% | 32.79% | 44.94% |

---

# 🏆 Best Performing Model

## Logistic Regression

### Accuracy

87%

### Confusion Matrix

```
                Predicted

              No        Yes

Actual No    126         13

Actual Yes    13         48
```

---

# 📁 Project Structure

```
loan-approval-prediction-ml/
│
├── dataset/
│   └── loan_approval_data.csv
│
├── notebook/
│   └── CreditWise_loan.ipynb
│
├── images/
│   ├── loan_distribution.png
│   ├── applicant_income_histogram.png
│   ├── coapplicant_income_histogram.png
│   ├── boxplot_income.png
│   ├── credit_score_distribution.png
│   └── correlation_heatmap.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

# 🚀 Installation

Clone the repository.

```bash
git clone https://github.com/akshaysyadav/loan-approval-prediction-ml.git
```

Move into the project.

```bash
cd loan-approval-prediction-ml
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open

```
CreditWise_loan.ipynb
```

Run all cells.

---

# 📌 Results

- Successfully cleaned and preprocessed banking data.
- Performed Exploratory Data Analysis.
- Applied Feature Engineering and Scaling.
- Compared three Machine Learning algorithms.
- Logistic Regression achieved the highest overall accuracy (**87%**).

---

# 🔮 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- Random Forest Classifier
- XGBoost Classifier
- Support Vector Machine
- Streamlit Web Application
- Flask REST API Deployment
- Docker Containerization

---

# 👨‍💻 Author

**Akshay Yadav**

🎓 Information Technology Student

💼 Full Stack Developer | Machine Learning Enthusiast

🔗 GitHub: https://github.com/akshaysyadav

🔗 LinkedIn: https://linkedin.com/in/akshayyadav2005

---

<div align="center">

### ⭐ If you found this project useful, please consider giving it a Star ⭐

</div>
