# Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning model to predict whether a loan application will be approved or not based on applicant and loan attributes. It involves data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation using classification algorithms.

---

## 🧠 Problem Statement

Financial institutions face the challenge of assessing a borrower's eligibility for loan approval. Automating this decision-making process using historical data and machine learning can streamline operations and reduce human bias.

---

## 📊 Dataset Overview

The dataset includes information about loan applicants as mentioned below. 

| Column Name           | Description |
|-----------------------|-------------|
| **Loan_ID**           | A unique id  |
| **Gender**            | Gender of the applicant Male/female |
| **Married**           | Marital Status of the applicant, values will be Yes/ No |
| **Dependents**        | It tells whether the applicant has any dependents or not. |
| **Education**         | It will tell us whether the applicant is Graduated or not. |
| **Self_Employed**     | This defines that the applicant is self-employed i.e. Yes/ No. |
| **ApplicantIncome**   | ApplicantIncome |
| **CoapplicantIncome** | Co-applicant income |
| **LoanAmount**        | Loan amount (in thousands) |
| **Loan_Amount_Term**  | Terms of loan (in months) |
| **Credit_History**    | Credit history of individual's repayment of their debts |
| **Property_Area**     | Area of property i.e. Rural/Urban/Semi-urban  |
| **Loan_Status**       | Status of Loan Approved or not i.e. Y- Yes, N-No  |


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

- **Random Forest Classifier**
- **K Neighbors Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**


---

## 📈 Visualizations

- Count plots for categorical features
- Bar plots showing approval status across demographics
- Histograms for numeric variables
- Correlation heatmaps

---

## 📁 Project Structure
