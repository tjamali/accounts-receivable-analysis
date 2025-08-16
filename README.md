# Accounts Receivable & Payment Pattern Analysis

This mini-project analyzes accounts receivable (AR) data to uncover **payment patterns, customer risk profiles, and receivable health**.  
The analysis covers data cleaning, duplicate detection, payment behavior metrics, and finance-focused visualizations.

---

## Project Overview
Managing receivables efficiently is crucial for liquidity and working capital.  
This notebook demonstrates how to:
- Clean and prepare AR datasets (remove duplicates, normalize customer names, handle missing dates).
- Calculate **days late**, **aging buckets**, and **DSO (Days Sales Outstanding)**.
- Identify **high-risk customers** and **late-payment trends**.
- Visualize receivable health with **finance dashboards**.

---

## Dataset
The dataset used in this project is publicly available on Kaggle: [Payment Date Dataset](https://www.kaggle.com/datasets/rajattomar132/payment-date-dataset). It is provided for non-commercial and educational purposes, making it suitable for exploratory data analysis and demonstration projects like this one.

---

## Key Insights
- **Payment Behavior**: Most invoices clear within 20 days, but long-tail late payments exist up to ~180 days.  
- **Pareto Effect**: A handful of customers drive the majority of late receivable exposure.  
- **Aging Trends**: The mix of receivables across aging buckets shifts month to month, revealing seasonal or structural risk.  
- **DSO Trend**: Average collection time hovers around 18 days but fluctuates across months and business codes.  

---

## Visualizations
The project includes several **finance-focused plots**:
1. **Days Late Distribution** (normal range vs long-tail).
2. **Pareto of Late Amounts** (top customers driving exposure).
3. **Stacked Aging Buckets Over Time**.
4. **Business-Code Boxplots** with exposure overlay.
5. **Interactive DSO Trend** (Plotly).
