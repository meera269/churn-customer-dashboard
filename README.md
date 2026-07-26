
# Customer Churn Dashboard

An Excel-based dashboard analyzing churn behavior across 10,000 bank customers, 
with engineered features and KPI/chart visualizations.

## 📊 Overview
- **Total Customers:** 10,000
- **Total Churned:** 2,037 (20.37% churn rate)
- **Avg Balance (Churned):** $91,108 vs **Avg Balance (Retained):** $72,745
- **Avg Credit Score (Churned):** 645 vs **Avg Credit Score (Retained):** 652
- **Avg Age (Churned):** 44.8 vs **Avg Age (Retained):** 37.4

## 🗂️ Sheets
- **Dashboard** – KPI cards + 8 charts summarizing churn trends
- **Data** – Raw customer data (CreditScore, Geography, Gender, Age, Balance, etc.) 
  plus engineered features: `BalanceSalaryRatio`, `AgeGroup`, `TenureGroup`, 
  `CreditScoreBand`, `EngagementScore`
- **Summary** – Churn rate breakdown by Geography, Gender, and other segments

## 🔍 Key Insight
Germany shows the highest churn rate (~32%) compared to France (~16%) and 
Spain (~17%), despite having higher average balances — suggesting geography-specific 
retention issues worth investigating further.

## 🛠️ Tools Used
Microsoft Excel — PivotTables, Charts, Feature Engineering, KPI Dashboard Design
