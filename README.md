# 🛒 ShopKart D2C — E-Commerce Sales & Customer Analytics (2024–2025)

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Excel-Analytics%20Dashboard-217346?style=for-the-badge&logo=microsoft-excel" alt="Excel Analytics Dashboard"/>
  <img src="https://img.shields.io/badge/Business-Intelligence-0F5C9B?style=for-the-badge" alt="Business Intelligence"/>
  <img src="https://img.shields.io/badge/Data-Analysis-FF7F50?style=for-the-badge" alt="Data Analysis"/>
</p>

An executive-grade retail analytics dashboard and relational data model built in Microsoft Excel. This project evaluates multi-channel sales performance, customer retention dynamics, regional fulfillment efficiency, and marketing spend efficiency across 4,800+ transactions spanning 2024–2025.

---

## 📌 Business Overview & Objectives
ShopKart is a direct-to-consumer (D2C) brand retailing across multi-channel marketplaces (**Amazon, Flipkart, Myntra, Nykaa**, and direct **Website**). 

### Key Business Challenges Addressed:
1. **Channel & Category Profitability**: Identifying which sales channels deliver sustainable operating margins after factoring discounts, COGS, and return shipping costs.
2. **Customer Retention**: Tracking repeat vs. first-time buyer acquisition trends over 24 continuous months.
3. **Logistics & Delivery Operations**: Assessing fulfillment speed benchmarks (Express $\le$2 days vs. Delayed 5+ days) and their impact on product return rates.
4. **Marketing Spend Efficiency**: Measuring regional advertising spend ROI and correlation to net state revenue.

---

## 🛠️ Technical Stack & Excel Features Applied
* **Advanced Lookups & Data Modeling**:
  * Multi-criteria aggregation via `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`.
  * Normalized data structuring using `INDEX/MATCH` across dimensional tables (`Products`, `State`, `Market`).
  * Dynamic timeline logic using `EDATE` and date serial boundaries.
* **KPI & Performance Engine**:
  * Decoupled calculation engine (`Analysis` sheet) driving clean, presentation-ready dashboard cards.
  * Real-time dynamic header generation (`="Showing: " & selYear & " • Region: " & selRegion ...`).
* **Statistical & Trend Modeling**:
  * Ordinary Least Squares linear regression (`SLOPE`, `INTERCEPT`, `RSQ`, `CORREL`) analyzing marketing spend sensitivity.
  * Dynamic rank scoring and tie-breaking algorithms for product leaderboards.
* **Interactive UX / UI Design**:
  * Standardized dropdown validation parameters (`selYear`, `selRegion`, `selChannel`, `selCategory`, `selTopN`).
  * Custom number formatting (`₹#,##0` and `₹0.0,"L"` for lakh scale readability).

---

## 📊 Visual Insights & Findings

### 1. Net Revenue by Sales Channel
![Net Revenue by Sales Channel](channel_revenue.png)
* **Finding**: Third-party marketplaces (**Amazon** and **Flipkart**) account for the highest gross order volumes, while direct **Website** and **Myntra** channels drive substantial high-margin revenue.

### 2. Net Revenue by Product Category
![Net Revenue by Product Category](category_revenue.png)
* **Finding**: **Apparel** and **Footwear** dominate total gross sales, whereas **Skincare** and **Wellness** show high steady-state recurring orders.

### 3. Regional Performance Breakdown
![Net Revenue by Region](region_revenue.png)
* **Finding**: The **North** and **South** regions lead total regional contributions, followed closely by West and East fulfillment hubs.

---

## 📈 KPI Coverage & Scorecard

| KPI Category | Description | Business Value |
|---|---|---|
| **Revenue** | Total sales generated across channels and time | Measures top-line growth |
| **Profit** | Net earnings after COGS and shipping | Evaluates bottom-line efficiency |
| **Profit Margin** | Profit as a percentage of net revenue | Shows pricing and cost effectiveness |
| **Orders** | Total completed order count | Indicates demand volume |
| **Average Order Value** | Average transaction size | Supports customer value analysis |
| **Return Rate** | Percentage of orders returned | Highlights product or fulfillment risk |
| **Average Delivery Days** | Average days to fulfill order | Reflects operational performance |

---

## Dashboard Preview

### Main Dashboard
![ShopKart Executive Dashboard](shopkart-dashboard-main.png)

### Analytics Overview
![ShopKart Analytics Overview](shopkart-analytics-overview.png)

---

## 📁 Repository Files
* `Ecommerce_Sales_Data_Analyst_Project.xlsx` — The complete interactive project workbook featuring the Executive Dashboard, Analysis Engine, and Data Models.
* `RAW_Ecommerce_Sales_Data.xlsx` — Initial raw unstructured data exports.
* `channel_revenue.png`, `category_revenue.png`, `region_revenue.png` — Visual analytical exports.

---

## 📥 How to Explore the Project
1. Download `Ecommerce_Sales_Data_Analyst_Project.xlsx` from this repository.
2. Open in **Microsoft Excel (Microsoft 365 or Excel 2021+)**.
3. Navigate to the **`Dashboard`** tab to test interactive slicers, year/region filters, and dynamic scorecard metrics.

---

## Connect
- **LinkedIn**: [Lakshay Aggarwal](https://www.linkedin.com/in/lakshay-aggarwal-130a33236/)
- **Email**: lakshay.aggar@gmail.com
- **GitHub**: [345lakshayaggarwal-prog](https://github.com/345lakshayaggarwal-prog)

<p align="center">
  <strong>Built for business impact. Designed to stand out.</strong>
</p>
