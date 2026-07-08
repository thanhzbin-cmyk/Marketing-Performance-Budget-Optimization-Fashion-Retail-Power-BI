# Marketing Performance Budget Optimization | Fashion Retail | Power BI
A Power BI dashboard analyzing marketing campaign performance and sales effectiveness for a fashion retail business. The project integrates sales, product, and campaign data to evaluate marketing ROI, optimize advertising budgets, and support data-driven business decisions through Power Query, DAX, and interactive visualizations.
<img width="1784" height="882" alt="image" src="https://github.com/user-attachments/assets/9a546f0b-516f-4e0b-873a-b4a86d5d94fe" />

# Project Overview #

## 1. Background & Business Problem
**Business Context**

Fashion retailers invest heavily in marketing campaigns, but measuring their impact on sales and profitability remains challenging. This project helps evaluate campaign effectiveness and optimize marketing budget allocation through data-driven insights.

**This dashboard aims to help management answer the following business questions:**

- How effectively is the marketing budget generating sales and revenue?
- Which campaigns deliver the highest ROAS and ROI?
- Which products and product categories perform best under paid advertising?
- Where are the bottlenecks in the marketing funnel that reduce conversion efficiency?
- How should marketing budgets be reallocated to maximize business performance?

**The analysis focuses on**
- Sales Performance: Revenue, Orders, AOV, Gross Profit
- Marketing Performance: ROAS, ROI, CPA, CPC, CPM, CTR, CVR
- Business Dimensions: Campaigns, Products, Product Categories, Time
- Marketing Funnel: Impressions, Clicks, Engagement, Inbox, Orders
- Business Goal: Marketing ROI & Budget Optimization

## 2. Project Objective ##
- Evaluate overall marketing performance using sales and advertising KPIs.
- Measure campaign effectiveness through ROAS, ROI, and conversion metrics.
- Identify high-performing products and campaigns for budget optimization.
- Analyze the marketing funnel to uncover conversion opportunities.
- Build an interactive multi-page dashboard to support data-driven decision-making.

# Dataset Description & Data Structure #
The dataset combines sales transactions, marketing campaign performance, campaign costs, and product information to analyze marketing effectiveness, sales performance, and budget optimization in a fashion retail business.
- 2 Fact Tables: Orders, Marketing Campaign Performance
- 2 Dimension Tables: Products, Marketing Campaign Cost
- Time Period: May 2024 
- Data Volume: 3451 Sales Orders, 3844 Marketing Performance Records
- Data Model: Star Schema
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c6ab8252-1b7d-4f01-bc37-e1e78f9ab0df" />

# Design Thinking Process #
## Step 1. Empathize ##
- 5W1H <img width="1576" height="782" alt="image" src="https://github.com/user-attachments/assets/6fcd41ef-ed74-41a7-92f5-065872cd3e49" />
- Empathy Map <img width="1556" height="838" alt="image" src="https://github.com/user-attachments/assets/c1115c9e-b4a3-4ac2-94ed-3f9ef1f2482b" />
- Stakeholder Journey Map <img width="1860" height="662" alt="image" src="https://github.com/user-attachments/assets/95ff0978-8639-43a5-833b-ed328d1d838c" />

## Step 2: Define Point of View ##
- North Star Metrics <img width="1568" height="750" alt="image" src="https://github.com/user-attachments/assets/150de28e-9306-4d36-af2b-4723da6e42be" />
- Define Point of View <img width="1546" height="606" alt="image" src="https://github.com/user-attachments/assets/b35716b7-f4d9-488e-89e3-3ac75df42ed0" />
- Business Metrics Framework <img width="1550" height="630" alt="image" src="https://github.com/user-attachments/assets/f0914157-92dd-40ef-977b-dfdee07e03c5" />
  
# Key Insights & Visualizations #
## Overview ##
The Overview page provides a high-level summary of marketing performance and advertising efficiency. It enables stakeholders to monitor key KPIs, evaluate overall campaign performance, and quickly identify top-performing products and optimization opportunities.
<img width="1744" height="988" alt="image" src="https://github.com/user-attachments/assets/78b6deef-5965-416a-bc18-f7a9c1e88ed6" />

**Key Features**
- Displays key marketing KPIs including ROAS, ROI, Revenue from Ads, Marketing Cost, Orders, and CPA.
- Tracks daily trends in revenue, advertising performance, and ROI throughout the month.
- Dynamic parameter allows users to switch the main trend chart between ROAS and ROI.
- Top N parameter enables users to display the Top 5, Top 10, or Top N products based on selected ranking metrics.
- Ranking analysis supports multiple dimensions, including Category, SKU, Product Name, and Campaign.

