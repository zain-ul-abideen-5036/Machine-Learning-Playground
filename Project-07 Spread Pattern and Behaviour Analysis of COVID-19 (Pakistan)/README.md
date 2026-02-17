<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2785/2785819.png" width="90" height="90"/>
  <h2 align="center">Spread Pattern & Behaviour Analysis of COVID-19 (Pakistan)</h2>
</p>

<p align="center">
  Data Analysis and Machine Learning based forecasting of COVID-19 trends in Pakistan.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-Interactive%20Visualization-purple?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Time%20Series-Forecasting-red?style=for-the-badge"/>
</p>

---

## Project Overview

This project analyzes the **spread pattern and behavior of COVID-19 in Pakistan** using publicly available data from February 26, 2020 to September 01, 2020.

The project includes:

- Exploratory Data Analysis (EDA)
- Daily, Weekly & Monthly trend analysis
- Per Thousand & Per Million statistics
- Visualization of testing, cases, recoveries & deaths
- Machine Learning forecasting using:
  - Linear Regression
  - Random Forest Regressor

**Dataset:** `COVID-19 Daily.xlsx`

---

## Dataset Features

- Date  
- Daily Test  
- Daily Cases  
- Daily Recoveries  
- Daily Deaths  

---

## Data Preparation

- Imported dataset using Pandas
- Converted Date column to datetime format
- Checked null values and column info
- Generated descriptive statistics
- Created new time-based features (Day Number)
- Calculated Per Thousand & Per Million metrics  

---

## Exploratory Data Analysis

### Daily Trend Analysis
- Line Graphs for:
  - Daily Tests
  - Daily Cases
  - Daily Recoveries
  - Daily Deaths
- Scatter Plots
- Bar Charts

### Above & Below Average Analysis
- Highlighted above-average daily testing (Red)
- Highlighted below-average daily testing (Green)

### Weekly & Monthly Analysis
- Resampled data into:
  - Weekly totals
  - Monthly totals
- Identified:
  - Maximum & Minimum values with dates
- Exported weekly & monthly stats to Excel files

---

## Per Thousand & Per Million Statistics

Calculated normalized metrics using Pakistan’s population:

- Tests per Thousand
- Cases per Million
- Recoveries per Million
- Deaths per Million

This helps compare spread intensity relative to population size.

---

## Machine Learning Forecasting

To predict future trends of:

- Daily Cases
- Daily Deaths

### ✔ Model 1: Linear Regression
- Captures linear trend over time

### ✔ Model 2: Random Forest Regressor
- Captures non-linear patterns
- More flexible for real-world fluctuations

### Steps Performed:
- Created numerical time feature (Day_Number)
- Split data into training & testing sets
- Trained both models
- Generated 30-day future predictions

---

## Key Insights

- Testing increased significantly after initial months.
- Cases peaked mid-2020 before gradual decline.
- Recoveries improved with time.
- Death rate remained comparatively stable after peak period.
- Random Forest provided better prediction accuracy compared to Linear Regression.

---

## State-wise Analysis

After national-level analysis, the same:

- Daily trend analysis
- Weekly & Monthly stats
- Per Million calculations
- ML forecasting

were implemented for each province/state separately.

---

## Conclusion

This project demonstrates how data science and machine learning can:

- Analyze pandemic spread patterns
- Identify peak and recovery phases
- Normalize health statistics
- Forecast future outbreak trends
- Assist policymakers with data-driven insights

---

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)

