# 📈 Predictive Analytics Using Historical Data

> Forecast future trends using regression and time-series models with interactive visualizations and model evaluation metrics.

🔗 **Live Demo:** [https://piyush-kumar-768.github.io/predictive-analytics-dashboard](https://piyush-kumar-768.github.io/predictive-analytics-dashboard)

---

## 📌 Project Overview

This project builds a full predictive analytics pipeline — from raw historical data to future forecasts — using four different models. The interactive dashboard lets you switch between models, choose forecast periods, upload your own CSV data, and evaluate model accuracy in real time.

---

## 🤖 Models Implemented

| Model | Best For | Accuracy |
|---|---|---|
| Linear Regression | Steady upward/downward trends | High on linear data |
| Polynomial Regression | Curved, non-linear trends | High on complex patterns |
| Moving Average | Smoothing noisy data | Moderate — simple baseline |
| Exponential Smoothing | Recent-weighted forecasting | High on seasonal data |

---

## ✨ Key Features

- **4 Prediction Models** — Linear, Polynomial, Moving Average, Exponential Smoothing
- **Model Evaluation** — R², RMSE, MAE with visual accuracy gauge
- **Forecast Chart** — Historical + fitted line + future forecast with 95% confidence bands
- **Residuals Plot** — Error analysis to validate model assumptions
- **Error Distribution** — Histogram to check for normally distributed errors
- **Trend Decomposition** — Separates Original · Trend · Seasonality components
- **Preprocessing Pipeline** — Shows all data cleaning steps applied
- **Forecast Table** — Predicted values with upper/lower confidence bounds
- **3 Built-in Datasets** — Monthly Sales, Temperature, Stock Price
- **CSV Upload** — Bring your own historical data
- **Export Forecast** — Download predictions as CSV

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Frontend & UI |
| Chart.js | Interactive visualizations |
| PapaParse | CSV file parsing |
| Python (scikit-learn) | Referenced ML methodology |
| Statistical Methods | R², RMSE, MAE, Gauss Elimination |

---

## 📊 Datasets Included

| Dataset | Periods | Description |
|---|---|---|
| Monthly Sales | 24 months | Revenue trend with seasonal pattern |
| Temperature | 24 months | Cyclical temperature variation |
| Stock Price | 24 months | Upward trending stock price |

You can also upload your own CSV — any file with a numeric column works automatically.

---

## 📐 Model Evaluation Metrics

| Metric | What it means | Good value |
|---|---|---|
| **R²** | % of variance explained by model | > 0.85 = Excellent |
| **RMSE** | Average prediction error (penalizes large errors) | Lower is better |
| **MAE** | Average absolute prediction error | Lower is better |

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/piyush-kumar-768/predictive-analytics-dashboard.git

cd predictive-analytics-dashboard

# Open directly in browser — no installation needed
open index.html
```

---

## 📁 Project Structure

```
predictive-analytics-dashboard/
│
├── index.html      # Full dashboard (self-contained)
└── README.md       # Project documentation
```

---

## 📈 Key Insights

- **Linear Regression** achieves R² > 90% on trending datasets
- **Exponential Smoothing** outperforms on seasonal or cyclical data
- **Residuals** should be randomly distributed — any pattern means underfitting
- **Confidence bands** widen over time — uncertainty grows with forecast horizon

---

## 👤 Author

**Piyush Kumar**
B.Tech CSE (AI & ML) — Guru Jambheshwar University of Science & Technology

- 📧 piyushkumar768x@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/piyush-kumar2908)
- 🐙 [GitHub](https://github.com/piyush-kumar-768)

---

## 🏆 Acknowledgements

- Built as part of a Data Analytics project submission
- Modeling methodology inspired by scikit-learn and statsmodels
- Forecasting approach based on classical time-series analysis techniques
