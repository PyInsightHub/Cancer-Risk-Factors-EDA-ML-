# 🧬 Cancer Risk Factors: Exploratory Data Analysis & Machine Learning

> A comprehensive Data Science project analyzing how **lifestyle, environmental, and genetic factors** influence the risk of five common cancer types using **Exploratory Data Analysis (EDA)** and **Machine Learning**.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

This project investigates how **lifestyle habits**, **environmental exposure**, and **genetic factors** contribute to cancer risk. The dataset contains **2,000 patient records** with **21 numerical features**, making it ideal for:

- 📊 Exploratory Data Analysis (EDA)
- 📈 Interactive Dashboard Development
- 🤖 Machine Learning
- 📉 Feature Importance Analysis
- 📋 Statistical Hypothesis Testing

---

# 📂 Dataset Information

| Feature | Details |
|----------|---------|
| Records | 2,000 |
| Features | 21 |
| Dataset Type | Structured |
| Missing Values | None |
| Target Variable | Cancer_Type |
| ML Task | Multiclass Classification |

---

# 🎯 Project Objectives

This project aims to:

- Analyze the distribution of cancer risk factors.
- Discover relationships between lifestyle and cancer occurrence.
- Build meaningful visualizations for data exploration.
- Train multiclass classification models.
- Compare model performance using standard evaluation metrics.
- Identify the most influential cancer risk factors.

---

# 🎯 Target Variables

## Primary Target

**Cancer_Type**

- Lung Cancer
- Breast Cancer
- Colon Cancer
- Prostate Cancer
- Skin Cancer

Recommended evaluation metrics:

- Accuracy
- Precision
- Recall
- Macro F1-Score
- Confusion Matrix

---

## Optional Target

**Risk_Level**

Derived from **Overall_Risk_Score**:

| Risk Score | Category |
|------------|----------|
| < 0.35 | Low |
| 0.35 – 0.65 | Medium |
| > 0.65 | High |

---

# 🔍 Exploratory Data Analysis (EDA)

## Categorical Analysis

The following categorical variables were analyzed:

- Cancer Type
- Risk Level
- Gender
- H. Pylori Infection
- BRCA Mutation

### Key Findings

- Most patients belong to the **Medium** and **High** risk groups.
- BRCA mutations show a strong association with specific cancer types.
- H. Pylori infection appears more frequently in selected cancer categories.

---

## Statistical Analysis

### Chi-Square Test

Statistical hypothesis testing confirmed significant relationships between:

- Cancer Type
- H. Pylori Infection
- BRCA Mutation

All significant associations achieved:

**p-value < 0.05**

---

## Numerical Feature Analysis

Analyzed numerical variables include:

- Age
- BMI
- Smoking
- Alcohol Use
- Air Pollution
- Physical Activity
- Diet Quality
- Overall Risk Score

### Observations

High-risk individuals generally exhibit:

- Higher BMI
- Higher Smoking Scores
- Greater Air Pollution Exposure
- Older Age

Lower-risk individuals generally demonstrate:

- Better Physical Activity
- Healthier Diet Quality

---

# 📈 Correlation Analysis

The strongest predictors of cancer risk were:

1. 🚬 Smoking
2. 🌫 Air Pollution
3. ⚖ BMI
4. 👤 Age

These variables showed the highest correlation with **Overall Risk Score**.

---

# ⚙ Data Preparation

The dataset was prepared using the following preprocessing pipeline:

- ✅ Removed non-predictive ID columns
- ✅ Encoded categorical variables
- ✅ Feature scaling (where applicable)
- ✅ Train-Test Split (80:20)
- ✅ Model-ready dataset creation

---

# 🤖 Machine Learning Models

## Random Forest Classifier

**Accuracy:** **96%**

Top Important Features

- Overall Risk Score
- Smoking
- Air Pollution
- BMI
- Age

---

## Logistic Regression

**Accuracy:** **85%**

---

# 📊 Model Comparison

| Model | Accuracy |
|--------|----------|
| Random Forest | **96%** |
| Logistic Regression | **85%** |

✅ **Random Forest achieved the best overall performance with an approximate Macro F1-Score of 0.95.**

---

# 💡 Key Insights

- Environmental and lifestyle factors have a significant impact on cancer risk.
- Smoking is the strongest predictor among all variables.
- Air pollution substantially increases cancer risk.
- Higher BMI is associated with increased overall cancer risk.
- Regular physical activity and a healthy diet appear to reduce cancer risk.
- Genetic mutations such as BRCA also contribute to elevated risk for specific cancer types.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost and LightGBM implementation
- SHAP explainability
- Cross-validation
- Interactive Power BI Dashboard
- Model deployment using Streamlit or Flask

---

# 👨‍💻 Author

**Arpan Ghosal**

**Junior Data Scientist**

Passionate about transforming data into actionable insights through Machine Learning, Data Analytics, and Artificial Intelligence.

---

⭐ **If you found this project useful, consider giving it a Star!**
