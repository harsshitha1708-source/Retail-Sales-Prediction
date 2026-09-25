# 🛒 Retail Sales Prediction & Business Insights

## 📌 Project Overview

This project analyzes retail sales data to identify patterns in product and outlet performance and uses machine learning to predict product outlet sales.

The project combines Exploratory Data Analysis (EDA), data preprocessing, visualization, and machine learning to generate useful business insights.

---

## 🎯 Objectives

- Analyze retail sales data
- Clean and preprocess the dataset
- Explore relationships between product and outlet features
- Visualize sales patterns
- Build a machine learning regression model
- Evaluate prediction performance
- Identify important features influencing sales
- Generate business insights

---

## 📊 Dataset

The project uses the BigMart Sales dataset.

The dataset contains information about:

- Products
- Product categories
- Product price
- Product visibility
- Outlet characteristics
- Outlet location
- Outlet type
- Product outlet sales

### Target Variable

`Item_Outlet_Sales`

The target variable represents the sales of a product at a particular outlet.

---

## 🔍 Exploratory Data Analysis

The analysis includes:

- Sales distribution
- Average sales by product type
- Average sales by outlet type
- Average sales by outlet location
- MRP vs sales analysis
- Correlation analysis
- Feature importance

---
### Results

| Metric | Value |
|---|---:|
| Mean Absolute Error (MAE) | 760.11 |
| Root Mean Squared Error (RMSE) | 1087.10 |
| R² Score | 0.5652 |

The Random Forest Regressor achieved an R² score of 0.5652 on the test dataset, meaning the model explains approximately 56.52% of the variation in the target sales values.

## 🤖 Machine Learning

### Model Used

**Random Forest Regressor**

The model predicts:

```text
Item_Outlet_Sales
## 💡 Key Findings

The analysis explored how product characteristics and outlet-related factors are associated with retail sales.

Key areas examined include:

- Product type and average sales
- Outlet type and average sales
- Outlet location and average sales
- Product MRP and sales
- Item visibility and sales
- Feature importance from the Random Forest model

The model's feature importance analysis was used to identify which variables contributed most to sales predictions.