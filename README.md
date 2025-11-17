# Linear-Regression-House-Price-Prediction-Python-Scikit-Learn-
A simple and multiple linear regression project built using Python, Scikit-Learn, Pandas, and Matplotlib.  This project predicts house prices based on area, bedrooms, and age of the house.  Includes dataset, model training, evaluation (MAE, MSE, R²), and a regression line plot.  Beginner-friendly and ready to run.

---

## 📊 Project Objective

The objective of this task is to:

- Understand **Simple Linear Regression**
- Import and preprocess a dataset
- Split data into training and testing sets
- Train a regression model
- Evaluate performance using  
  - MAE (Mean Absolute Error)  
  - MSE (Mean Squared Error)  
  - R² Score  
- Plot the regression line and interpret coefficients

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Scikit-Learn**
- **Matplotlib**

---

## 📥 Dataset Information

The dataset (`house_dataset.csv`) contains the following features:

| Column        | Description                        |
|---------------|------------------------------------|
| Area_sqft     | Built-up area of the house         |
| Bedrooms      | Number of bedrooms                 |
| Age           | Age of the house (years)           |
| Price         | Target variable (House Price ₹)    |

No external download is required because the dataset is included inside this repository.

---

## 🚀 How to Run the Project

### **1️⃣ Install Required Libraries**

Make sure Python is installed.  
Then run:
pip install pandas scikit-learn matplotlib
python linear_rregression.py


---

## 📈 Output Explanation

When the program runs, it will:

### ✔ Print evaluation metrics:
- **MAE** (Mean Absolute Error)  
- **MSE** (Mean Squared Error)  
- **R² Score** (Accuracy of model)

### ✔ Plot a regression graph showing:
- The **actual data points** (scatter plot)
- The **predicted regression line**

This helps visualize the relationship between **Area (sqft)** and **Price**.

---

## 🧠 What You Will Learn

By using this project, you will understand:

- How Linear Regression works
- How to split datasets into Train/Test
- How to evaluate regression models
- How to visualize ML predictions
- How coefficients relate to price prediction
- How to analyze model accuracy

---

## 📚 Code Overview

### **Model Training Steps**
1. Import dataset  
2. Select feature (Area_sqft)  
3. Train model using `LinearRegression()`  
4. Predict values  
5. Evaluate model  

Everything is implemented using:

- `pandas`
- `scikit-learn`
- `matplotlib`

---

## 🧩 Possible Extensions

Here are improvements you can add later:

- ✔ Multiple Linear Regression (Area + Bedrooms + Age)
- ✔ Model saving using Pickle
- ✔ Convert into a Flask Web App
- ✔ Add user input prediction
- ✔ Create a Jupyter Notebook version
- ✔ Add more advanced ML models



