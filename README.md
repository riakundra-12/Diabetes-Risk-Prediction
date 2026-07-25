# 🩺 Diabetes Risk Prediction using Machine Learning

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-00599C?style=for-the-badge)
![Random Forest](https://img.shields.io/badge/Random%20Forest-228B22?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📌 Project Overview

This project develops machine learning models to predict **diabetes risk** using behavioral, clinical, and socioeconomic indicators from the **CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015** survey.

The goal is to build a **low-cost screening model** capable of identifying individuals at high risk for diabetes without requiring expensive clinical testing.

---

## 📊 Dataset

**Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015

- 📈 253,680 survey respondents
- 🧩 21 predictor variables
- ✅ 0 missing values
- 📉 Diabetes prevalence: 13.9%

The dataset includes:

- Clinical indicators
- Lifestyle behaviors
- Self-reported health
- Demographic & socioeconomic factors

---

## 🔍 Research Question

> **To what extent can diabetes status be predicted using observable health behaviors and socioeconomic characteristics, and which variables contribute most to prediction performance?**

---

## 🛠️ Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- LASSO Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Neural Network

Both **standard** and **class-weighted** versions of the models were developed to address class imbalance.

---

## 📈 Evaluation Metrics

Model performance was evaluated using:

- ROC-AUC
- Recall (Sensitivity)
- Precision
- Accuracy
- Confusion Matrix

Special emphasis was placed on **Recall**, since correctly identifying diabetic individuals is more important than maximizing overall accuracy.

---

## 📂 Repository Structure

```
Diabetes-Risk-Prediction
│
├── STAT4710_Final_Project.Rmd
├── STAT4710_Final_Project-RF,XGBOOST.Rmd
├── Final Project Slides.pdf
└── README.md
```

---

## 🚀 Key Highlights

- Developed predictive models using six different machine learning algorithms.
- Applied **LASSO** for feature selection.
- Addressed severe class imbalance through **class weighting**.
- Compared traditional statistical models with ensemble learning methods.
- Evaluated model performance using ROC-AUC, Recall, Precision, and Accuracy.
- Identified key predictors including:
  - General Health
  - High Blood Pressure
  - BMI
  - High Cholesterol
  - Age
  - Income
  - Education

---

## 💻 Technologies Used

- R
- R Markdown
- XGBoost
- Random Forest
- Neural Networks
- glmnet (LASSO)
- caret
- ggplot2
- dplyr

---

## 📑 Presentation

The repository also includes the final project presentation summarizing:

- Motivation
- Dataset
- Feature Engineering
- Exploratory Data Analysis
- Machine Learning Pipeline
- Results
- Conclusions

---

## 👥 Team Project

This project was completed collaboratively as part of the **STAT 4710 Machine Learning** course at the **University of Pennsylvania**.

My primary contributions included:

- Research design
- Data understanding and preprocessing
- Statistical analysis
- Machine learning implementation
- Report writing
- Presentation preparation

---

## ⭐ Future Improvements

- Hyperparameter optimization
- SHAP Explainability
- Deployment using Streamlit/Shiny
- Real-time diabetes risk prediction dashboard

---

