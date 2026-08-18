# 🚗 Austo Automobile Customer Analysis

## 📌 Project Overview

This project analyzes customer and automobile purchasing data for Austo Motor Company to identify customer characteristics, purchasing patterns, and factors associated with automobile purchase prices.

The analysis uses exploratory data analysis (EDA) to understand customer demographics, financial characteristics, vehicle preferences, and purchasing behavior. The findings can help Austo improve customer segmentation, marketing strategies, and targeted promotions.

---

## 🎯 Business Problem

Austo Motor Company wants to better understand its customers and their automobile purchasing behavior.

The objective of this analysis is to identify meaningful patterns in customer demographics, income, vehicle preferences, and purchasing behavior and use these insights to support data-driven marketing and business decisions.

---

## 🔍 Key Business Questions

The analysis addresses the following questions:

1. What are the key demographic and financial characteristics of Austo's customers?
2. Which automobile types are most preferred by customers?
3. How are customer income and automobile purchase prices distributed?
4. How does personal loan status relate to automobile purchase behavior?
5. How much money was spent on automobiles by customers who took a personal loan?
6. Does having a working partner influence the purchase of higher-priced automobiles?

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Exploratory Data Analysis (EDA)**
- **Statistical Analysis**
- **Data Visualization**

---

## 📊 Analysis Performed

### Data Understanding
- Dataset structure and shape
- Data types and column information
- Missing-value identification
- Categorical value analysis
- Data quality checks

### Data Cleaning & Preparation
- Standardization of categorical values
- Missing-value treatment
- Partner salary imputation based on partner employment status
- Preparation of data for analysis

### Exploratory Data Analysis
- Univariate analysis
- Bivariate analysis
- Distribution analysis
- Boxplots
- Correlation analysis
- Pairplot analysis
- Customer segmentation by demographic and financial characteristics

---

## 💡 Key Insights

- Customer age and automobile purchase price show a strong positive relationship in the dataset.
- Automobile purchase preferences vary across customer demographic groups.
- Personal-loan and non-personal-loan customers show broadly similar automobile purchase-price distributions.
- Customers who took personal loans spent approximately ₹27.29 million on automobiles.
- Partner employment status does not appear to be a strong indicator of purchasing a higher-priced automobile.
- Customer demographics, income, and vehicle preferences can support more targeted customer segmentation.

---

## 📈 Business Recommendations

- Develop targeted customer segments using demographic, financial, and vehicle-preference characteristics.
- Use age and income-related patterns to support targeted marketing for different automobile price segments.
- Develop targeted financing options for customers interested in higher-value vehicles.
- Analyze financing preferences and affordability before designing loan offers.
- Do not rely on partner employment status as a primary segmentation factor for higher-priced vehicle targeting.
- Continuously evaluate customer purchasing patterns to improve marketing and promotional strategies.

---

## 📂 Repository Structure

```text
austo-automobile-customer-analysis/
│
├── data/
│   └── austo_automobile.csv
│
└── Austo_Automobile_Customer_Analysis.ipynb
