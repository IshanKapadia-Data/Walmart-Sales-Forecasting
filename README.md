# 📈 **Walmart Sales Forecasting**

---

## ⭐ Project Overview  
This project forecasts **weekly sales** for Walmart stores using historical sales data, economic indicators, and holiday information.  
The objective is to help Walmart optimize **inventory planning**, **staffing**, and **financial forecasting**.

---

## 🎯 **Objective**  
> Predict weekly sales per store using time series forecasting with machine learning models and evaluate performance using **RMSE**, **MAE**, and **R²**.

---

## 📂 **Dataset Summary**  
- **Period:** February 2010 – October 2012  
- **Features:**  
  - `Store` — Store ID  
  - `Date` — Week start date  
  - `Weekly_Sales` — Total sales (Target)  
  - `Holiday_Flag` — Indicator for holiday weeks  
  - `Temperature`, `Fuel_Price`, `CPI`, `Unemployment` — Economic factors  

---

## 🔍 **Exploratory Data Analysis (EDA) Insights**  
- Sales peak in **November & December** (Holiday season)  
- **Holiday weeks boost sales by ~8%**  
- Economic indicators show **weak correlation** with sales  

---

## 🛠️ **Feature Engineering**  
- ✅ Lag Feature — Previous week's sales (`Lag_1`)  
- ✅ Rolling Mean — 4-week moving average (`Rolling_Mean_4`)  
- ✅ Extracted **Year, Month, Week** for seasonal trends  

---

## 🤖 **Model Performance**  

| Model | RMSE | MAE | R² |
|---|---|---|---|
| Random Forest | \$112,267 | \$75,930 | 0.9562 |
| XGBoost (Default) | \$117,637 | \$76,245 | 0.9519 |
| **XGBoost (Tuned)** | **\$105,052** | **\$68,387** | **0.9617** |

- ✅ **Tuned XGBoost** achieved the best performance with **96% variance explained**

---

## 🔑 **Feature Importance (XGBoost)**  
- ⭐ **Rolling_Mean_4** — Top predictor  
- ⭐ **Lag_1** — Significant time-series influence  
- ⭐ **Holiday_Flag** — Moderate impact  

---


## 🏆 **Key Learnings**  
- Leveraged **time-series feature engineering**  
- Understood importance of hyperparameter tuning  
- Business context is crucial for real-world forecasting  

---

## 👨‍💻 **Author**  
**Ishan Kapadia** — Data Scientist

