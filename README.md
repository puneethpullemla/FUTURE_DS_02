# FUTURE_DS_02

# 📈 Social Media Campaign Performance Dashboard – Power BI Project

This is a digital marketing analytics dashboard developed as part of my **Data Science & Analytics Internship** with **Future Interns**.  
The project focuses on creating an interactive, multi-layered **Campaign Performance Dashboard** using ad-level, campaign-level, and regional-level data.

---

## ✅ Task Objective

To design a Power BI dashboard that delivers key insights into:
- 🎯 Campaign performance across various platforms
- 📊 Engagement metrics like CTR, CPC, ROI
- 🌍 Regional effectiveness and device breakdown
- 🧭 Filterable insights by campaign type, region, platform, and time

---

## 📁 Dataset Overview

Three structured datasets were joined and analyzed:

### 1. `marketing campaign performance.xlsx`
Daily-level performance metrics per ad:
- `Campaign Name`, `Ad Name`, `Date`
- `Impressions`, `Clicks`, `Spend`, `Revenue`

### 2. `marketing campaign details.xlsx`
Campaign metadata:
- `Campaign Name`, `Objective`, `Platform`
- `Start Date`, `End Date`

### 3. `region performance.xlsx`
Regional breakdown:
- `Region`, `Device`, `Sales`, `Clicks`, `Conversions`

🔗 **Join Key**: `Campaign Name` (1-to-many relationship across datasets)

---

## 📊 Dashboard Features

- **KPI Cards**:  
  ✅ Total Impressions  
  ✅ Total Clicks  
  ✅ Total Spend  
  ✅ Total Revenue  
  ✅ CTR (Click-Through Rate)  
  ✅ CPC (Cost Per Click)  
  ✅ ROI (Return on Investment)

- **Visuals**:
  - 📊 Bar Chart: Top Campaigns by Revenue
  - 📈 Line Chart: CTR or Spend Over Time
  - 🧭 Matrix: Region vs Device Performance
  - 🥧 Pie Chart: Click Share by Platform
  - 📋 Table: Ad-level performance metrics

- **Filters/Slicers**:
  - 📅 Campaign Date Range
  - 📱 Platform & Campaign Objective
  - 🌍 Region & Device Type
  - 🎯 Campaign Name or Ad Name

---

## 🛠 Tools & Technologies Used

- **Power BI Desktop**
- **Microsoft Excel** (for cleaning & structuring)
- **DAX Measures**:
  - `CTR = DIVIDE(SUM([Clicks]), SUM([Impressions]))`
  - `CPC = DIVIDE(SUM([Spend]), SUM([Clicks]))`
  - `ROI = DIVIDE(SUM([Revenue]) - SUM([Spend]), SUM([Spend]))`
  - `Total Metrics = SUM(...)` for Spend, Revenue, Clicks, Impressions

---

## 🎥 Demo Video

▶️ Watch my dashboard walkthrough here:  
[🔗 https://www.linkedin.com/feed/update/urn:li:activity:7357497683311292417/ ]

---

## 📸 Screenshot

| Dashboard Preview |
|-------------------|
<<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/5c6261fc-e557-40bc-948d-227cf907132f" />
>

---

## 📚 Learnings & Takeaways

- ✅ Building relationships across multiple datasets using Power BI's data model
- ✅ Analyzing real-world marketing KPIs (CTR, CPC, ROI)
- ✅ Designing flexible dashboards with filters by platform, region, device
- ✅ Using DAX to drive smart insights and campaign comparisons

---

## 🔖 Tags

`Power BI` `Digital Marketing` `Social Media Analytics` `Campaign Performance` `CTR` `ROI` `Marketing Dashboard` `Data Visualization` `Internship Project` `Future Interns`
