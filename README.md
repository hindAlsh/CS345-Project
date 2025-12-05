# CS345-Project


## Team Members
- **Hind Alshahrani**
- **Chase Bishop**

---

## Dataset
**Student Performance Predictions**  
https://www.kaggle.com/datasets/haseebindata/student-performance-predictions

This dataset includes information about student performance in a course.  
Features include:
- Attendance  
- Study hours  
- Previous grades  
- Parental support  
- Final grade (target)

---

## Goal
Our goal is to predict the final grade of students in the course. Since the final grade is a continuous variable, this is a **regression problem**.

We aim to:
- Minimize prediction error  
- Tune hyperparameters  
- Detect overfitting and underfitting  
- Identify the most important features  
- Compare performance to a simple baseline model  

---

## Methods
We began with data preprocessing, including:
- Imputing missing values  
- Normalizing numerical features  
- Encoding categorical variables  

We split the dataset into training and testing sets for fair evaluation.

We then trained several regression models:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

Hyperparameters were tuned using **Grid Search** or **Random Search** with **cross-validation**.

Feature analysis included:
- Correlation analysis  
- Recursive Feature Elimination (RFE)

---

## Evaluation
To measure model performance, we used:
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **Mean Absolute Error (MAE)**  
- **R² Score**  

We compared metrics across all models to determine which offered the best balance of accuracy and interpretability. Residuals and learning curves were inspected to identify overfitting or underfitting.

---

## Team Member Responsibilities

### **Hind**
- Collected and cleaned the dataset  
- Performed EDA with visualizations and statistics  
- Built and trained regression models  
- Tuned hyperparameters  
- Checked for overfitting and underfitting  

### **Chase**
- Evaluated model metrics across all models  
- Interpreted performance metrics to determine the best models  
- Created visualizations of metrics vs. hyperparameters  

---
