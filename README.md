# Marketing Performance Analytics — End-to-End Case Study

> **From raw campaign data to business decisions:** data preparation, KPI engineering, analytical modeling, Power BI dashboarding, and performance recommendations.

---

## Business Question

**Which marketing channels generate the strongest returns, and where is efficiency leaking?**

This project analyzes campaign-level marketing data across **Google, Meta, LinkedIn, and YouTube** to evaluate spend efficiency, revenue generation, conversion performance, and cost economics across regions, objectives, devices, and ad types.

The objective is not simply to build a dashboard, but to turn campaign data into **decision-ready performance insights**.

---

## Analytical Workflow

```text
Raw Campaign Data
       ↓
Data Cleaning & Validation
       ↓
Metric / KPI Engineering
       ↓
Exploratory & Comparative Analysis
       ↓
Power BI Data Model & Measures
       ↓
Interactive Dashboard
       ↓
Business Insights & Recommendations
```

### 1. Data Preparation

The campaign dataset was inspected and cleaned before analysis, including:

- Standardizing categorical fields such as platform, region, objective, device, and ad type
- Validating numeric fields and handling inconsistent values
- Removing structural noise and unusable rows
- Preparing a consistent analytical table for downstream reporting

### 2. KPI Engineering

The analysis focuses on business-relevant performance metrics including:

- **Total Spend**
- **Total Revenue**
- **ROI %**
- **ROAS**
- **Total Conversions**
- **Conversion Rate**
- **CPC**
- **Cost per Conversion**

### 3. Power BI Analysis

The cleaned campaign data was modeled in **Power BI** and transformed into an interactive performance dashboard with measures for platform-level efficiency and conversion economics.

The dashboard supports filtering by:

- Platform
- Region
- Objective
- Ad Type
- Device

---

## Dashboard

### Marketing Performance Dashboard

The final dashboard answers four core questions:

1. **Where is marketing spend producing the strongest financial return?**
2. **Which platforms have an efficiency gap?**
3. **How do conversion rates differ across channels?**
4. **What does the platform-level performance matrix imply for budget allocation?**

> The current portfolio-facing dashboard is built in **Power BI**. The repository's earlier Excel dashboard has been superseded by this analytical version.

---

## Key Findings

### Google is the clear efficiency leader

- **812% ROI**
- **9.12 ROAS**
- **2,946 conversions**
- **₹117.19 cost per conversion**

Google generates substantially stronger returns than the other platforms while also maintaining the lowest CPC in the final analytical view.

### Meta is the secondary performance channel

- **200% ROI**
- **3.00 ROAS**
- **961 conversions**
- **₹331.18 cost per conversion**

Meta remains economically viable, but its return profile is materially weaker than Google.

### LinkedIn and YouTube show major efficiency pressure

- LinkedIn: **38% ROI**, **₹769.49 cost per conversion**
- YouTube: **16% ROI**, **₹795.29 cost per conversion**

These channels require tighter targeting, experimentation, or budget scrutiny rather than simply receiving additional spend.

### Overall economics

- **Total Revenue:** ₹5.28M
- **Total Spend:** ₹1.57M
- **Overall ROI:** 235%
- **Overall ROAS:** 3.35
- **Total Conversions:** 5,074
- **Overall Cost per Conversion:** ₹310.20

---

## Business Recommendations

### 1. Protect and scale high-efficiency spend

Prioritize Google for incremental performance budget while monitoring whether marginal returns remain sustainable as spend increases.

### 2. Keep Meta as a complementary performance channel

Maintain Meta as a secondary acquisition channel and optimize targeting, creative, and objective mix before increasing spend aggressively.

### 3. Review LinkedIn and YouTube allocation

Investigate the high cost per conversion and low ROI before allocating additional budget. Test narrower audiences, creative formats, and campaign objectives.

### 4. Use the dashboard for budget decisions, not just reporting

The Power BI dashboard is designed to support interactive channel comparisons and identify where marketing efficiency is improving or deteriorating.

---

## Repository Structure

```text
├── README.md
├── raw_marketing_data.xlsx
├── cleaned_marketing_data.xlsx
├── Excel_Marketing_Analysis_Final.xlsx
└── screenshots/
```

The Excel files are retained as **source/data-preparation artifacts**, not as the primary deliverable. The analytical output has moved to the Power BI layer.

---

## Tools & Skills Demonstrated

**Analytics:**
- Data Cleaning & Validation
- Exploratory Data Analysis
- KPI Design
- Marketing Performance Analysis
- Channel Efficiency Analysis
- Business Recommendation

**BI / Visualization:**
- Power BI
- Power Query
- DAX Measures
- Interactive Slicers
- KPI Cards
- Performance Matrix
- Comparative Visualizations

**Business Concepts:**
- ROI & ROAS
- Conversion Rate
- CPC & Cost per Conversion
- Budget Allocation
- Channel Performance
- Marketing Efficiency

---

## Project Outcome

This project demonstrates an end-to-end analytical workflow: **starting with imperfect campaign data, structuring it for analysis, engineering decision-relevant KPIs, building an interactive Power BI reporting layer, and translating the results into concrete marketing actions.**

The emphasis is on **analytical reasoning and business impact**, not on dashboard decoration alone.

---

### Aashka Tanvi

**Data Analytics | Marketing Analytics | Business Intelligence**
