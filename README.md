# MONDO_MARKET_PROFITABILITY_ANALYSIS (Tableau)
# Project Overview:
 This project analyzes competitor sales and cost data to evaluate channel-wise profitability for Mondo Market. The objective is to identify the most profitable sales channel for small business customers using Tableau-based visual analytics.
 The analysis focuses on revenue, profit, and profit margin performance across channels between **April 2021 and July 2021**.
# Business Objective:
 MondoMarket plans to launch a new product and needs to decide which sales channel delivers better profitability.  
This project answers:
 Which channel has higher profit margins?
 How does revenue vary by channel and month?
 What is the overall profitability performance during the selected period?
# Datasets Used
  *Competitor Daily Sales Data* – revenue by channel, market, and date  
  *Competitor Monthly Cost Data* – fixed and variable costs for B2B and B2C channels   
The datasets were combined using a *LEFT JOIN* to ensure no sales records were lost.
# Filters Applied
 Market segment: *Small Businesses*
 Date range: *1 April 2021 – 31 July 2021*
# Key Calculations
  *Total Cost* = Fixed Cost + Variable Cost  
  *Profit* = Total Sale Amount − Total Cost  
  *Profit Margin* = SUM(Profit) / SUM(Total Sale Amount)
All ratio calculations were performed at an aggregated level to ensure accuracy.
# Dashboard Components
The Tableau dashboard includes:
  *Profit Margin by Channel**
  *Revenue by Channel and Month**
  *KPI Summary*: Total Sales, Total Profit, and Overall Profit Margin
The dashboard is formatted for clarity, consistency, and executive-level interpretation.
# Key Insight
The analysis highlights clear differences in profitability between channels, enabling data-driven recommendations on which channel should be prioritized for product launch.
# Tools Used
 Tableau Public
 Microsoft Excel
# Disclaimer
 This project is created for learning and analytical demonstration purposes only. The data does not represent real financial information of Mondo Market.
