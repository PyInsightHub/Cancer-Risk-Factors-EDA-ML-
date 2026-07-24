# 𝐂𝐚𝐧𝐜𝐞𝐫-𝐑𝐢𝐬𝐤-𝐅𝐚𝐜𝐭𝐨𝐫𝐬-𝐄𝐃𝐀-𝐌𝐋
*A compact and standardized dataset examining how lifestyle, environmental, and genetic factors influence five common cancer types.*
*Contains 2,000 individual records × 21 features, fully numerical and ready for EDA, dashboarding, and multiclass ML tasks.*


# Why This Dataset?

*Explore risk distributions and correlations across lifestyle factors
Build visual dashboards for population-level cancer risk
Train multiclass models on Cancer_Type with balanced evaluation (macro-F1, accuracy)
Practice class imbalance handling and interpretability*


# Targets

**Primary target:**
*Cancer_Type ∈ {Lung, Breast, Colon, Prostate, Skin}
→ Ideal for multiclass classification (use macro-F1, accuracy, confusion matrix).*

**Optional target:**

*Risk_Level ∈ {Low, Medium, High}
→ Derived from Overall_Risk_Score thresholds:
Low < 0.35 | 0.35–0.65 = Medium | > 0.65 = High*


# 🔍 Analysis Pipeline

**Categorical Features:** 

*Analyzed variables like Cancer_Type, Risk_Level, Gender, H_Pylori_Infection, and BRCA_Mutation using bar charts.*

*Most patients fall into Medium or High risk groups.*

*H_Pylori_Infection and BRCA_Mutation strongly link to specific cancer types.*

**Chi-Square Test:** 

*Confirmed strong associations (p < 0.05) between Cancer_Type,*

*H_Pylori_Infection, and BRCA_Mutation with overall risk level.*

**Numerical Features:** 

*Variables: Age, BMI, Smoking, Alcohol_Use, Air_Pollution, Physical_Activity, etc.*

*High-risk patients → higher BMI, Smoking, and Air Pollution.*

*Low-risk patients → better Physical Activity and Diet Quality.*

**Correlation & Feature Importance:**

 *Top correlated features with overall risk:*

 *1️⃣ Smoking 2️⃣ Air Pollution 3️⃣ BMI 4️⃣ Age*

**Data Preparation:**

 *✅ Dropped non-predictive IDs*

 *✅ One-hot encoded categorical variables*

 *✅ Train-test split (80/20)*

**🤖 Machine Learning Models**

*Random Forest Classifier:*

*Accuracy: 96%*

*Top Predictors: Overall_Risk_Score, Smoking, Air_Pollution, BMI, Age*

*Logistic Regression:*

*Accuracy: 85%*

*✅ Random Forest outperformed across all metrics (F1 ≈ 0.95).*


# 📊 Key Insights

*Environmental and lifestyle factors dominate cancer risk.*

*Smoking, Air Pollution, and Obesity are top contributors.*

*Exercise and Healthy Diet act as strong protective factors.*



---
