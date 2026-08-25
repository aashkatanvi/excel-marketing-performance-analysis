# Marketing Performance Analytics

An end-to-end marketing analytics project evaluating 300+ digital marketing campaigns across Google, Meta, LinkedIn, and YouTube to identify high-performing channels, regional conversion patterns, and areas of efficiency leakage.

The project covers data preparation, KPI development, analytical modeling, DAX-based metric calculation, and interactive Power BI dashboarding to translate campaign-level data into actionable marketing insights.

## Business Problem

Marketing teams need to understand which channels are generating efficient returns, where acquisition efficiency is weakening, and whether performance varies across regions.

This analysis addresses:

- Which platforms generate the strongest financial returns?
- Where is marketing spend becoming inefficient?
- Which regions demonstrate stronger conversion performance?
- How do platforms compare across ROI, ROAS, conversion rate, CPC, and cost per conversion?
- Where could marketing budget allocation be improved?

## Tools & Technologies

- **Power BI** — Data modeling, interactive dashboarding, KPI reporting
- **Power Query** — Data cleaning, transformation, and preparation
- **DAX** — Business metrics and analytical measures
- **Excel** — Source data handling and supporting analysis
- **GitHub** — Project documentation and version control

## Analytical Approach

### 1. Data Preparation

Prepared campaign-level marketing data for analysis by cleaning and transforming fields related to campaign performance, investment, engagement, and conversion.

Key dimensions included:

- Platform
- Objective
- Region
- Device
- Ad Type

Key performance measures included:

- Impressions
- Clicks
- Conversions
- Spend
- Revenue
- Likes
- Comments
- Shares

### 2. KPI & Metric Development

Developed business-focused measures using DAX to evaluate both financial return and acquisition efficiency:

- Total Revenue
- Total Spend
- ROI %
- ROAS
- Total Conversions
- Conversion Rate
- CPC
- Cost per Conversion

### 3. Performance Analysis

Analyzed campaign performance across:

- Digital platforms
- Geographic regions
- Revenue generation
- Marketing investment
- Conversion efficiency
- Customer acquisition efficiency

The analysis compares platforms using both return-based metrics such as ROI and ROAS and efficiency-based metrics such as conversion rate, CPC, and cost per conversion.

### 4. Interactive Dashboard

Built an interactive Power BI dashboard featuring:

- Executive KPI overview
- Spend vs Revenue by Platform
- Conversion Rate by Region
- Conversion Rate by Platform
- Platform Performance Matrix
- Interactive slicers for Objective, Region, Ad Type, Platform, and Device

The dashboard enables users to move from high-level marketing performance to platform- and region-level efficiency analysis.

## Key Findings

### 1. Google Is the Strongest-Performing Platform

Google significantly outperformed the other platforms across financial and acquisition-efficiency metrics:

- **812% ROI**
- **9.12 ROAS**
- **3.42% Conversion Rate**
- **₹117.19 Cost per Conversion**

Google generated the strongest return while also maintaining the lowest cost per conversion among the four platforms.

### 2. YouTube and LinkedIn Show Significant Efficiency Gaps

YouTube and LinkedIn were the weakest platforms on financial efficiency:

**YouTube**
- **16% ROI**
- **1.16 ROAS**
- **₹795.29 Cost per Conversion**

**LinkedIn**
- **38% ROI**
- **1.38 ROAS**
- **₹769.49 Cost per Conversion**

Their relatively low returns and high acquisition costs indicate areas where campaign targeting, spend allocation, and conversion efficiency should be reviewed.

### 3. Regional Conversion Performance Varies

Conversion performance differed across regions:

- **Central — 3.09%**
- **South — 2.62%**
- **East — 2.62%**
- **North — 2.49%**
- **West — 2.40%**
- **Unknown — 1.98%**

Central recorded the highest conversion rate, while the Unknown region showed the weakest conversion performance.

## Business Recommendations

Based on the analysis:

1. **Prioritize high-return channels such as Google** where stronger ROI and lower acquisition costs are supported by the data.
2. **Review LinkedIn and YouTube spending** to identify campaigns with weak returns and high acquisition costs.
3. **Investigate regional conversion differences** before making geographic budget allocation decisions.
4. Evaluate campaigns using **multiple efficiency metrics**, rather than optimizing solely for revenue or ROI.
5. Continuously monitor **ROAS, conversion rate, CPC, and cost per conversion** when reallocating marketing spend.

## Dashboard

![Marketing Performance Dashboard](images/marketing_performance.png)

The Power BI dashboard provides an interactive view of platform and regional performance, with filters for objective, region, ad type, platform, and device.

## Project Structure

```text
marketing-performance-analytics/
│
├── data/
│   └── marketing_data.csv
│
├── dashboard/
│   └── marketing-performance.pbix
│
├── images/
│   └── marketing-performance-dashboard.png
│
└── README.md
