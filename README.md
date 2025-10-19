# Data Preprocessing (UCI Imports-85)

This repository contains a complete preprocessing workflow for the **Automobile (Imports-85) dataset** and **Laptop Pricing dataset**. 
Automobile dataset was from the UCI Machine Learning Repository.  
The project demonstrates essential data cleaning and transformation steps to prepare raw data for analysis and machine learning tasks.

---

## 📌 Dataset
## 1
- Source: [UCI Machine Learning Repository – Automobile Dataset](https://archive.ics.uci.edu/ml/datasets/automobile)
- Rows: 205
- Attributes: 26 (mix of categorical, continuous, and integer values)
- Target variable (commonly): `price`
## 2
Laptop Pricing Dataset
---

## ⚙️ Preprocessing Steps
1. Import dataset and assign descriptive column headers  
2. Replace `"?"` with `NaN` and evaluate missing data  
3. Handle missing values  
   - Numerical: replace with **mean**  
   - Categorical: replace with **most frequent value (mode)**  
   - Drop rows with excessive missingness  
4. Convert data types to proper numeric and categorical formats  
5. Standardize numerical features (mean=0, variance=1)  
6. Normalize data to range [0,1]  
7. Apply **data binning** (e.g., horsepower → low/medium/high)  
8. Create **indicator (dummy) variables** for categorical attributes  

---

## 📊 Outcome
- Clean, structured, and analysis-ready dataset  
- Suitable for machine learning tasks like price prediction and classification  
- Reusable template for real-world preprocessing pipelines  

---