**Business Value**
- Provides an executive overview of marketing performance.
- Identifies the highest-performing products based on ROAS and advertising revenue.
- Monitors marketing efficiency and advertising costs over time.
- Supports quick decision-making for marketing budget optimization.
## Campaign ## 
The Campaign page provides a comprehensive analysis of marketing campaign performance. It enables stakeholders to compare campaign effectiveness, monitor the marketing funnel, evaluate customer acquisition, and identify high-performing campaigns for budget optimization.
<img width="1746" height="990" alt="image" src="https://github.com/user-attachments/assets/61aa9a5b-cf8e-49fe-b7fb-043f24da3c0d" />
**Key Features**
- Displays campaign KPIs including Impressions, Clicks, CTR, Engagement, Inbox, Orders, CVR, ROAS, ROI, and CPA.
- Monitors campaign performance trends over time, including marketing costs, revenue, and profitability.
- Visualizes the marketing funnel from impressions to completed orders to identify conversion bottlenecks.
- Uses a scatter plot to compare campaign performance based on ROAS and Revenue from Ads, helping identify campaigns with strong scaling potential.
- Includes a campaign performance table with conditional formatting for quick comparison across multiple marketing KPIs.
- Supports drill-through navigation to analyze the detailed performance of each campaign.

**Business Value**
- Compare campaign effectiveness using marketing and profitability metrics.
- Identify high-performing campaigns that deserve additional budget.
- Detect underperforming campaigns that require optimization or budget reduction.
- Monitor customer acquisition efficiency throughout the marketing funnel.
- Support data-driven decisions for campaign optimization and marketing investment.

## Campaign detail (Drill through) ##
The Campaign Drill-through page provides an in-depth analysis of an individual marketing campaign. It enables stakeholders to evaluate campaign performance, budget allocation, product contribution, and conversion efficiency at a detailed level.
<img width="1550" height="884" alt="image" src="https://github.com/user-attachments/assets/7bcef926-6e1e-46f0-a67e-5ebe7b012592" />
**Key Features**
- Displays campaign-specific KPIs including Revenue, ROAS, CPA, Orders, and Number of Campaign Variations.
- Shows budget allocation within the selected campaign.
- Analyzes revenue contribution by individual products.
- Visualizes campaign funnel performance from impressions to completed orders.
- Provides a detailed performance table with daily trends, sparklines, and campaign-level marketing KPIs for comparison.

**Business Value**
- Evaluate the effectiveness of an individual campaign.
- Identify which campaign variations generate the highest return.
- Understand product contributions within the selected campaign.
- Monitor campaign efficiency throughout the customer acquisition funnel.
   Support optimization of campaign budget allocation and execution strategy.
  
## Product ##
The Product page analyzes marketing performance from a product perspective. It enables stakeholders to identify high-performing product categories and SKUs, evaluate advertising efficiency, and optimize product-level marketing investments.
<img width="1744" height="986" alt="image" src="https://github.com/user-attachments/assets/b5f12f31-60d0-4c27-a723-5504b99811d0" />

**Key Features**
- Compares marketing performance across product categories using Revenue, Revenue from Ads, ROAS, ROI, CTR, and CVR.
- Interactive category selector enables users to analyze one product category in detail.
- Displays key KPIs including ROAS, ROI, CPA, Number of SKUs, and Number of Campaigns for the selected category.
- Compares Organic and Paid (Ads) revenue contribution.
- Analyzes product sales distribution by size.
- Provides detailed performance tables for both campaign and SKU levels with conditional formatting for quick comparison.
  
**Business Value**
- Identify the most profitable product categories and SKUs.
- Compare organic and paid sales contributions across products.
- Evaluate advertising effectiveness at the product level.
- Prioritize products with high marketing potential for future campaigns.
- Support product portfolio optimization and marketing budget allocation.
  
# Final Conclusion & Recommendations #
<img width="1548" height="764" alt="image" src="https://github.com/user-attachments/assets/f77f99ad-1d06-4ee8-8f2f-633f35f7efb4" />

This project showcases an end-to-end analytics workflow for marketing performance and budget optimization. The process includes understanding business requirements through Design Thinking, transforming and modeling data with Power Query and a star schema, developing business logic and marketing KPIs with DAX, and building interactive dashboards using advanced Power BI features such as drill-through, field parameters, dynamic Top N analysis, and tooltips. The final solution enables stakeholders to evaluate campaign effectiveness, optimize marketing investments, and make data-driven business decisions.
