# 🛒 Walmart Sales Forecasting

Forecasting weekly sales across Walmart stores using XGBoost regression and time-series feature engineering. The project analyzes holiday impacts, identifies high-volatility stores, and forecasts future sales.

## 📌 Objectives
- Predict weekly sales per store
- Analyze holiday effects on sales
- Identify stores with volatile sales patterns
- Forecast next 4 weeks using autoregressive modeling

## 🧪 Tools & Techniques
- Python, Pandas, NumPy
- XGBoost, Scikit-learn
- Seaborn, Matplotlib
- Feature engineering: lag variables, seasonality, rolling means
- Evaluation metrics: RMSE, MAE, R²
- Statistical analysis: t-test on holiday impact

## 📉 Model Performance
| Metric   | Value       |
|----------|-------------|
| RMSE     | 18,363.12   |
| MAE      | 12,362.91   |
| R² Score | 0.9988      |

> ✅ High predictive accuracy using time-aware XGBoost modeling and engineered features.

## 📊 Key Insights
- **Holidays boost sales** significantly (*p < 0.05*)
- **Store 4, 10, 20** are most volatile → need better forecasting/inventory plans
- Model effectively generalizes across stores with low error and high R²


