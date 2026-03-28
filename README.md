Dataset sintético para la predicción de deserción estudiantil utilizando Machine Learning
# 🎓 Student Dropout Prediction - Synthetic Dataset

## 📌 Description
This project focuses on the creation of a synthetic dataset to simulate student dropout in a university context. The goal is to support the analysis and prediction of student attrition using Machine Learning techniques.

---

## 🎯 Objective
To generate a dataset that allows the identification of students at risk of dropping out during their first academic year.

---

## 🧠 Machine Learning Approach
This problem is framed as a **supervised learning classification task**, since the objective is to predict a binary outcome (Dropout: Yes/No).

A **Logistic Regression model** is proposed because:
- It is suitable for binary classification problems  
- It estimates probabilities  
- It is simple and interpretable  

---

## 📊 Dataset Information

The dataset contains **500 records** and includes the following types of variables:

### 🔹 Demographic Variables
- Age: 17–30  
- Gender: Male / Female  
- Origin: Urban / Rural  

### 🔹 Academic Variables
- HighSchool_GPA: 50–100 (with outliers up to 120)  
- Admission_Score: 50–100  
- First_Semester_Grade: 40–100 (with outliers = 0)  

### 🔹 Financial Variables
- Socioeconomic_Level: Low / Medium / High  
- Scholarship: Yes / No  
- Loan: Yes / No  

### 🔹 Target Variable
- Dropout: Yes / No  

---

## ⚠️ Data Issues Introduced

To simulate real-world scenarios, the dataset includes:

- **Missing values:**  
  5% of the data was randomly replaced with null values.

- **Outliers:**  
  - HighSchool_GPA values up to 120  
  - First_Semester_Grade values equal to 0  

- **Categorical variables:**  
  Multiple variables are categorical and require encoding for modeling.

---

## 📈 Exploratory Data Analysis (EDA)

An exploratory analysis was performed using Google Colab to understand the dataset.

### 🔎 Key Findings:
- The dataset structure and variables were successfully validated.  
- Missing values and outliers were identified as expected.  
- The distribution of the *Dropout* variable was analyzed.  
- A relationship between academic performance and dropout risk was observed.  

### 🧾 Conclusion:
The dataset is consistent, meets all the requirements of the activity, and is suitable for supervised Machine Learning models focused on dropout prediction.

---

## 📁 Repository Structure
student-dropout-ml/
│
├── student_dropout_dataset.csv
├── analysis.ipynb
└── README.md

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

##  Final Notes
