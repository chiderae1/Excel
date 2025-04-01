# 📊 Customer & Transaction Record for Rubies (Excel Project)

## 📁 Project Overview

This Excel project presents a structured analysis of customer and transaction data for a financial institution. It covers the end-to-end workflow of data cleaning, transformation, aggregation, visualization, and reporting.

---

## 🎯 Purpose

The project aims to:
- Understand customer distribution across countries, tiers, and statuses
- Explore monthly registration and transaction behaviors
- Analyze inward, outward, and internal fund flows
- Present data visually through interactive dashboards using PivotTables, slicers, and charts

---

## 📂 Dataset Description

The data consists of:
- **Cleaned Customer Data (clean Customer sheet): Includes registration dates, account status, tiers, age, and country
- **Cleaned Transaction Data (Clean Transaction sheet): Contains transaction dates, types, amounts, and derived insights like fair amount and counts

Data originates from a financial instituttion and is used for demonstration purposes only.

---

## 🛠️ Key Techniques & Features

- Cleaned and transformed raw data for analysis
- Derived time-based fields like month for both registration and transactions
- Created categorized columns (e.g., transaction fairness)
- Built visual insights using PivotTables and PivotCharts
- Incorporated slicers and timeline filters for interactive dashboard views
- Applied TEXT(), IF(), and aggregation formulas to prepare meaningful summaries

---

## 📈 Key Insights

### 👥 Customer Demographics
- **Total Customers: 8,966
- **By Account Status:
  - Active: 8,311
  - Pending: 401
  - Blocked: 254

### 🌍 Customer Distribution by Country
- **Nigeria: 3,910 customers (44%)
- **Kenya: 2,175 customers
- **United Kingdom: 1,699 customers
- **Ghana: 1,182 customers

📌 *Nigeria is the dominant customer base. Ghana may offer room for growth.

### 🧱 Account Distribution by Tier
| Tier   | Customers |
|--------|-----------|
| TIER 0 | 4,112     |
| TIER 1 | 3,627     |
| TIER 2 | 805       |
| TIER 3 | 422       |

📌 *TIER 0 and TIER 1 dominate. TIER 2 and TIER 3 offer potential upselling opportunities.

### 💸 Transaction Summary
- **Total Internal Transfers:** ₦409,831,424.90  
- **Total Inward Transfers:** ₦1,209,860,988.71  
- **Total Outward Transfers:** ₦1,302,802,020.16  

📌 *Outward transfers slightly exceed inward flows. Internal transfers make up a smaller portion.

---

## 📊 Dashboard Features
- **Customer Overview Dashboard (Sheet: 'Dashboard'): Visualizes account statuses, tier distributions, and country insights.
- **Transaction Overview Dashboard (Sheet: 'Dashboard 2'): Highlights total values by type, transaction volume by day and month, and filters to explore behavior over time.

Both dashboards include:
- Interactive slicers (country, status, tier)
- Timeline filters for monthly analysis

---

## 🚀 Future Enhancements
- Integrate with Power BI for extended drill-down capabilities
- Automate monthly updates using Power Query
- Add segmentation analysis (e.g., age groups)

---

## 🧠 Learnings

This project enhanced my Excel proficiency in:
- Cleaning and preparing structured data
- Using advanced formulas and dynamic references
- Building interactive dashboards with PivotTables
- Drawing actionable insights from raw transactional data
