# 💳 Credit Card Financial Dashboard

An end-to-end **Power BI + SQL** business intelligence project analyzing credit card customer and transaction data — built to simulate a real-world financial reporting workflow, from raw data to stakeholder-ready dashboards.

---

## 📌 Overview

This project connects a SQL database to Power BI and transforms raw credit card data into two interactive dashboards, covering both **transaction-level performance** and **customer-level insights**. The goal: turn scattered raw data into clear, decision-ready reporting — the kind a finance or product team could actually use to track weekly performance and understand their customer base.

---

## 📊 Dashboard 1: Credit Card Transaction Report

**Key Metrics:** Revenue (57M) · Transaction Amount (46M) · Interest Earned (7.98M) · Transaction Count (667K)

**What it shows:**
- Revenue and transaction count trends across quarters, visualized with a dual-axis combo chart
- Revenue breakdown by **card category** (Blue, Silver, Gold, Platinum) — Blue cards alone account for ~83% of total revenue (₹47.2M of ₹56.5M)
- Revenue segmented by **expenditure type** (Bills, Entertainment, Fuel, Grocery, Food, Travel)
- Revenue by **education level** and **customer job** (Businessman, White-collar, Self-employed, Govt, Blue-collar, Retirees)
- Fully interactive with slicers for Card Category, Quarter, Gender, and Customer Segment (Low/Medium/High)

---

## 👥 Dashboard 2: Credit Card Customer Report

**Key Metrics:** Revenue (57M) · Income (588M) · Interest (7.98M) · Avg. Credit Score Summary (3.19)

**What it shows:**
- Weekly revenue trend split by gender
- Revenue by **age group** (20–30 through 60+), highlighting where the strongest customer segments sit
- Revenue by **top 5 states** (TX, NY, CA, FL, NJ)
- Revenue by **marital status**, **income group** (Low/Medium/High), **dependent count**, and **education level**
- A payment-method treemap (Swipe / Chip / Online)
- Customer job-level breakdown table showing Revenue, Interest Earned, and Income side-by-side for direct comparison

---

## 🛠️ Tools & Techniques Used

| Category | Details |
|---|---|
| **Data Source** | SQL database |
| **BI Tool** | Power BI Desktop |
| **Data Cleaning** | Power Query — null handling, type corrections, categorical standardization |
| **DAX** | `SWITCH` for age/income bucketing, `CALCULATE` + `FILTER` for week-over-week revenue comparisons |
| **Visuals** | KPI cards, combo charts, treemaps, horizontal bar charts, line charts, cross-filterable tables |
| **Interactivity** | Slicers for Card Category, Quarter, Gender, Income Segment, and Week |

---

## 🎯 What This Project Demonstrates

- Connecting Power BI directly to a SQL backend rather than static file imports
- Writing real DAX logic for time-based comparisons (week-over-week % change) and custom segmentation
- Designing dashboards with a consistent, minimal color palette so KPIs stay the focus, not the visuals
- Structuring a BI project the way a real analyst would: separate transaction-level and customer-level views for different stakeholder needs

---

## 👤 About Me

Built as a hands-on portfolio project to strengthen practical BI development skills — going beyond tutorials to actually connect, clean, model, and present financial data the way a Data/Business Analyst would in a real role.
