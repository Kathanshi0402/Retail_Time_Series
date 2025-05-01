
---

## 🧰 Technologies & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels (SARIMAX, ADF, ARCH tests)

---

## 🔍 Key Features

### ✅ Data Wrangling & Merging
- Handled missing values via forward/backward fill
- Merged oil data into retail sales using date alignment

### 📊 Exploratory Data Analysis
- Time series visualization: Total, Monthly, Quarterly trends
- Sales by store and product family
- Correlation with oil price

### 🛠 Feature Engineering
- Created **Year**, **Month**, **Quarter**, **Year-Month**, **Year-Quarter**
- Differenced data to achieve stationarity
- Encoded product families for modeling

### 📉 Modeling
- SARIMAX trained globally and per-family with exogenous input (`dcoilwtico`)
- ACF/PACF plots and grid search to determine optimal (p,d,q) parameters
- Model adequacy checked via ADF and ARCH tests

### 📈 Forecasting
- Predicted sales for Q2, Q3, Q4 of 2023 by family
- Negative forecasts replaced with 0
- Final predictions aggregated and visualized

---

## 📊 Results

- RMSE & RMSE Ratio computed for each product family
- Actual vs. Predicted sales plotted quarterly
- Forecasts structured for business-level insight across 3 upcoming quarters

---

## 📎 Files to Check Out

- 📘 `Retail_Forecasting.ipynb`: All code, visuals, and logic
- 📄 `Retail.pdf`: Clean, step-by-step report of the analysis
- 📁 `Final_Predictions.csv`: Forecasted sales by product family and quarter

---

## 📈 Sample Visualization

![Sales vs. Oil Prices](assets/sales_vs_oil_prices.png) *(optional)*  
*Scatter plot showing sales fluctuations against crude oil prices.*

---

## 🚀 Future Work

- Incorporate promotions or holiday data as additional features
- Explore LSTM or Prophet models for comparison
- Automate quarterly forecast updates via pipeline

---

## 🤝 Let's Connect

If you have feedback, questions, or ideas for collaboration, feel free to connect!

📧 kathanshi0402@gmail.com  
🔗 https://www.linkedin.com/in/kathanshi-jain/
