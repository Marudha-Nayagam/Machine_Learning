# 📈 Startup Profit Prediction using Multiple Linear Regression

## 📌 Project Overview

This project implements a **Multiple Linear Regression (MLR)** model to predict the **profit of startups** based on their spending in different areas and their operating state. The goal is to understand how various factors influence profit and to build a predictive model that can be reused in real-world applications.

Dataset used: **50_Startups.csv**

---

## 🎯 Problem Statement

To predict the **Profit** of a startup using the following features:

* R&D Spend
* Administration Cost
* Marketing Spend
* State (categorical)

This is a **supervised regression problem**.

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Pickle

---

## 📂 Project Workflow

### 1️⃣ Data Loading

* Loaded the dataset using Pandas.

### 2️⃣ Data Preprocessing

* Converted categorical feature (`State`) into numerical form using **One-Hot Encoding**.
* Used `drop_first=True` to avoid the **dummy variable trap** (multicollinearity).

### 3️⃣ Feature Selection

* **Independent Variables (X):**

  * R&D Spend
  * Administration
  * Marketing Spend
  * State_Florida
  * State_New York

* **Dependent Variable (Y):**

  * Profit

### 4️⃣ Data Visualization

* Scatter plots were used to visualize the relationship between individual features and profit.
* Regression line visualization was done using **R&D Spend** to validate linearity.

### 5️⃣ Train-Test Split

* Dataset split into:

  * 67% Training data
  * 33% Testing data

### 6️⃣ Model Training

* Applied **Multiple Linear Regression** using `LinearRegression()` from Scikit-learn.

### 7️⃣ Model Evaluation

* Evaluated model performance using **R² Score**.
* R² score measures how well the independent variables explain the variance in profit.

### 8️⃣ Model Saving

* Trained model saved using **Pickle** for future deployment and reuse.

---

## 📊 Model Evaluation Metric

* **R² Score**

A higher R² score indicates better model performance.

---

## 📁 Files in This Repository

* `50_Startups.csv` – Dataset
* `multiple_linear_regression.py` – Model training code
* `profit_prediction_model_mlr.pkl` – Saved trained model
* `README.md` – Project documentation

---

## 🧠 Key Concepts Covered

* Multiple Linear Regression
* One-Hot Encoding
* Dummy Variable Trap
* Train-Test Split
* Model Evaluation (R² Score)
* Model Serialization (Pickle)

---

## 🚀 Future Improvements

* Add Adjusted R² for better evaluation
* Perform feature selection using VIF
* Deploy model using Flask or Streamlit
* Add residual and error analysis plots

---

## 👨‍💻 Author

**Marudhanayagam M**
Aspiring AI / Machine Learning Engineer
Skilled in Machine Learning, Deep Learning, NLP, and Data Science

---

⭐ If you found this project useful, feel free to star the repository!
