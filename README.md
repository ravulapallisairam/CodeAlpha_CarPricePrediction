# 🚗 Car Price Prediction using Machine Learning

**📌 Internship Project – CodeAlpha | Task 3**

This project is part of my **Data Science Internship at CodeAlpha**, where I developed a machine learning model to predict the **resale price of used cars** using regression techniques. The goal is to analyze how different features like car age, fuel type, and kilometers driven affect pricing.

---

## 📁 Dataset Overview

- **Filename:** `car data.csv`
- **Columns:**
  - `Car_Name`: Brand/Model
  - `Year`: Manufacturing Year (used to derive car age)
  - `Selling_Price`: Target Variable
  - `Present_Price`: Price when new
  - `Kms_Driven`: Distance driven
  - `Fuel_Type`: Petrol/Diesel/CNG
  - `Seller_Type`: Dealer/Individual
  - `Transmission`: Manual/Automatic
  - `Owner`: No. of previous owners

---

## 🔧 Tools & Libraries

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🧠 Project Workflow

1. Data Cleaning & Feature Engineering
2. Convert `Year` into `Car_Age`
3. One-Hot Encoding for Categorical Columns
4. Scaling with StandardScaler
5. Model Training (Random Forest Regressor)
6. Evaluation using RMSE and R² Score
7. Visualizations for Insights

---

## 📊 Visualizations Included

- 🔥 Heatmap: Feature correlation
- 📈 Scatter Plot: Actual vs Predicted price
- 📊 Bar Plots: Seller type, fuel type, etc.

---

## ✅ Model Evaluation

| Metric | Value (Example) |
|--------|-----------------|
| RMSE   | 1.22            |
| R²     | 0.91            |

> Model performs with high accuracy and low error on test data.

---

## 📌 Key Insights

- Cars with fewer kilometers and newer models have higher resale prices.
- Diesel and Automatic cars often retain higher value.
- Dealer sales tend to be priced higher than individual sellers.

---

## ▶️ How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/CodeAlpha_CarPricePrediction.git
