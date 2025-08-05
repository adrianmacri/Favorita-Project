# Favorita-Project
# 🛒 Retail Demand Forecasting App

This project is part of the Masterschool Data Analyst program. The goal is to build a demand forecasting app for the **Guayas** region, predicting product sales for the first quarter of 2014 using historical data and a machine learning model.

---

## 🎯 Project Purpose

Retailers need accurate demand forecasting to optimize inventory, reduce waste, and improve logistics. This project helps demand planners visualize sales forecasts interactively and export predictions when needed.

---

## 🤖 Model Choice & Performance

We tested multiple models during Sprint 3 and selected **XGBoost Regressor** due to its high accuracy and efficiency.

- ✅ **Best Model:** XGBoost Regressor  
- 📊 **Validation RMSE:** 15.6919  
- 📅 **Forecast Range:** Jan–Mar 2014  
- 📍 **Region:** Guayas  
- 🛍️ **Product Families:** GROCERY I, BEVERAGES, CLEANING  

The model was trained on historical sales data from 2013 using features like promotions, holidays, store, and item information.

---

## 📂 Project Structure

retail_demand_forecast/
│
├── app/
│ ├── main.py # Streamlit UI
│ ├── config.py # Paths and constants
│ └── init.py
│
├── model/
│ ├── model_utils.py # Model loading and prediction
│ └── init.py
│
├── data/
│ ├── data_utils.py # Data loading and preprocessing
│ └── init.py
│
├── mlflow_results/ # MLflow tracking results (not pushed to GitHub)
│
├── best_model.pkl # Saved model (optional: ignored in GitHub)
├── requirements.txt # Required Python packages
└── README.md # This file


