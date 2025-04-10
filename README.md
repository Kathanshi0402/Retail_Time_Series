# 🛒 Retail Sales Forecasting with GARCH and ARIMA

This project focuses on **forecasting retail sales** by addressing **heteroscedasticity** in time series data using **GARCH models**, followed by **ARIMA-based forecasting**. The analysis is performed **category-wise** for various independent product families (e.g., Automobiles, Bakery), ensuring tailored and accurate sales predictions.

---

## 📊 Overview

- **Objective:** Predict future retail sales while accounting for volatility and category-specific trends.
- **Data:** Daily sales data categorized into multiple independent product families.
- **Tools:** Python, pandas, statsmodels, arch, matplotlib

---

## 🧠 Key Components

### 1. Data Preprocessing
- Grouped data by product family and date
- Cleaned and transformed sales time series for modeling

### 2. Heteroscedasticity Detection
- Conducted residual diagnostics using ARCH model
- Applied GARCH models to stabilize variance where necessary

### 3. Time Series Forecasting
- Built individual ARIMA models for each product family
- Performed category-wise predictions due to independence across product types

### 4. Visualization
- Plotted actual vs predicted sales
- Displayed confidence intervals and volatility estimates


## 🔍 Key Insights

- **Heteroscedastic patterns** found in several categories, requiring GARCH modeling before applying ARIMA.
- **Independent modeling** of product families (e.g., Bakery ≠ Automobiles) improved forecast accuracy.
- ARIMA performed well after variance stabilization, especially in high-volume product categories.

---

## 🛠️ Tools Used

- **Python**
- **pandas**, **matplotlib**, **statsmodels**
- **arch** (for GARCH modeling)

---



