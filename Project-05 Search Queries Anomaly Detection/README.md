<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/3588/3588614.png" width="90" height="90"/>
  <h2 align="center">Search Queries Anomaly Detection</h2>
</p>

<p align="center">
  Identifying unusual search query performance using statistical analysis and machine learning.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-Interactive%20Visualization-purple?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Isolation%20Forest-Anomaly%20Detection-red?style=for-the-badge"/>
</p>

---

## Project Overview

This project focuses on detecting **underperforming and overperforming search queries** using anomaly detection techniques.

The objective is to analyze search performance metrics and identify unusual query patterns based on:

- Clicks  
- Impressions  
- CTR (Click Through Rate)  
- Search Position  

**Dataset:** `Queries.csv`

---

## Dataset Features

- Top Queries  
- Clicks  
- Impressions  
- CTR  
- Position  

---

## Data Preparation

- Checked null values, column information, and descriptive statistics
- Converted CTR from percentage string to float
- Cleaned and tokenized search queries
- Analyzed word frequency using text processing  

---

## Exploratory Data Analysis

- Identified most common words in queries  
- Visualized word frequency distribution  
- Analyzed top queries by clicks and impressions  
- Compared highest and lowest CTR queries  
- Generated correlation matrix between metrics  

---

## Anomaly Detection

Applied **Isolation Forest Algorithm** to detect unusual search query behavior.

Steps performed:
- Selected relevant numerical features  
- Trained Isolation Forest model  
- Generated anomaly predictions  
- Classified queries as normal or anomalous  

---

## Key Insights

- Queries with high impressions but low CTR indicate optimization opportunities  
- Extremely high CTR with low impressions may indicate niche success  
- Position strongly influences click performance  
- Isolation Forest effectively detects outlier queries  

---

## Conclusion

This project demonstrates how anomaly detection can improve:

- SEO optimization strategies  
- Marketing performance analysis  
- Content planning decisions  
- Search visibility monitoring  

---

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)
