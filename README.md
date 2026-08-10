# 🤖 Machine Learning Classification & Regression

<p align="center">
  <strong>End-to-End Supervised Machine Learning Project</strong>
</p>

<p align="center">
  Data Exploration • Preprocessing • Feature Engineering • Model Development • Evaluation
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square">
  <img src="https://img.shields.io/badge/Project-Academic-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Domain-Machine%20Learning-purple?style=flat-square">
</p>

---

## 📌 About the Project

This project presents a complete **machine learning workflow** developed as part of an individual machine learning assignment.

The project focuses on applying supervised machine learning techniques to structured datasets, with particular emphasis on:

- Exploratory Data Analysis
- Data Preprocessing
- Feature Engineering
- Classification Model Development
- Model Evaluation
- Algorithm Comparison
- Result Analysis
- Model Serialization

Three classification algorithms were implemented and compared:

| Algorithm | Type |
|---|---|
| Logistic Regression | Linear Classification |
| Decision Tree | Tree-Based Classification |
| Random Forest | Ensemble Classification |

The project also investigates the suitability of the provided dataset for regression modeling.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Understand and explore the provided datasets.
- Perform Exploratory Data Analysis (EDA).
- Identify data quality issues and feature relationships.
- Apply suitable preprocessing techniques.
- Perform feature engineering.
- Develop multiple classification models.
- Compare at least three machine learning algorithms.
- Evaluate models using suitable performance metrics.
- Analyze class imbalance and its effect on model performance.
- Save trained models for future use.
- Generate structured prediction and evaluation results.
- Document the complete machine learning workflow.

---

# 🔄 Machine Learning Workflow

```text
┌─────────────────────┐
│     Raw Dataset     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Data Understanding  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Exploratory Data    │
│ Analysis (EDA)      │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Data Preprocessing  │
│ • Cleaning          │
│ • Encoding          │
│ • Scaling           │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Feature Engineering │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Train / Test Split  │
└──────────┬──────────┘
           │
     ┌─────┼─────┐
     ▼     ▼     ▼
   ┌────┐ ┌────┐ ┌────┐
   │ LR │ │ DT │ │ RF │
   └─┬──┘ └─┬──┘ └─┬──┘
     │      │      │
     └──────┼──────┘
            ▼
┌─────────────────────┐
│ Model Evaluation    │
│ • Accuracy          │
│ • Precision         │
│ • Recall            │
│ • F1-Score          │
│ • ROC-AUC           │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Model Comparison    │
└─────────────────────┘
