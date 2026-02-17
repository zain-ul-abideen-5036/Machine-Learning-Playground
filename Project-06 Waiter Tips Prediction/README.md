<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/3075/3075977.png" width="90" height="90"/>
  <h2 align="center">Waiter Tips Prediction using Machine Learning</h2>
</p>

<p align="center">
  Predicting restaurant waiter tips using Linear Regression and data analysis.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-Visualization-purple?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-Linear%20Regression-orange?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

---

## Project Overview

This project analyzes tipping behavior in restaurants and builds a **Linear Regression model** to predict the tip amount based on customer and billing information.

**Dataset:** `tips.csv`

---

## Dataset Features

- `total_bill` – Total bill amount (including taxes)  
- `tip` – Tip amount  
- `sex` – Gender of payer  
- `smoker` – Smoker or non-smoker  
- `day` – Day of the week  
- `time` – Lunch or Dinner  
- `size` – Number of people at the table  

---

## Data Analysis

- Checked null values and descriptive statistics
-  Analyzed tips based on:
   - Total bill amount
   - Table size
   - Day of the week
   - Gender
   - Time (Lunch/Dinner)
   - Smoker vs Non-Smoker  

- Identified which:
   - Day generates highest tips
   - Gender tips more
   - Time of meal results in higher tips  

---

## Data Preprocessing

- Converted categorical features into numerical format  
- Split dataset into training and test sets  
- Prepared features for regression modeling  

---

## Model Training

- Applied **Linear Regression**  
- Trained model on selected features  
- Evaluated prediction performance  

---

## Sample Prediction

**Input:**

```python
{total_bill: 24.50, sex: 1, smoker: 0, day: 0, time: 1, size: 4}
```

**Input:**
```python
{total_bill: 24.50, sex: 1, smoker: 0, day: 0, time: 1, size: 4}
```

---

## Key Insights
- Total bill strongly influences tip amount
- Dinner typically results in higher tips than lunch
- Larger groups tend to give higher total tips
- Gender and smoking status show moderate behavioral differences

---

## Conclusion

This project demonstrates how regression models can be used to:
- Predict tipping behavior
- Analyze customer patterns
- Support restaurant revenue insights
- Apply real-world machine learning in hospitality analytics

---

## Contact

**Zain Ul Abideen**  
📩 abideen5036@gmail.com  
🌐 GitHub: [zain-ul-abideen-5036](https://github.com/zain-ul-abideen-5036)
