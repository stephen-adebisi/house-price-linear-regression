

https://github.com/user-attachments/assets/38d0ec84-b7f9-4dda-8b5d-aeecd6fee77c


# 🏠 House Price Prediction using Simple Linear Regression

This project implements **Simple Linear Regression** to predict house prices using a single independent variable.

The objective is to understand the fundamentals of linear regression, model evaluation, and visualization using Python and scikit-learn.

---

## 📊 Dataset Overview

The dataset contains:

- 📐 **Area** (Independent Variable)
- 💰 **Price** (Target Variable)

The model predicts house price based only on property area.

---

## ⚙️ Project Workflow

1️⃣ Data loading and preprocessing  
2️⃣ Train-test split (70% : 30%)  
3️⃣ Model training using `LinearRegression()`  
4️⃣ Model evaluation using:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - Relative RMSE (RRMSE %)
   - R² Score  
5️⃣ Visualization:
   - 📈 Line Plot (Actual vs Predicted)
   - 🎯 1:1 Scatter Plot

---

## 📐 Model Equation

\[
Y = aX + b
\]

Where:

- **X** = Area  
- **Y** = Predicted House Price  
- **a** = Slope (Coefficient)  
- **b** = Intercept  

---

## 📈 Model Performance

- R² ≈ 0.19  
- RRMSE ≈ 35%

These results indicate that house price cannot be accurately predicted using area alone.

---

## 🛠️ Technologies Used

- 🐍 Python  
- 📦 NumPy  
- 🗂 Pandas  
- 📊 Matplotlib  
- 🤖 Scikit-learn  

---

## 🚀 How to Run

Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
