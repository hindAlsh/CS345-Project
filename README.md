# CS345 Project 


## 👥 Team Members
- **Hind Alshahrani**
- **Chase Bishop**

---

## 📊 Dataset
**Student Performance Predictions**  
https://www.kaggle.com/datasets/haseebindata/student-performance-predictions

The dataset contains student performance information, including:
- Attendance  
- Study hours  
- Previous grades  
- Parental support  
- Final grade (target)

---

## 🎯 Goal
The goal of this project is to **predict students’ final course grades** using machine learning regression models.

Since the final grade is a continuous variable, this is a **regression problem**.

In this project, we aim to:
- Build multiple regression models  
- Minimize prediction error  
- Tune hyperparameters  
- Detect overfitting and underfitting  
- Identify the most important features  
- Compare performance against a baseline model  

---

## 🔧 Methods

### **Data Preprocessing**
- Imputed missing values  
- Normalized numerical features  
- Encoded categorical variables  
- Performed an 80/20 train-test split  

### **Models Used**
We trained the following models:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

### **Hyperparameter Tuning**
- Grid Search  
- Random Search  
- Cross-validation  

### **Feature Analysis**
- Correlation analysis  
- Recursive Feature Elimination (RFE)

---

## 📈 Evaluation
We evaluated the models using:
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **Mean Absolute Error (MAE)**  
- **R² Score**  

We also inspected:
- Residual plots  
- Learning curves  

This helped determine which models performed best and whether they were overfitting or underfitting.

---

## 👥 Team Member Responsibilities

### **Hind**
- Collected and cleaned the dataset  
- Performed Exploratory Data Analysis (EDA)  
- Built and trained regression models  
- Tuned hyperparameters  
- Checked for overfitting and underfitting  

### **Chase**
- Evaluated performance metrics  
- Interpreted model results and identified best models  
- Created metric visualizations (e.g., error vs. hyperparameters)  

---

