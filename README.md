# Fleet Management Profitability & Operational Efficiency Analysis

## Executive Summary

This project analyzes the profitability and operational efficiency of a fleet management business operating between 2018–2019. The analysis focuses on identifying cost inefficiencies, revenue leakage, fleet misallocation, and customer segmentation issues that significantly impact overall profitability.

The objective was to transform raw operational data into actionable business insights using Power BI, Excel, Power Query, and DAX.

Key outcomes include:
- Identification of 3 major profitability drivers causing margin leakage
- Discovery of fixed-cost structural inefficiency during low-demand seasons
- Detection of vehicle-type misallocation leading to negative gross margins
- Identification of customer segmentation imbalance affecting capacity utilization

---

## Business Problem

The company is facing declining profitability despite stable operational activity.

Key challenges:
- High fixed operational costs regardless of demand fluctuations
- Poor vehicle-to-route assignment strategy
- Uneven customer profitability distribution
- Inefficient fleet utilization across seasonal cycles

Why it matters:
These issues directly reduce gross margin, increase cost per kilometer, and prevent scalable growth.

---

## Project Objectives

- Analyze cost structure and identify fixed vs variable cost impact
- Evaluate fleet utilization efficiency across seasons
- Identify profitability by vehicle type and route
- Segment customers based on revenue contribution
- Provide actionable recommendations to improve margins

---

## Dataset Overview

- **Data Source:** Real Business Operational Dataset
- **Time Period:** 2018–2019
- **Total Orders:** 92.1K
- **Total Customers:** 44K
- **Active Customers:** 8K
- **Fleet Size:** 31 Trucks
- **Active Trucks:** 23

### Key Fields:
- Revenue per order
- Cost per kilometer
- Truck type classification (BOX, TRAILER, TRACTOR, SEMI-TRAILER)
- Customer segmentation
- Fleet utilization metrics
- Monthly operational costs

### Limitations:
- Limited external macroeconomic variables
- No fuel price fluctuation index
- Partial driver behavior tracking

---

## Methodology

### 1. Business Understanding
Defined profitability loss areas across fleet operations, customer mix, and seasonal demand.

### 2. Data Collection
Aggregated operational data from fleet, cost, and customer tables.

### 3. Data Cleaning
Handled missing values, inconsistent route records, and duplicate transactions.

### 4. Data Transformation
Built calculated fields in Power Query and DAX for:
- Cost per km
- Revenue per truck
- Fleet utilization rates

### 5. Exploratory Data Analysis (EDA)
Identified seasonal revenue fluctuations and cost concentration patterns.

### 6. Root Cause Analysis
Developed structured RCA framework across:
- Fleet utilization
- Vehicle-type efficiency
- Customer segmentation

### 7. Dashboard Development
Built interactive Power BI dashboards:
- Cost Analysis
- Vehicle Performance
- Customer Segmentation

### 8. Insights Generation
Extracted profitability bottlenecks and operational inefficiencies.

### 9. Recommendations
Designed actionable strategies for cost reduction and revenue optimization.

---

## Tools & Technologies

- Power BI
- Excel
- Power Query
- DAX
- SQL (data exploration)
- Data Modeling techniques

---

## Key Findings

### Scenario 1 — Fixed Cost Overload in Low Demand Seasons
- Fixed costs represent **88.8% of total costs**
- Loss-making months: May (-28.9%), June (-24.3%)
- Severe margin compression due to idle fleet capacity

### Scenario 2 — Vehicle Misallocation
- BOX trucks: -16.5% GM
- TRAILER trucks: -5.3% GM
- TRACTOR trucks: +25.4% GM (most efficient)
- 64.5% of fleet operating in low or negative margin segments

### Scenario 3 — Customer Imbalance
- 2,824 low-tier customers generate only 1.9% revenue
- High-tier customers generate 5x revenue per order
- Low-value trips consume high operational capacity

---

## Recommendations

- Implement seasonal fleet parking strategy (Apr–Jul)
- Shift high-value routes to TRACTOR & SEMI-TRAILER trucks only
- Introduce minimum order value policy ($80+ threshold)
- Retire or lease underperforming BOX units
- Build route-to-vehicle optimization model

---

## Business Impact

If implemented:
- Estimated **12–18% reduction in operational costs**
- **15–22% improvement in gross margin**
- Increased fleet utilization efficiency by 20%
- Improved revenue per truck by optimizing route allocation

---

## Dashboard Features

- KPI tracking: Revenue, Cost, Margin, Utilization
- Seasonal performance analysis
- Vehicle-type profitability breakdown
- Customer segmentation view
- Interactive filters (time, vehicle type, customer tier)

---

## Project Structure
