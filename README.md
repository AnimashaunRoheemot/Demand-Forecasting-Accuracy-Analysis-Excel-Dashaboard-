# Demand Forecasting Accuracy Analysis (Excel Dashboard)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Project Objectives](#project-objectives)
4. [Dataset Description](#dataset-description)
5. [Tools Used](#tools-used)
6. [Data Preparation & Feature Engineering](#data-preparation--feature-engineering)
7. [KPIs Defined](#kpis-defined)
8. [Business Questions & Analysis](#business-questions--analysis)
9. [Dashboard Overview](#dashboard-overview)
10. [Key Insights](#key-insights)
11. [Recommendations](#recommendations)
12. [How to Use This Project](#how-to-use-this-project)

---

## Project Overview
This project analyzes demand forecasting accuracy in a retail environment using historical sales data. The objective is to evaluate forecast performance, identify error patterns, and highlight areas where forecasting improvements can reduce inventory imbalance and improve profitability.

---

## Business Problem
Retailers frequently experience stockouts and excess inventory due to inaccurate demand forecasts. Despite having access to historical sales data, forecasting errors persist, leading to inefficiencies in inventory management and lost revenue opportunities.

---

## Project Objectives
- Evaluate the accuracy of demand forecasts.
- Identify forecast error patterns across products, categories, and time.
- Measure the impact of forecasting inaccuracies on inventory efficiency.
- Provide actionable recommendations to improve forecasting performance.

---

## Dataset Description
The dataset contains **10,000+ records** with **15 columns**, including:

- Product ID  
- Product Name  
- Category  
- Sales Date  
- Units Sold  
- Sale Price  
- Discount Applied  
- Forecasted Demand  
- Actual Demand  
- Inventory Level  
- Minimum Stock Level  
- Lead Time  
- Stockout Indicator  
- Supplier ID  
- Supplier Reliability  

---

## Tools Used
- **Microsoft Excel**
  - Data cleaning and transformation  
  - Pivot tables and calculated fields  
  - Interactive dashboard creation  

---

## Data Preparation & Feature Engineering
The following steps were performed:

- Reviewed the business brief to understand analysis requirements.
- Duplicated the dataset to preserve raw data.
- Checked for null values and corrected data types.
- Converted date fields to proper date format.
- Removed unnecessary columns.
- Created derived columns:
  - Month  
  - Year  
  - Forecast Error  
  - Absolute Error  
  - Mean Absolute Percentage Error (MAPE)  
  - Forecast Accuracy Level  

---

## KPIs Defined
Three key performance indicators were used to evaluate forecast accuracy:

- **Total MAPE:** 16%  
- **Forecast Bias:** 3% (slight over-forecasting)  
- **Products with High Forecast Error:** 26%  

---

## Business Questions & Analysis

### 1️⃣ Are forecasts accurate across categories?
- **Metric:** Forecasted vs Actual Demand by Category  
- **Insight:** Forecasted demand is consistently higher than actual demand across all categories, indicating a slight over-forecasting trend.

### 2️⃣ Which categories are hardest to forecast?
- **Metric:** Average MAPE by Category  
- **Insight:** Forecast accuracy is consistent across categories (~16%), suggesting forecasting challenges are driven by product-level factors.

### 3️⃣ Are forecast errors consistent over time?
- **Metric:** Average Absolute Error by Month  
- **Insight:** Forecast errors remain stable throughout the year, indicating systematic rather than seasonal inaccuracies.

### 4️⃣ How is forecast accuracy distributed across products?
- **Metric:** Forecast Accuracy Level Distribution  
- **Insight:** 26% of products fall into the low-accuracy group and contribute most to overall forecast error.

---

## Dashboard Overview
The Excel dashboard includes:
- 3 KPI cards (MAPE, Forecast Bias, High Error Products)
- 4 analytical visuals
- Interactive slicer for product-level exploration

### Dashboard Preview

![Demand Forecasting Dashboard](https://github.com/AnimashaunRoheemot/Demand-Forecasting-Accuracy-Analysis-Excel-Dashaboard-/blob/main/Forecast%20and%20demand%20accuracy.png)

---

### Key Insights
- Overall forecast accuracy is moderate.
- Slight over-forecasting bias exists.
- Forecast errors are consistent across time and categories.
- A subset of products drives most forecasting inaccuracies.

---

### Recommendations
- Prioritize high-error products for forecast refinement.
- Perform regular forecast calibration to reduce bias.
- Segment products by forecast accuracy.
- Monitor forecast performance monthly using MAPE and bias.

---
### How to Use This Project
1. Download the Excel dashboard file.
2. Use slicers to explore forecast accuracy by product.
3. Review KPIs and visuals to understand forecasting performance.
4. Refer to the recommendation report for improvement strategies.
