# Madrid Housing Market Analysis – Power BI Project

## 📌 Project Overview
This project analyzes housing market data of Madrid using Power BI.
The goal is to understand property price trends, analyze the impact of
property features, and identify top investment opportunities using
interactive dashboards.

---

## 🧾 Dataset Used
- File Name: houses_Madrid.csv
- Data includes property prices, house types, features (pool, garden,
  new development), area details, and loan interest rates.

---

## 🛠 Tools & Technologies
- Power BI Desktop
- Power Query (Data Cleaning & Transformation)
- DAX (Measures & Calculations)

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning & Preparation
- Data imported using Power Query
- Column data types verified
- Blank values kept as-is to preserve original data
- No duplicate flag available, so dataset used as provided

---

### 2. Price Analysis by Property Features
- Analyzed average buy price based on:
  - has_pool
  - is_new_development
- Found that properties with pools generally have higher prices

---

### 3. Market Segmentation by House Type
- Properties segmented using house_type_id
- Calculated Average Price per Square Meter
- Áticos showed the highest price per sqm

---

### 4. Investment Opportunity Analysis
- Created an Investment Score using:
  - Built-up area (sq_mt_built)
  - Loan interest rate (loan_int_rate)
- Applied Top N filter to identify Top 5 investment opportunities

---

### 5. Interactive Dashboard
- Created an interactive dashboard with:
  - KPI Cards (Average Buy Price, Avg Price per Sqm, Total Listings, Investment Score)
  - Bar Charts for feature-based price comparison
  - Tables for segmentation and investment analysis
- Added slicers for:
  - has_pool
  - has_garden
  - is_new_development
  - is_exterior

---

## 📊 Key Insights
- Properties with pools have higher average prices
- New developments show moderate pricing
- Áticos are the most expensive per square meter
- Casa o chalet frequently appears in top investment opportunities

---

## 📁 Project Output
- Power BI Interactive Dashboard
- 6–7 Slide Presentation
- GitHub README Documentation

---

## 👤 Author
**Name:** Shahroj  
**Batch:** B9  

---

## ✅ Conclusion
This project demonstrates how Power BI can be used to analyze real estate
data effectively. Interactive visuals and DAX calculations help derive
meaningful insights for market analysis and investment decisions.
