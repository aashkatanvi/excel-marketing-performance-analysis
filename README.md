# Marketing Performance Analysis

An end-to-end marketing analytics project evaluating 300+ digital marketing campaigns across Google, Meta, LinkedIn, and YouTube to identify high-performing channels, regional conversion patterns, and areas of efficiency leakage.

The project combines data preparation, KPI development, analytical modeling, and interactive dashboarding to translate campaign-level data into actionable marketing insights.

## Business Problem

Marketing teams need to understand which channels are generating efficient returns and where campaign spend is underperforming.

This analysis focuses on:

- Which platforms generate the strongest financial returns?
- Where is marketing spend becoming inefficient?
- Which regions have stronger conversion performance?
- How do platforms compare across ROI, ROAS, CPC, conversion rate, and cost per conversion?
- Where could budget allocation be improved?

## Tools & Technologies

- **Power BI** — Data modeling, DAX measures, interactive dashboarding
- **Power Query** — Data cleaning and transformation
- **Excel** — Source data preparation and initial analysis
- **DAX** — KPI and performance metric calculations
- **GitHub** — Project documentation and version control

## Analytical Approach

### 1. Data Preparation
Cleaned and transformed campaign-level marketing data to create an analysis-ready dataset.

Key fields included:

- Platform
- Objective
- Region
- Device
- Ad Type
- Impressions
- Clicks
- Conversions
- Spend
- Revenue
- Engagement metrics

### 2. KPI Development

Developed business-focused measures including:

- Total Revenue
- Total Spend
- ROI %
- ROAS
- Total Conversions
- Conversion Rate
- CPC
- Cost per Conversion

### 3. Performance Analysis

Compared marketing performance across:

- Digital platforms
- Geographic regions
- Conversion efficiency
- Campaign investment
- Revenue generation
- Customer acquisition efficiency

### 4. Dashboard Development

Built an interactive Power BI dashboard with:

- Executive KPI overview
- Spend vs Revenue analysis
- Conversion Rate by Region
- Conversion Rate by Platform
- Platform performance matrix
- Interactive filters for Objective, Region, Ad Type, Platform, and Device

## Key Findings

### Platform Performance

**Google was the strongest-performing platform**, generating:

- **812% ROI**
- **9.12 ROAS**
- **3.42% conversion rate**
- **₹117.19 cost per conversion**

Google generated substantially stronger returns than the other platforms while maintaining the lowest cost per conversion.

### Efficiency Leakage

**YouTube and LinkedIn showed the weakest financial efficiency.**

YouTube recorded:

- **16% ROI**
- **1.16 ROAS**
- **₹795.29 cost per conversion**

LinkedIn recorded:

- **38% ROI**
- **1.38 ROAS**
- **₹769.49 cost per conversion**

Both platforms therefore require closer scrutiny of campaign targeting, spend allocation, and conversion efficiency.

### Regional Performance

Conversion performance varied across regions.

**Central recorded the highest conversion rate at 3.09%**, followed by South and East at **2.62%**.

The regional comparison provides an additional dimension for evaluating where marketing investment is converting more efficiently.

## Business Recommendations

Based on the analysis:

1. **Prioritize high-return channels such as Google** where the data supports stronger ROI and lower acquisition costs.
2. **Review LinkedIn and YouTube spending**, particularly campaigns producing low returns relative to acquisition cost.
3. **Investigate regional differences in conversion performance** before reallocating budget geographically.
4. Use **conversion efficiency alongside ROI** when evaluating campaigns to avoid optimizing solely for revenue.
5. Continuously monitor **cost per conversion, conversion rate, and ROAS** when making budget allocation decisions.

## Dashboard

![Marketing Performance Dashboard](images/marketing-performance-dashboard.png)

The Power BI dashboard provides an interactive view of platform and regional performance, allowing users to filter results by objective, region, ad type, platform, and device.

## Project Structure

```text
marketing-performance-analysis/
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
