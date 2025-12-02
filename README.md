# ❤️ Predicting Heart Disease Using Machine Learning  
**A Full Predictive Analytics Project | ISOM 835 | Suffolk University**

This project uses the UCI Heart Disease dataset to build predictive models that estimate a patient's likelihood of having heart disease based on clinical attributes. The goal of the project is to follow the complete predictive analytics workflow—from Exploratory Data Analysis (EDA) to model development, evaluation, interpretation, and business recommendations.

This repository showcases my work as part of my graduate-level Predictive Analytics course and is designed to be professional and portfolio-ready.

---

## 📌 Project Objectives

- Build a predictive model that identifies heart disease risk using clinical features  
- Perform full EDA to understand data structure and patterns  
- Clean, preprocess, encode, and scale data  
- Train and compare multiple machine learning models  
- Interpret model results and provide business & healthcare insights  
- Discuss ethical considerations and responsible AI principles  

---

## 🔍 Business Questions

1. Which patient characteristics most strongly predict heart disease risk?  
2. Which medical factors are most closely associated with heart disease in this dataset?  
3. Are there noticeable differences between patients with and without heart disease?

---

## 📊 Dataset Description

**Source:** UCI Machine Learning Repository  
**Dataset Name:** Heart Disease Dataset  
**Observations:** 303  
**Features:** 14 predictors + target variable  
**Target:** Presence of heart disease (binary: 0 = no disease, 1 = disease)

**Key Attributes:**
- Age  
- Sex  
- Resting Blood Pressure  
- Cholesterol  
- Chest Pain Type  
- Max Heart Rate  
- Exercise-Induced Angina  
- ST Depression (Oldpeak)  
- Slope, Fasting Blood Sugar, ECG results  
- Thalassemia  

---

## 🧪 Google Colab Notebooks

👉 **Notebook 1: Exploratory Data Analysis (EDA)**  
https://colab.research.google.com/drive/1CfCrtcL5yymUl_UYBVdwMENEn5m43XJd#scrollTo=Tf7y5EVdMBHt

👉 **Notebook 2: Data Cleaning & Preprocessing**  
https://colab.research.google.com/drive/11I91EA-Dpnn6TlCNWikgL13GaCTn-Nid

👉 **Notebook 3: Model Development & Evaluation**  
https://colab.research.google.com/drive/11I91EA-Dpnn6TlCNWikgL13GaCTn-Nid

---

## 📈 Exploratory Data Analysis (EDA)

The EDA focuses on understanding the structure and relationships within the data:

- Distribution of key variables  
- Comparison of features between disease vs. non-disease groups  
- Correlation heatmap  
- Boxplots and histograms  
- Scatter plots for ST depression vs. heart disease  
- Identification of outliers and missing values  

*This notebook includes at least 6 visualizations required for the project.*

---

## 🛠️ Data Cleaning & Preprocessing

Steps included:

- Handling missing values using median/mode imputation  
- Encoding all categorical features using OneHotEncoder  
- Standardizing numerical features  
- Fixing target variable (binary classification)  
- Train/test split with stratification  
- Preparing pipelines with ColumnTransformer  

---

## 🤖 Machine Learning Models

Three models were developed and evaluated:

1. **Logistic Regression** — Baseline, interpretable  
2. **Decision Tree Classifier** — Non-linear split model  
3. **Random Forest Classifier** — Ensemble model (best performer)

### 📊 Evaluation Metrics Used

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC Curve & AUC  
- Cross-validation  
- Hyperparameter tuning with GridSearchCV  

---

## 🏆 Results Summary

### ⭐ Best Model: **Random Forest Classifier**

Random Forest achieved:

- Highest accuracy  
- Best recall for detecting heart disease  
- Best F1-score  
- Highest AUC on ROC curve  
- Lowest false negative rate  

### 📌 Most Important Features (Feature Importance)

- Chest pain type  
- Maximum heart rate  
- ST depression (oldpeak)  
- Exercise-induced angina  
- ECG results  

These align with well-known cardiovascular risk indicators.

---

## 💼 Business Insights & Recommendations

- Patients with high ST depression, low max heart rate, or asymptomatic chest pain should be prioritized for further screening.  
- The model can be used as a **clinical decision-support tool**, not a standalone diagnostic tool.  
- Hospitals can use model outputs to improve early detection workflows.  
- Healthcare networks can use insights to reduce readmission rates through targeted preventive care.  

---

## ⚖️ Ethics & Responsible AI Considerations

- Dataset may not fully represent all demographic groups.  
- Models should be tested for fairness across gender, age, and ethnicity (if available).  
- Predictions should never be used to deny treatment, coverage, or patient autonomy.  
- Transparency is essential—clinicians should understand the basis of predictions.  
- Real-world deployment would require HIPAA-compliant data protection.

---

## 📁 Repository Structure
---

## ▶️ How to Run the Project

1. Clone the repository  
2. Open any notebook in Google Colab  
3. Upload `heart_disease_uci.csv`  
4. Run the full notebook top to bottom  
5. Review the outputs, charts, and model results  

---

## 🙏 Acknowledgments

- UCI Machine Learning Repository for dataset  
- Suffolk University — ISOM 835 Predictive Analytics  
- scikit-learn, pandas, numpy, matplotlib, seaborn  
- ChatGPT was used for writing assistance, editing, and formatting support.  
  All coding, analysis, modeling, and interpretation were done by me.

---

## 📬 Contact

If you’d like to view the full project or discuss the analysis, feel free to reach out!

**Daniela Iebba**  
Graduate Student, Suffolk University  
