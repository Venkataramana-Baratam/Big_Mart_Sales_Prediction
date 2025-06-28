# Big Mart Sales Prediction 🛒📊

This project predicts the sales of products across various outlets for a retail chain called Big Mart. The goal is to use regression techniques on historical sales and product data to estimate future sales.

## 🎯 Objective
Predict the **Item Outlet Sales** using machine learning based on item-level and outlet-level features.

## 📊 Dataset Summary
- **Source**: Big Mart Sales dataset
- **Features include**:
  - Item characteristics: `Item_MRP`, `Item_Weight`, `Item_Fat_Content`, etc.
  - Outlet characteristics: `Outlet_Type`, `Outlet_Establishment_Year`, etc.
- **Target**: `Item_Outlet_Sales` (numeric)

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Sklearn
- XGBoost

## 📈 ML Approach
- **Data Preprocessing**
  - Handling missing values
  - Label Encoding and One-Hot Encoding
  - Feature scaling (if needed)
- **Modeling**
  - Used **XGBoost Regressor** (`XGBRegressor`) for prediction
- **Evaluation**
  - RMSE, R² Score
