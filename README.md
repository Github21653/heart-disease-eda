# Heart Disease Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a comprehensive exploratory data analysis (EDA) on a heart disease dataset containing demographic, clinical, and diagnostic features. The objective is to identify meaningful patterns, associations, and limitations in the data before predictive modeling.

---

## 📊 Dataset Description
- Records: 270 patients
- Features: 14 (numerical and categorical)
- Target variable: Heart Disease (Presence / Absence)
- Dataset appears to be hospital-based with a relatively high disease prevalence.

---

## 🔍 EDA Approach

### 1. Data Quality Checks
- No missing values detected
- No duplicate records found
- Encoded categorical variables verified

### 2. Univariate Analysis
- Numerical features exhibit skewness and medically plausible outliers
- Several categorical features show imbalanced distributions

### 3. Bivariate Analysis (Target vs Feature)
- Strong associations observed with:
  - Chest pain type
  - ST depression
  - Exercise-induced angina
  - Maximum heart rate
- Moderate associations observed with age
- Weak standalone discrimination from blood pressure and cholesterol

### 4. Multivariate Analysis
- Feature combinations (e.g., ST depression + Max HR) provide clearer separation
- Multivariate patterns outperform individual feature analysis

---

## 🧠 Key Insights
- Chest pain characteristics and stress-test indicators are strong signals of heart disease
- Exercise tolerance is inversely related to disease presence
- Traditional risk factors alone show limited discriminative power
- Multivariate modeling is required for effective prediction

---

## ⚠️ Limitations
- Observational analysis only (no causal inference)
- Feature overlap exists between disease classes
- Moderate dataset size

---

## 🚀 Next Steps
- Feature engineering and preprocessing
- Predictive modeling and validation
- Feature importance analysis

---

## 📎 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 👤 Author
Sahil Darge
