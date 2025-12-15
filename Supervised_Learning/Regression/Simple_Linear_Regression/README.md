# 💼 Salary Prediction using Simple Linear Regression

This project demonstrates the implementation of **Simple Linear Regression** to predict an employee's salary based on their **Years of Experience** using Python and Scikit-learn.

---

## 📌 Project Overview
Simple Linear Regression is a supervised machine learning algorithm used to predict a **continuous dependent variable** using a **single independent variable**.

In this project:
- **Independent Variable**: Years of Experience
- **Dependent Variable**: Salary

The model learns the relationship using the equation:

y = mx + b

where:
- m = slope (weight)
- b = intercept (bias)

---

## 🧰 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pickle

---

## 📊 Dataset
- **Salary_Data.csv**
- Contains employee salary details based on years of experience.

---

## ⚙️ Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Visualize the data  
4. Split data into training and testing sets  
5. Train the Linear Regression model  
6. Extract model parameters (slope & intercept)  
7. Make predictions  
8. Evaluate model performance using R² score  
9. Save and load the trained model using Pickle  
10. Predict salary for new user input  

---

## 📈 Model Performance
- **Evaluation Metric**: R² Score
- Measures how well the independent variable explains the dependent variable.

---

## 🔮 Sample Prediction
```python
Enter Years of Experience: 15
Predicted Salary: ₹ XXXXX
