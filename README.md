# 📊 Amazon Sales Overview

## ✅ Objective
To explore sales data from Amazon, identifying key trends, category performance, revenue distribution, and sales behavior across months and shipping types to derive actionable business insights.

---

## 🧰 Tools & Libraries Used
- **Pandas & NumPy**: For data manipulation and transformation  
- **Matplotlib & Seaborn**: For visualizing sales performance  
- **Scikit-learn (StandardScaler)**: For normalization tasks  
- **Statsmodels**: Imported for future statistical modeling  

---

## 🧹 Data Cleaning & Preparation
- Parsed dates using `pd.to_datetime()`  
- Dropped irrelevant columns: `"New"` and `"PendingS"`  
- Extracted `Month` and `Year` from the `Date` column  
- Exported cleaned dataset as `"Clean Data"`  

---

## 📈 Key Analysis & Findings

### 📅 Monthly Sales Overview
- **April** recorded the **highest revenue** at ~$28.8M  
- **May** followed with ~$26.2M  
- **March** had the **lowest revenue** (~$101.7K), suggesting a potential issue (e.g., low inventory, poor promotions)

### 📦 Shipment Service Impact
Analysis of shipping service preferences and effects on revenue is upcoming.

---

## 📉 Insights
- Sales peak in **Q2 (April–May)** suggests seasonal demand or effective promotions.  
- **March’s drop** indicates possible operational issues or data inconsistencies.  
- Month-wise grouping revealed clear revenue trends.

---

## 📌 Recommendations
1. **Investigate March’s Drop** — Review inventory, customer feedback, and promotions.  
2. **Double Down on Q2 Campaigns** — Boost campaigns in April–May to maximize peak season.  
3. **Analyze Shipment Status** — Evaluate customer satisfaction and shipping performance in future phases.

