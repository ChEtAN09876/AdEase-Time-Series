# 📈 AdEase Wikipedia Page Views Forecasting

Welcome to the official repository for **Wikipedia Page View Forecasting**, a project by the **Data Science Team at AdEase**, a digital ads and marketing infrastructure company.

This project aims to forecast daily view counts of over 145,000 Wikipedia pages across 550 days using time series models. The forecast insights help AdEase clients optimize their ad placements across multiple languages and regions.

---

## 🧠 About AdEase

AdEase helps businesses elicit maximum clicks at minimum cost using an end-to-end AI-driven digital advertising pipeline powered by three modules:

- **Design** – Creative generation
- **Dispense** – Intelligent distribution
- **Decipher** – Impact analytics

Forecasting Wikipedia traffic is a key component in our **Decipher** module to predict and optimize where, when, and how ads should be displayed.

---

## 📁 Dataset

📂 **[Download Dataset](https://drive.google.com/drive/folders/1mdgQscjqnCtdg7LGItomyK0abN6lcHBb)**


## 🧪 Concepts 

- 🧹 **Exploratory Data Analysis**
- 🔁 **Time Series Preprocessing**
- 📊 **ARIMA & SARIMAX Modeling**
- 📆 **Forecasting with Facebook Prophet**
- 🧠 **Model Evaluation (MAPE)**

---

## 📌 What Does "Good" Look Like?

✅ **Data Understanding & Preparation**
- Load & inspect data structure
- Handle missing/null values
- Parse `Page` column into: title, language, access type, and origin
- Visualize page views and identify trends

✅ **Time Series Conversion**
- Reshape wide → long format (date, views)
- Aggregate views (by language, page, etc.)
- Handle seasonality and stationarity
- Apply Dickey-Fuller test
- Use differencing & decomposition

✅ **Modeling**
- Fit **ARIMA** on univariate series
- Use **SARIMAX** with exogenous variables (English campaign days)
- Forecast with **Prophet** (trend + seasonality + holiday handling)
- Evaluate performance using **MAPE**

✅ **Optimization**
- Use grid search or tuning for best ARIMA/SARIMAX/Prophet parameters
- Compare models across different languages
- Generate recommendations for optimal ad placement strategy

---


