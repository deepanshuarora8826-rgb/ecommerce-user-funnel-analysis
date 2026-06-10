# 🛒 E-Commerce User Funnel Analysis

## 📌 Project Overview

This project analyzes user behavior across an e-commerce funnel to identify conversion bottlenecks, high-performing acquisition channels, revenue-driving product categories, and customer purchasing patterns.

The analysis was conducted using **Python (Pandas)** for data cleaning and exploratory analysis, **PostgreSQL** for business-focused SQL analysis, and **Power BI** for interactive dashboard development.

The objective was to simulate a real-world Data Analyst workflow and derive actionable business insights that can improve user conversion and revenue generation.

---

## 🎯 Business Problem

E-commerce businesses often struggle to understand:

- Where users drop off in the purchase journey
- Which marketing channels drive the highest conversions
- Which product categories generate the most revenue
- Which customer segments perform best
- When users are most likely to generate revenue

This project aims to answer these questions through end-to-end data analysis.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|--------|
| Python (Pandas) | Data Cleaning & EDA |
| PostgreSQL | Business Analysis & SQL Queries |
| Power BI | Dashboard Development |
| Jupyter Notebook | Data Exploration |
| GitHub | Project Documentation |

---

## 📂 Dataset Information

**Source:** Kaggle

### Dataset Size

- Total Records: 21,409+
- Unique Users: 10,000
- Funnel Stages:
  - Browse
  - Add to Cart
  - Checkout
  - Purchase

### Key Columns

| Column | Description |
|----------|----------|
| user_id | Unique user identifier |
| session_id | Session identifier |
| event_time | Timestamp of event |
| event | Funnel stage |
| device | Desktop / Mobile / Tablet |
| region | User region |
| channel | Acquisition channel |
| product_category | Product category |
| revenue | Revenue generated |
| bonus_flag | Promotional indicator |

---

# 🔄 Project Workflow

## 1️⃣ Data Cleaning & Preparation (Python)

Performed using Pandas:

- Removed duplicate records
- Checked missing values
- Converted timestamp columns
- Created:
  - Date
  - Day
  - Month
  - Hour
- Validated funnel stages
- Performed Exploratory Data Analysis (EDA)

---

## 2️⃣ SQL Analysis (PostgreSQL)

Key analyses performed:

### Funnel Analysis

- Users at each funnel stage
- Browse → Add to Cart conversion
- Add to Cart → Checkout conversion
- Checkout → Purchase conversion

### Conversion Analysis

- Conversion Rate by Device
- Conversion Rate by Channel
- Conversion Rate by Region
- Conversion Rate by Product Category

### Revenue Analysis

- Revenue by Product Category
- Revenue by Channel
- Revenue by Day
- Revenue by Hour
- Revenue Share Analysis

### Customer Value Analysis

- Average Revenue per Purchase by Category

---

## 📊 Key Business Insights

### Funnel Performance

| Stage | Users |
|---------|---------:|
| Browse | 10,000 |
| Add to Cart | 6,949 |
| Checkout | 3,456 |
| Purchase | 1,004 |

### Overall Conversion Rate

**10.04%**

---

### Funnel Bottleneck

The largest drop-off occurred between:

```text
Checkout → Purchase
```

Only **29.05%** of users who reached checkout completed their purchase.

### Recommendation

- Simplify checkout flow
- Improve payment experience
- Introduce cart abandonment campaigns

---

### Conversion Analysis

#### Best Device

**Desktop** — 10.58%

#### Best Channel

**Google Ads** — 10.63%

#### Best Region

**South** — 10.54%

#### Best Product Category

**Electronics** — 11.16%

---

### Revenue Insights

#### Total Revenue

**₹277.32K**

#### Highest Revenue Category

**Electronics**

Revenue Share: **22.69%**

#### Highest Revenue Channel

**Google Ads**

#### Peak Revenue Day

**Wednesday**

Revenue Generated: **₹49.6K**

---

### Customer Value Insights

Although Electronics generated the highest overall revenue, **Sports** achieved the highest average revenue per purchase.

This suggests that Sports customers tend to place higher-value orders despite contributing less overall revenue.

---

# 📈 Dashboard Pages

## Executive Summary Dashboard

Features:

- KPI Cards
- Funnel Analysis
- Revenue by Category
- Revenue by Channel
- Business Insights

![Executive Summary](Dashboard%20Screenshots/Executive_Summary.png)

---

## Conversion Analysis Dashboard

Features:

- Conversion by Device
- Conversion by Channel
- Conversion by Region
- Conversion by Product Category
- Key Findings

![Conversion Analysis](Dashboard%20Screenshots/Conversion_Analysis.png)

---

## Revenue Analysis Dashboard

Features:

- Revenue by Hour
- Revenue by Day
- Revenue Share Analysis
- Average Revenue per Purchase
- Revenue Insights

![Revenue Analysis](Dashboard%20Screenshots/Revenue_Analysis.png)

---

# 📁 Repository Structure

```text
ecommerce-user-funnel-analysis/
│
├── Dataset/
│   └── Funnel_Analysis_Data.csv
│
├── Python/
│   └── user_funnel_analysis.ipynb
│
├── SQL/
│   └── user_funnel_analysis.sql
│
├── PowerBI/
│   └── User_Funnel_Analysis.pbix
│
├── Dashboard Screenshots/
│   ├── Executive_Summary.png
│   ├── Conversion_Analysis.png
│   └── Revenue_Analysis.png
│
└── README.md
```

---

# 💡 Business Recommendations

### Funnel Optimization

- Reduce friction during checkout
- Improve payment success rates
- Implement checkout abandonment reminders

### Marketing Optimization

- Increase investment in Google Ads
- Improve conversion performance of Organic traffic

### Product Strategy

- Prioritize Electronics for revenue growth
- Promote Sports products to capitalize on high order values

### Customer Experience

- Optimize Mobile user experience
- Improve conversion performance across lower-performing regions

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Querying
- Funnel Analysis
- Revenue Analysis
- Business Intelligence
- Dashboard Design
- Data Visualization
- Business Recommendation Framework
- Stakeholder-Oriented Reporting

---

## 👤 Author

**Deepanshu**

Aspiring Data Analyst skilled in SQL, Python, PostgreSQL, Excel, and Power BI, focused on transforming data into actionable business insights.

Connect with me on LinkedIn for collaboration and analytics discussions.
