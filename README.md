# AI & ML Internship – Task 4  
## Feature Encoding & Scaling (Adult Income Dataset)

---

## 📌 Objective
The goal of this task is to preprocess the Adult Income Dataset by applying appropriate feature encoding and scaling techniques to make the data ready for machine learning models.

---

## 📊 Dataset
**Adult Income Dataset**  
Source: UCI Machine Learning Repository  

The dataset contains demographic and employment-related information used to predict whether an individual earns more than $50K per year.

---

## 🔍 Features Overview

### Numerical Features
- age  
- fnlwgt  
- education-num  
- capital-gain  
- capital-loss  
- hours-per-week  

### Categorical Features
- workclass  
- education  
- marital-status  
- occupation  
- relationship  
- race  
- sex  
- native-country  

### Target Variable
- income (`<=50K`, `>50K`)

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 🔄 Steps Performed

1. Loaded the Adult Income Dataset directly from the UCI repository  
2. Handled missing values by removing incomplete rows  
3. Identified numerical and categorical features  
4. Applied **Label Encoding** to the target variable (`income`)  
5. Applied **One-Hot Encoding** to categorical features  
6. Scaled numerical features using **StandardScaler**  
7. Compared feature values before and after scaling  
8. Saved the final preprocessed dataset  

---

## ⚖ Why Encoding & Scaling?

- Encoding converts categorical data into numerical form required by ML models  
- One-Hot Encoding prevents incorrect ordinal relationships  
- Feature scaling ensures all numerical features contribute equally  
- Improves model accuracy, convergence speed, and stability  

---

## 📁 Repository Structure

