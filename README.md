Vendor Performance & Profitability Analysis
Project Overview

This project analyzes vendor-level sales, procurement, and profitability metrics to evaluate operational efficiency and supplier performance in the retail/wholesale domain.

The objective is to identify underperforming brands, assess vendor dependency risks, optimize bulk purchasing strategies, and improve inventory turnover using data-driven insights.

Business Objectives

Identify underperforming brands requiring pricing or promotional adjustments

Determine top vendors contributing to total sales and gross profit

Analyze cost advantages from bulk purchasing

Evaluate inventory turnover efficiency

Compare profitability models of high vs low-performing vendors

Data Preparation & Filtering

Removed transactions with Gross Profit ≤ 0

Excluded records with Profit Margin ≤ 0

Eliminated entries with Total Sales Quantity = 0

Cleaned inconsistent and missing values

Standardized financial and numeric columns

Dataset Size: 10,692 vendor records

Key Analytical Findings
🔹 1. Vendor Dependency Risk

Top 10 vendors contribute 65.69% of total purchases

Indicates over-reliance on limited suppliers

Suggests need for diversification strategy

🔹 2. Bulk Purchasing Impact

Large volume buyers receive 72% lower unit costs

Bulk strategy significantly improves cost efficiency

Encourages procurement optimization

🔹 3. Inventory Inefficiency

Unsold inventory capital: $2.71M

Slow-moving inventory reduces liquidity and increases holding costs

Highlights need for improved stock management

🔹 4. Profit Margin Analysis
Vendor Group Mean Profit Margin
Top Vendors 31.17%
Low Vendors 41.55%

Low-performing vendors maintain higher margins but lower sales volume, indicating potential pricing inefficiencies or limited market reach.

Hypothesis testing confirms a statistically significant difference between the two vendor groups.

5.  Correlation Insights

Strong correlation (0.999) between Purchase Quantity and Sales Quantity → Efficient inventory flow

Weak correlation between Purchase Price and Profit → Price variation alone does not drive profitability

Negative correlation between Profit Margin and Sales Price → Competitive pricing may compress margins

Dashboard Features

Vendor-wise Profitability Breakdown

Top & Bottom Vendor Analysis

KPI Cards (Sales, Profit, Margin, Turnover)

Bulk Purchase Cost Comparison

Inventory Turnover Analysis

Interactive Filters & Drill-through Views

Tools Used

Power BI

DAX

Statistical Analysis

Data Cleaning & Transformation

Hypothesis Testing

Business Impact

This analysis enables:

Improved vendor diversification strategy

Optimized bulk purchasing decisions

Reduced inventory holding costs

Enhanced pricing and margin optimization

Data-driven procurement planning

Repository Structure
vendor-performance-analysis-powerbi/
│
├── data/
├── dashboard/
├── report/
├── images/
└── README.md
