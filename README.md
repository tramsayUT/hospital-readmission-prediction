#  Hospital Readmission Prediction

This project uses real-world hospital encounter data to build a machine learning model that predicts whether a diabetic patient will be readmitted to the hospital within 30 days. It demonstrates a full data science pipeline—from data cleaning and exploration to modeling, evaluation, and interpretability—using a public dataset from the UCI Machine Learning Repository.

---

##  Objective

To classify hospital encounters as either leading to a **30-day readmission** or not, using patient demographics, diagnoses, and treatment-related features.

---

##  Dataset

**Source**: [UCI Diabetes 130-US Hospitals Dataset](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)  
**Records**: ~100,000 de-identified patient encounters  
**Time Period**: 1999–2008  
**Target Variable**: `readmitted`  
- Encoded as binary:
  - `1`: readmitted within 30 days
  - `0`: not readmitted (`>30` or `NO`)

**Selected Features**:
- Demographics: `age`, `race`, `gender`
- Clinical: `time_in_hospital`, `number_inpatient`, `number_diagnoses`
- Medications: `diabetesMed`, `insulin`, `change`
- Diagnoses: `diag_1`, `diag_2`, `diag_3`

---

##  Key Questions

- Can patient characteristics and treatment behavior predict early readmission?
- Which features are most predictive of hospital readmission risk?
- How can SHAP values improve the interpretability of the model?

---

##  Tools & Libraries

- `pandas`, `numpy` – data manipulation  
- `scikit-learn`, `XGBoost`, `LightGBM` – modeling  
- `matplotlib`, `seaborn` – visualization  
- `SHAP` – model interpretability  
- `Streamlit` (optional) – deployment demo  

---

##  Workflow

1. **Data cleaning & preprocessing**  
2. **Exploratory data analysis (EDA)**  
3. **Feature engineering & encoding**  
4. **Model training & evaluation**  
5. **Interpretability with SHAP**  
6. **Optional: Deploy simple scoring app with Streamlit**

---

## Evaluation Metrics

- F1 Score  
- Precision / Recall  
- ROC AUC  
- SHAP Feature Importance  

---




