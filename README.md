# 🛍️ Retail Business Performance Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes four years of retail transaction data (2011–2014) to identify key business drivers affecting sales, profitability, customer behavior, and market performance.

Rather than focusing solely on descriptive reporting, this project combines **Business Intelligence, statistical analysis, and customer segmentation** to uncover actionable insights and support data-driven business decisions.

---

## 🎯 Business Objectives

- Analyze overall business performance from 2011–2014.
- Identify profitable and underperforming products.
- Evaluate the impact of discount strategies on profitability.
- Analyze market and regional performance.
- Segment customers using K-Means Clustering.
- Develop strategic business recommendations.

---

## 🛠️ Tools & Technologies

### Languages
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Scikit-posthocs

### Business Intelligence
- Power BI

---

## 📂 Dataset

**Dataset:** Global Superstore (Public Dataset)

The dataset contains over **51,000 retail transactions** collected between **2011–2014**, including:

- Sales
- Profit
- Discount
- Shipping Cost
- Customer Information
- Product Information
- Market & Region
- Order Date

**Dataset Source**

https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset

---

## 🔄 Project Workflow

```text
Business Understanding
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Business Performance Analysis
        ↓
Product & Profitability Analysis
        ↓
Statistical Validation
(Kruskal–Wallis & Dunn's Test)
        ↓
Market Performance Analysis
        ↓
Customer Segmentation
(K-Means Clustering + PCA)
        ↓
Strategic Business Recommendations
```

---

# 📊 Live Dashboard

🚀 **Interactive Dashboard**

https://retail-business-intelligence-analysis.streamlit.app/

---

# 📊 Dashboard Preview

### Business Performance

![Overview](Dashboard%20img/1.png)

### Product Analysis

![Product](Dashboard%20img/2.png)

### Market Analysis

![Market](Dashboard%20img/3.png)

### Customer Analysis

![Customer](Dashboard%20img/4.png)

---

# 📈 Key Business Insights

### 📊 Business Performance

- Sales followed a consistent seasonal pattern across four years.
- Profit experienced recurring declines, particularly during **July**.

### 📦 Product Performance

- Technology generated the highest sales and profit.
- Tables consistently recorded negative profitability despite relatively high sales.

### 💰 Pricing Strategy

- Discounts above **20%** significantly reduced profitability without generating statistically significant additional purchase volume.
- Kruskal–Wallis and Dunn's post-hoc tests validated that discounts beyond 20% did not significantly increase purchase quantity.

### 🌍 Market Performance

- APAC generated the highest overall sales and profit.
- Canada achieved strong profit margins while maintaining minimal discount levels.

### 👥 Customer Analysis

- K-Means clustering identified **five distinct customer segments**.
- High-Value customers represented the greatest long-term business value.
- Discount-Dependent customers generated revenue but consistently reduced profitability.

---

# 💼 Strategic Business Recommendations

### 💰 Pricing Optimization

- Limit discounts to **20% or below**
- Reduce excessive discounting on low-margin products

### 📦 Product Optimization

- Prioritize high-margin product categories
- Review pricing and assortment of underperforming sub-categories

### 👥 Customer Strategy

- Retain High-Value customers
- Reactivate At-Risk customers through personalized campaigns

### 🌍 Market Strategy

- Expand growth initiatives in APAC
- Replicate Canada's low-discount, high-margin pricing approach where applicable

---

# 📈 Business Impact

This project demonstrates how Business Intelligence, statistical analysis, and customer analytics can be integrated to transform retail transaction data into actionable business strategies.

The analysis not only identifies profitability drivers but also validates findings statistically and translates insights into practical recommendations that support sustainable business growth.

---

## 📁 Repository Structure

```text
Retail-Business-Performance-Analysis
│
├── notebooks/
│   └── Retail_Business_Performance_Analysis.ipynb
│
├── dashboard/
│   ├── Retail Dashboard.pbix
│   └── Dashboard img/
│
├── data/
│   └── Global_Superstore.xlsx
│
├── app.py
├── requirements.txt
├── README.md
└── images/
```

---

## 👩‍💻 Author

**Jessica Agnesia Tataung**

**Aspiring Business Intelligence Analyst | Data Analyst**

### Skills

- Python
- Power BI
- Machine Learning
- Statistical Analysis
- Business Intelligence
- Data Visualization

🔗 **LinkedIn**

https://www.linkedin.com/in/jessicaagnesiat/

🌐 **Portfolio**

https://jessicaagnesiat.github.io/portfolio-website/
