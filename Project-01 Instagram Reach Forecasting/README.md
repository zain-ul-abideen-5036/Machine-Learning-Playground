<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" width="90" height="90"/>
  <h2 align="center">Instagram Reach Forecasting</h2>
</p>

<p align="center">
  Predict the reach of Instagram posts using historical data and time series forecasting.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistics-teal?style=for-the-badge&logo=seaborn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Statsmodels-Time%20Series-orange?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/SARIMA-Model-brightgreen?style=for-the-badge"/>
</p>

---

## Project Overview

Instagram Reach Forecasting predicts the number of people that an Instagram post, story, or content will reach, based on historical data. It helps content creators optimize their posting strategy, improve engagement, and plan content effectively.

**Dataset:** `Instagram-Reach.csv`  

**Columns:**
- Date
- Instagram Reach

---

## Analysis & Insights

- Checked for missing values and descriptive statistics.  
- Converted `Date` column to datetime format.  
- Analyzed trends and patterns using:
  - Line chart for reach over time  
  - Bar chart for daily reach  
  - Box plot for distribution  
- Extracted day of the week to analyze reach per day.  
- Grouped data by day to calculate mean, median, and standard deviation.  
- Visualized reach for each day using bar charts.  

---

## Forecasting

- Checked trends and seasonality in Instagram reach.  
- Used **SARIMA (Seasonal ARIMA)** model for time series forecasting.  
- Determined optimal `p`, `d`, `q` values using:
  - Autocorrelation plot (ACF)  
  - Partial autocorrelation plot (PACF)  
- Trained SARIMA model and predicted future reach.  

---

## Results

- Predicted Instagram reach for upcoming periods.  
- Visualized forecast against historical reach to evaluate trends.  
- Provided insights for content scheduling and audience engagement.

---

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)
