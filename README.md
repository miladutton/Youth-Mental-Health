# 🧠 Youth Mental Health Analysis

---

## 📌 Overview

This project explores factors contributing to youth mental health outcomes in the United States using survey data from the **2023 Youth Risk Behavior Surveillance System (YRBS)**. The primary goal is to identify key behavioral, environmental, and demographic predictors of **self-reported sadness** among teens through a combination of **exploratory data analysis (EDA)** and **machine learning models**.

---

## 🎯 Objectives

- **Preprocess and clean** large-scale youth survey data
- Conduct **exploratory analysis** of trends in mental health indicators
- Build predictive models to identify youth at higher risk of emotional distress
- Visualize the relative importance of key predictors

---

## 🛠 Methods & Tools

**Languages & Libraries:**
- Python: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`
- Jupyter / Google Colab notebooks

**Methods:**
- Data cleaning and encoding
- Correlation analysis
- Logistic regression
- Random Forest, XGBoost classifiers
- Feature importance visualization

---

## 📊 Key Findings

- Variables like **bullying**, **lack of sleep**, and **screen time** emerged as strong predictors of reported sadness.
- Logistic regression achieved an AUC of **~0.73**, outperforming more complex models in interpretability.
- EDA revealed gender and age group disparities in reported mental health outcomes.

---

## 📌 Future Work

- Explore **longitudinal modeling** if time-series data becomes available  
- Integrate **natural language processing (NLP)** on open-ended responses  
- Test performance of ensemble models like **stacked classifiers**


