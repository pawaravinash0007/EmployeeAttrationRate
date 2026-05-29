<div align="center">

# 👥 EmployeeAttrationRate

### Employee Attrition Prediction & HR Analytics

[![Language](https://img.shields.io/badge/Language-Python-blue?style=flat-square&logo=python)](.)
[![ML](https://img.shields.io/badge/ML-Scikit--learn-orange?style=flat-square&logo=scikit-learn)](.)
[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?style=flat-square&logo=jupyter)](.)
[![Dataset](https://img.shields.io/badge/Dataset-IBM%20HR%20Analytics-purple?style=flat-square)](.)

</div>

---

## 📖 Overview

An **HR Analytics** project that predicts **employee attrition** — whether an employee will leave the company — using the IBM HR Analytics dataset. The project provides actionable insights for HR departments to identify at-risk employees and improve retention strategies.

---

## 🎯 Business Problem

Employee turnover costs companies 33–200% of an employee's annual salary. This project builds a predictive model to identify employees likely to leave, enabling proactive HR interventions.

---

## 📊 Dataset

| Property | Details |
|----------|---------|
| **Source** | IBM HR Analytics Employee Attrition |
| **Samples** | 1,470 employees |
| **Features** | 35 attributes |
| **Target** | `Attrition` (Yes/No) |
| **Attrition Rate** | ~16% (imbalanced) |

**Key Features:** Age, Department, DistanceFromHome, Education, EnvironmentSatisfaction, JobInvolvement, JobLevel, JobSatisfaction, MaritalStatus, MonthlyIncome, NumCompaniesWorked, OverTime, PerformanceRating, WorkLifeBalance, YearsAtCompany.

---

## 🤖 Models & Results

| Model | Accuracy | AUC-ROC |
|-------|---------|---------|
| Logistic Regression | 86% | 0.82 |
| Random Forest | 88% | 0.87 |
| Gradient Boosting | 89% | 0.89 |
| XGBoost | 90% | 0.91 |

---

## ✨ Key Insights

- **Overtime** is the #1 predictor of attrition
- Employees with **low job satisfaction** and **poor work-life balance** are 3× more likely to leave
- **Single employees** and those with **short tenure** have higher attrition rates
- **Sales Representatives** have the highest department-level attrition

---

## 🚀 Getting Started

```bash
git clone https://github.com/pawaravinash0007/EmployeeAttrationRate.git
cd EmployeeAttrationRate
pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter
jupyter notebook Employee_Attrition.ipynb
```

---

## 📁 Repository Structure

```
EmployeeAttrationRate/
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── Employee_Attrition_EDA.ipynb
├── Employee_Attrition_Model.ipynb
└── README.md
```

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `Matplotlib` · `Seaborn`

---

## 👤 Author

**Avinash Pawar** | [@pawaravinash0007](https://github.com/pawaravinash0007)

<div align="center">⭐ Star this repo if you find it useful! ⭐</div>
