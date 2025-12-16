
# Credit Card Risk Prediction

## 📌 Project Overview
This project focuses on predicting **credit card risk** by classifying customers as **Good** or **Bad** based on their financial and behavioral attributes.  
The goal is to assist financial institutions in assessing creditworthiness and minimizing default risk using machine learning techniques.

---

## 🎯 Problem Statement
To build a machine learning classification model that predicts whether a credit card customer is a **good** or **bad** credit risk.

---

## 📊 Dataset
- **Source:** Kaggle  
- **File Name:** `credit_card.csv`  
- **Rows:** ~200,000  
- **Columns:** 15  
- The dataset contains both numerical and categorical features related to customer credit behavior.

---

## 🏷 Target Variable
- **Good Customer** – Low credit risk  
- **Bad Customer** – High credit risk / potential defaulter  

---

## ⚙️ Data Preprocessing & Feature Engineering
The following steps were performed to prepare the data for modeling:

### 1. Data Splitting
- Split the dataset into **training** and **testing** sets.

### 2. Missing Value Treatment
- Handled missing values using the **Random Sample Imputation** method.

### 3. Variable Transformation
- Applied **Yeo-Johnson transformation** to normalize skewed numerical features.

### 4. Outlier Treatment
- Detected and handled outliers using the **Trimming technique**.

### 5. Feature Selection
- **Filter method**
- **Correlation and hypothesis-based techniques**

### 6. Encoding
- Converted categorical variables into numerical format using **One-Hot Encoding**.

### 7. Data Balancing & Scaling
- Balanced the target classes to handle class imbalance.
- Scaled features to improve model performance.

---

## 🤖 Machine Learning Models
Multiple classification models were trained and evaluated using the cleaned dataset.

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Naive Bayes  

### ✅ Final Model Selection
- **Logistic Regression** was selected as the final model based on **ROC Curve performance**.

---

## 📈 Model Performance
- **Accuracy:** 96%  
- **Evaluation Metrics Used:**
  - Accuracy
  - ROC Curve
  - Classification Report

The model demonstrated strong predictive performance in distinguishing between good and bad customers.

---

## 💾 Model Saving
- The trained Logistic Regression model was saved using **Pickle** for future deployment and inference.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries & Frameworks:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Flask
  - Logging

---


## 📌 Conclusion
This project successfully demonstrates an end-to-end machine learning pipeline for **credit risk prediction**, from data preprocessing and feature engineering to model selection and evaluation. The final model can be effectively used to support data-driven credit approval decisions.

---
