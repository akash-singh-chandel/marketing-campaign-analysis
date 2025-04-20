# 🛍️ Marketing Campaign Analysis

> SimpliLearn Course-End Project | Applied Data Science with Python

---

## 📌 Problem Statement

Marketing mix is a foundational concept in marketing strategy, commonly structured around the **Four Ps**: Product, Price, Place, and Promotion. This project focuses on analyzing customer data to understand the impact of these components on customer acquisition, purchasing behavior, and campaign effectiveness.

---

## 🎯 Objective

As a data scientist, your role is to conduct **exploratory data analysis (EDA)** and **hypothesis testing** to derive insights that can enhance marketing performance.

---

## 📁 Dataset Overview

- **File**: `marketing_data.csv`
- **Attributes**:
  - **People**: Age, Marital Status, Education, Income
  - **Product**: Expenditures on Wine, Fruits, Meat, Fish, Gold, etc.
  - **Place**: Sales channels (web, store, catalog)
  - **Promotion**: Campaign responses, number of accepted offers, etc.

---

## 🔍 Analysis Steps

1. **Data Loading & Cleaning**
   - Converted income to numeric
   - Parsed date fields
   - Handled missing values using median imputation (grouped by education + marital status)

2. **Feature Engineering**
   - Derived `Age`, `Total_Children`, `Total_Spending`, `Total_Purchases`

3. **Outlier Treatment**
   - Visualized with box plots
   - Applied IQR-based capping

4. **Encoding**
   - Ordinal encoding for `Education`
   - One-hot encoding for `Marital_Status`, `Country`

5. **Correlation & Visualization**
   - Generated heatmaps and scatter plots

6. **Hypothesis Testing**
   - 📌 Older customers prefer in-store shopping?
   - 📌 Parents prefer online purchases?
   - 📌 Are physical stores cannibalized by digital channels?
   - 📌 Does the US outperform other countries in purchase volume?

7. **Insights & Business Questions**
   - 🔝 Top/low revenue products
   - 🎯 Age vs campaign acceptance
   - 🌍 Country-wise campaign success
   - 🧒 Kids vs Spending patterns
   - 🧾 Complaints vs Education

---

## 📊 Tools & Libraries

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy.stats`
- `sklearn.preprocessing`

---

## ✅ Results & Key Insights

- Customers with children lean toward **online channels**.
- **Wine** dominates product revenue, while **fruits and sweets** perform the lowest.
- There's a mild negative correlation between **age and campaign acceptance**.
- Customers from **Spain** and **USA** were among the top responders.
- Complaints were slightly more frequent among customers with **lower education levels**.

---

## 📎 Files Included

- `marketing_campaigns.ipynb` - Main project notebook
- `marketing_data.csv` - Dataset
- `1716985201_marketing_campaign_problem_statement.pdf` - Project brief
- `Data Dictionary.xlsx` (optional)

---

## 📬 Contact

Project by **Akash** | For SimpliLearn Data Science Certification

---
