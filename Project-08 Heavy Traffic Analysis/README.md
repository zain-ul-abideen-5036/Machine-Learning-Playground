<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/1482/1482291.png" width="90" height="90"/>
  <h2 align="center">Traffic Volume Analysis</h2>
</p>

<p align="center">
  Analyze traffic patterns and identify indicators of heavy traffic using historical data, visualizations, and time-based analysis.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistics-teal?style=for-the-badge&logo=seaborn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Time%20Series-Analysis-orange?style=for-the-badge&logoColor=white"/>
</p>

---

## Project Overview

This project analyzes traffic volume data collected from **2012-10-02 09:00:00** to **2018-09-30 23:00:00** to identify patterns and key indicators of heavy traffic.  

It focuses on:

- How traffic varies **by time of day**  
- How traffic varies **by day of the week**  
- How traffic varies **by month and year**  
- Optional: Impact of **weather conditions** on traffic  

**Dataset:** `Traffic Volume.csv`  

**Columns:**
- `date_time` – Timestamp of measurement  
- `traffic_volume` – Number of vehicles per hour  

---

## Analysis & Insights

### 1. Data Overview
- Checked for missing values and data types.  
- Converted `date_time` to `datetime` format for easier time-based analysis.  
- Traffic volume ranges from **0 to 7,280 cars per hour**.  

### 2. Day vs Night Analysis
- Day: 7 AM – 7 PM  
- Night: 7 PM – 7 AM  
- Observations:
  - Daytime traffic is significantly higher (left-skewed).  
  - Nighttime traffic is generally lighter (right-skewed).  

### 3. Time Indicators
- **Monthly Traffic:** Warm months (Mar–Oct) show heavier traffic; cold months (Nov–Feb) show lighter traffic.  
- **Day of Week:** Business days (Mon–Fri) have heavier traffic than weekends.  
- **Hourly Traffic:** Rush hours around **7 AM and 4 PM** on business days.  

### 4. Key Insights
- Daytime traffic is heavier than nighttime traffic.  
- Warm months → higher average traffic (~5,000 cars/hour).  
- Business days → heavier traffic than weekends.  
- Rush hours → 7 AM and 4 PM during business days.  
- Optional: Weather conditions can influence traffic patterns and can be analyzed if available.  

---

## Visualizations

- Histograms: Overall, day vs night traffic  
- Line plots: Average traffic by month, day of week, and hour  
- Bar plots: Distribution of traffic across days of the week  
- Optional scatter plots for weather impact  

---

## Optional Extensions

- **Weather Analysis:** Explore impact of temperature, rain, or snow on traffic volume.  
- **Predictive Modeling:** Use regression or time series forecasting (ARIMA/SARIMA) to predict traffic volume.  
- **Anomaly Detection:** Detect unusual spikes in traffic due to accidents, holidays, or construction.  
- **Interactive Dashboard:** Create a dashboard using `Plotly` or `Dash` for dynamic analysis.  

**Example Commented Code for Weather Analysis:**
```python
# plt.scatter(traffic['temp'], traffic['traffic_volume'])
# plt.xlabel('Temperature (°C)')
# plt.ylabel('Traffic Volume')
# plt.title('Traffic Volume vs Temperature')
# plt.show()
```

--- 

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)
