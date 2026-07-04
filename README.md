# 🛍️ Retail Business Intelligence Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project analyzes retail sales performance using the Global Superstore dataset to uncover key business insights, identify profitability drivers, and provide data-driven strategic recommendations.

The analysis follows a Business Intelligence approach by exploring business performance, product profitability, root cause investigation, regional performance, and customer contribution to support better business decision-making.

---

## 🎯 Business Objectives

- Evaluate overall business performance from 2011–2014.
- Identify high-performing and underperforming product categories.
- Investigate the root causes of low profitability.
- Analyze regional and customer performance.
- Provide actionable business recommendations based on data insights.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Global Superstore

The dataset contains over **51,000 retail transactions** from **2011–2014**, including:

- Customer Information
- Product Information
- Sales
- Profit
- Discount
- Shipping Cost
- Market
- Region
- Order Date

**Dataset Source:**
- Kaggle: https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset

---

## 🔄 Project Workflow

```text
Business Understanding
        ↓
Data Understanding
        ↓
Data Cleaning
        ↓
Business Performance Analysis
        ↓
Product Performance Analysis
        ↓
Root Cause Analysis
        ↓
Market Performance Analysis
        ↓
Customer Performance Analysis
        ↓
Executive Summary
```

---

# 📊 Analysis Overview

## 1. Business Performance Analysis

- Monthly Sales Trend
- Monthly Profit Trend

### Key Insight

Sales showed consistent growth from 2011–2014, while profit fluctuated more significantly, indicating that revenue growth alone did not guarantee stable profitability.

---

## 2. Product Performance Analysis

- Sales by Category
- Profit by Category
- Sales by Sub-Category
- Profit by Sub-Category

### Key Insight

Technology was the strongest-performing category, while Furniture generated relatively high sales but comparatively lower profitability. Tables was identified as the weakest-performing sub-category with negative total profit.

---

## 3. Root Cause Analysis

- Discount Analysis
- Shipping Cost Analysis
- Product Risk Analysis (Loss Rate)
- Root Cause Validation

### Key Insight

The analysis identified **discount levels above approximately 20%** as the primary factor associated with declining profitability.

Although Tables incurred relatively high shipping costs, shipping cost was **not identified as the primary driver**, supported by a positive correlation between shipping cost and profit.

Loss Rate analysis further revealed hidden transaction-level risks that could not be identified through aggregated profit alone.

---

## 4. Market Performance Analysis

- Sales by Market
- Profit by Market
- Sales by Region
- Profit by Region

### Key Insight

APAC generated the highest sales and profit among all markets.

At the regional level, the Central region demonstrated the strongest overall business performance, while Southeast Asia showed relatively high sales but comparatively weaker profitability.

---

## 5. Customer Performance Analysis

- Sales by Customer Segment
- Profit by Customer Segment
- Top 10 Customers by Sales

### Key Insight

The Consumer segment contributed the highest overall sales and profit.

Tom Ashbrook was identified as the highest-value customer based on total sales.

---

# 🔍 Key Findings

- Sales increased steadily between 2011 and 2014.
- Technology generated the highest sales and profit.
- Furniture produced strong sales but relatively weak profitability.
- Tables recorded negative total profit and the highest loss rate (57.6%).
- Average profit declined noticeably when discounts exceeded approximately 20%.
- Shipping cost was not the primary driver of low profitability.
- APAC and the Central region were the strongest-performing markets.
- Consumer customers generated the highest sales and profit.

---

# 💼 Business Recommendations

- Review discount strategies for products receiving discounts above 20%.
- Reassess pricing and promotional strategies for the Tables sub-category.
- Continue investing in high-performing markets such as APAC.
- Strengthen customer retention programs for high-value customers.
- Monitor transaction-level loss rates alongside traditional profitability metrics.

---

# 📈 Business Impact

This project demonstrates how Business Intelligence techniques can be applied to transform retail transaction data into actionable business insights.

Rather than focusing solely on descriptive reporting, the analysis investigates profitability drivers, validates potential root causes, evaluates operational risks, and provides strategic recommendations to support data-driven decision-making.

---

## 📁 Repository Structure

```text
Retail-Business-Intelligence-Analysis
│
├── Retail_Business_Intelligence_Analysis.ipynb
├── Global_Superstore.xlsx
├── README.md
└── images/
```

---

## 👩‍💻 Author

**Jessica Agnesia Tataung**

Aspiring Data Analyst & Business Intelligence Analyst

- Python
- SQL
- Power BI
- Tableau
- Business Intelligence
- Data Visualization

LinkedIn: https://www.linkedin.com/in/jessicaagnesiat/

Portfolio: https://jessicaagnesiat.github.io/portfolio-website/
