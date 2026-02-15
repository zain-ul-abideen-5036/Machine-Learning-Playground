<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2103/2103633.png" width="90" height="90"/>
  <h2 align="center">App User Segmentation & Churn Analysis</h2>
</p>

<p align="center">
  User behavior analysis, retention insights, clustering, and anomaly detection using Machine Learning.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/K--Means-Clustering-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Isolation%20Forest-Anomaly%20Detection-red?style=for-the-badge"/>
</p>

---

## Project Overview

This project analyzes user engagement data to:

- Identify retained and churned users  
- Understand behavioral differences  
- Create user segments using clustering  
- Detect anomalies using machine learning  

**Dataset:** `userbehaviour.csv`

---

## Dataset Features

- `userid`
- `Average Screen Time`
- `Average Spent on App (INR)`
- `Left Review`
- `Ratings`
- `New Password Request`
- `Last Visited Minutes`
- `Status` (Installed / Uninstalled)

---

## Data Analysis

- Checked null values, column info, and descriptive statistics
- Identified highest, lowest, and average screen time
- Identified highest, lowest, and average spending
- Analyzed relationship between:
  - Spending vs Screen Time (Installed vs Uninstalled users)
  - Ratings vs Screen Time
- Generated correlation matrix and explained metric relationships  

---

## User Segmentation

- Applied **K-Means Clustering**
- Determined optimal number of segments
- Segmented users into behavioral groups
- Identified:
  - Retained users
  - High-value users
  - At-risk users
  - Lost users
- Visualized clusters using scatter plots  

---

## Anomaly Detection

- Applied **Isolation Forest Algorithm**
- Detected unusual user behavior patterns
- Identified abnormal engagement metrics

---

## Key Insights

- Active users show higher screen time and spending.
- Low ratings often correlate with uninstall behavior.
- High password requests may indicate user frustration.
- Segmentation helps identify users likely to churn.
- Isolation Forest effectively detects abnormal engagement behavior.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Isolation Forest

---

## Conclusion

This project demonstrates how machine learning can be used to:

- Understand user behavior
- Improve retention strategies
- Identify churn patterns
- Detect anomalies in user engagement
- Support business decision-making

---

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)
