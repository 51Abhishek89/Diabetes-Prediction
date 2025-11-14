# Diabetes Prediction using Machine Learning
A machine learning model that predicts diabetes using medical features like glucose, BMI, insulin, and age. Includes preprocessing, normalization, logistic regression training, accuracy evaluation, and a custom input system for instant predictions.

## 📌 Overview
This project predicts whether a person is **diabetic** or **non-diabetic** based on medical diagnostic measurements.  
The dataset includes features such as glucose level, BMI, insulin value, age, pregnancies, and more.  
The goal is to build a reliable model that can assist early detection of diabetes.

---

## 🎯 Motivation
Diabetes has become one of the world's most serious health concerns.  
Early identification helps in:
- Preventive care  
- Reducing long-term health risks  
- Lowering hospitalization chances  

This project demonstrates how machine learning can assist healthcare decision-making using basic medical features.

---

## 🎓 Learning Outcomes
Through this project, I learned:
- How to handle medical datasets  
- Data preprocessing: cleaning, handling missing values, and normalization  
- Splitting data into training and testing sets  
- Building logistic regression models  
- Evaluating ML models using accuracy and other metrics  
- Building a custom prediction system for new patient data  
- End-to-end ML workflow in Google Colab  

---

## ⚙️ Technical Aspects
### ✔ Dataset  
- **diabetes.csv / custom dummy data**
- Features include:
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - DiabetesPedigreeFunction  
  - Age  
- Target variable:
  - `1` → Diabetic  
  - `0` → Non-diabetic  

### ✔ Problem Type  
- **Binary Classification**

### ✔ Machine Learning Workflow  
1. Data loading  
2. Exploratory Data Analysis (EDA)  
3. Handling missing values  
4. Feature scaling (if applied)  
5. Train-test split  
6. Model training (Logistic Regression)  
7. Model performance evaluation  
8. Predicting for new patient input  

---

## 🛠 Technology & Libraries Used
### 🔹 **Programming Language**
- Python

### 🔹 **Libraries**
- `pandas` — dataset loading and cleaning  
- `numpy` — numerical calculations  
- `sklearn.model_selection` — train-test split  
- `sklearn.linear_model` — Logistic Regression  
- `sklearn.preprocessing` — scaling  
- `sklearn.metrics` — accuracy evaluation  

### 🔹 **Tools**
- Google Colab  
- Jupyter Notebook  
- GitHub for version control  

---

## 🧠 Algorithm Used

### **Logistic Regression**
Used because:
- Highly efficient for binary classification  
- Performs well on medical datasets  
- Easy to interpret  
- Fast to train  

---

