# 🎓 Student Performance Analysis & Prediction using Machine Learning

## 📌 Project Overview
This project analyzes how **demographic and socio-economic factors influence student academic performance** and builds machine learning models to **predict student math scores**.

The project combines **Exploratory Data Analysis (EDA)** and **Machine Learning** to extract insights and create predictive models that can help educators identify at-risk students early.

---

## 🎯 Problem Statement
Educational institutions often struggle to:
- Identify students who may perform poorly
- Understand factors affecting academic success
- Provide early intervention

This project uses **data analysis and machine learning** to uncover patterns and predict student performance.

---

## 📊 Dataset Description
The dataset contains student demographic and academic information:

| Feature | Description |
|---|---|
| Gender | Male/Female |
| Race/Ethnicity | Group A–E |
| Parental Level of Education | Parent education background |
| Lunch | Standard / Free or Reduced |
| Test Preparation Course | Completed / None |
| Math Score | Target variable 🎯 |
| Reading Score | Exam score |
| Writing Score | Exam score |

---

## 🔎 Exploratory Data Analysis (EDA)

Key steps performed:

✔ Data cleaning & preprocessing  
✔ Missing value and duplicate checks  
✔ Feature engineering  
✔ Distribution & correlation analysis  
✔ Data visualization  

### 📈 Feature Engineering
New features created:
- **Total Score** = Math + Reading + Writing  
- **Average Score**

These features improved the understanding of overall performance.

---

## 📊 Key Insights from Data Analysis

- Students who completed **test preparation courses** scored higher.
- Students with **standard lunch** performed better.
- **Parental education level** strongly affects performance.
- Noticeable performance patterns across **gender and ethnicity**.
- Strong correlation between **reading, writing, and math scores**.

---

## 🤖 Machine Learning Models Used

Multiple regression models were trained and compared:

- Linear Regression ⭐ (Best model)
- Random Forest Regressor
- Decision Tree Regressor
- K-Nearest Neighbors Regressor

### 🏆 Best Model: Linear Regression
Linear Regression achieved the best performance in predicting math scores.

---

## 📏 Evaluation Metrics
Models were evaluated using:

- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)

These metrics measure prediction accuracy and model reliability.

---

## 🛠 Tech Stack

**Programming Language**
- Python 🐍

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

