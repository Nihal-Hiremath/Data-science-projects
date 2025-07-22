# Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning model to predict whether a loan application will be approved or not based on applicant and loan attributes. It involves data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation using classification algorithms.

---

## 🧠 Problem Statement

Financial institutions face the challenge of assessing a borrower's eligibility for loan approval. Automating this decision-making process using historical data and machine learning can streamline operations and reduce human bias.

---

## 📊 Dataset Overview

The dataset includes information about loan applicants such as income, credit history, education, employment status, and more, along with a target label indicating whether the loan was approved.

### 🔑 Key Features
- `Gender`, `Married`, `Dependents`
- `Education`, `Self_Employed`
- `ApplicantIncome`, `CoapplicantIncome`
- `LoanAmount`, `Loan_Amount_Term`
- `Credit_History`, `Property_Area`
- `Loan_Status` (target variable: Y = approved, N = not approved)

---

## 🔍 Objectives

1. Perform exploratory data analysis to understand trends and distributions.
2. Clean and preprocess the data (e.g., handling missing values, encoding).
3. Train various machine learning classification models.
4. Evaluate model accuracy using appropriate metrics.
5. Choose the best-performing model for deployment or further use.

---

## ⚙️ Tools & Technologies

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries Used:**
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for ML models and preprocessing

---

## 🧹 Data Preprocessing

- Handling missing values using mean/mode imputation
- Encoding categorical variables (Label Encoding or One-Hot Encoding)
- Feature selection based on correlation and importance
- Splitting the dataset into training and test sets

---

## 🤖 Machine Learning Models

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

### 📏 Evaluation Metrics:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC Curve and AUC

---

## 📈 Visualizations

- Count plots for categorical features
- Bar plots showing approval status across demographics
- Histograms for numeric variables
- Correlation heatmaps

---

## 📁 Project Structure

