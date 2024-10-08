# 📊 Marketing Campaign Analysis SQL Project

## Overview
This project is designed to analyze marketing campaign data from Facebook and Google Ads using SQL. The main objective is to transform raw data into actionable insights by calculating key performance indicators (KPIs) such as CPC, CPM, CTR, and ROMI. The analysis also includes identifying top-performing campaigns and ad sets, analyzing UTM campaigns, tracking monthly performance trends, and segmenting performance by various dimensions.

## 🛠️ Project Highlights
- **SQL CTEs and Window Functions:** Leveraged Common Table Expressions (CTEs) and window functions to organize complex queries and perform trend analyses.
- **Data Aggregation:** Aggregated key metrics such as spend, impressions, clicks, and conversion values by ad date, campaign, ad set, and media source.
- **Campaign and Ad Set Analysis:** Identified top-performing campaigns and ad sets based on ROMI and other KPIs, while also filtering out underperforming campaigns.
- **UTM Campaign Analysis:** Analyzed UTM campaign performance by decoding URL parameters and calculating KPIs for each campaign.
- **Monthly KPI Tracking:** Tracked month-over-month changes in key metrics, providing insights into campaign performance trends over time.
- **Performance Segmentation:** Segmented data by media source, campaign, and ad set to identify the most effective segments.

## 📈 Key Metrics Calculated
- **CPC (Cost Per Click):** Measures the average cost per click for each campaign.
- **CPM (Cost Per Thousand Impressions):** Indicates the cost per 1,000 ad impressions.
- **CTR (Click-Through Rate):** Percentage of impressions that resulted in clicks.
- **ROMI (Return on Marketing Investment):** Measures the return generated by campaigns relative to the amount spent.

## 🧑‍💻 How to Use
1. Clone this repository.
2. Run the provided SQL scripts in your preferred SQL environment (e.g., PostgreSQL).
3. Review the results to gain insights into the performance of marketing campaigns.

## 📝 Analysis Breakdown

### 1. Campaign Performance Analysis
**Objective:** Calculate KPIs such as CPC, CPM, CTR, and ROMI for each campaign on a daily basis.

**Query:** Aggregates spend, impressions, clicks, and value for each campaign and calculates key performance metrics.


### 2. Top Campaign and Ad Set Identification
**Objective:** Identify the top-performing campaigns and ad sets based on ROMI, filtering out low-spending campaigns.

**Query:** Filters campaigns and ad sets with spend over 500,000 and ranks them by ROMI.
														as g_and_f

### 3. UTM Campaign Analysis
**Objective:** Analyze the performance of campaigns based on UTM parameters in the URL.

**Query:** Decodes UTM parameters and calculates KPIs for each campaign.


### 4. Monthly Difference Analysis
**Objective:** Track the month-over-month changes in CPC, CPM, CTR, and ROMI for each UTM campaign.

**Query:** Calculates the percentage difference in performance metrics from one month to the next.



### 5. Campaign and Ad Set Trend Analysis
**Objective:** Identify trends in spend, impressions, clicks, and value over time for specific campaigns and ad sets.

**Query:** Calculates the month-over-month changes in performance metrics for each campaign and ad set.



### 6. Performance Segmentation Analysis
**Objective:** Segment data by campaign, ad set, and media source to identify the highest-performing segments.

**Query:** Aggregates performance metrics for each segment and ranks them by ROMI.

## 🚀 Results
- Identified the most efficient campaigns and ad sets with the highest ROMI.
- Compared the performance of campaigns across different months to identify trends.
- Segmented campaign performance by media source, campaign, and ad set, highlighting areas for optimization in future campaigns.
