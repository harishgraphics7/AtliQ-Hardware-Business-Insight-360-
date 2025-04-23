# AtliQ-Hardware-Business-Insight-360-
## 🏢 Company Overview
AtliQ Hardwares is a leading and fast-growing enterprise in the electronic goods sector, specializing in the design and distribution of high-performance PCs, keyboards, mice, and printers. With a strong commitment to quality, innovation, and customer-centricity, we cater to a diverse clientele across both consumer and business segments. Our product portfolio is engineered to deliver reliability, efficiency, and cutting-edge technology—positioning AtliQ Hardwares as a trusted partner in the evolving digital ecosystem

## Table of Contents
* Project Overview
* Problem Statement
* Objectives
* Datasets Used
* Data Modeling
* Dashboard Overview
* Power BI Techniques Learned
* Key Business Metrics and Insights
* Challenges and Learnings
* Conclusion and Future Scope

## ❓ Problem Statement
* AtliQ relied on Excel and assumption-based decision-making, which led to poor outcomes, especially in the Latin American market.
* As the company scales, it needs to adopt advanced analytics to stay competitive with industry giants like Dell.
* This project aims to bring transparency, data-backed decisions, and strategic insights using Power BI.

## 🎯 Objectives

- Implement a centralized analytics solution using **Power BI** to unify data and streamline reporting.
- Enable stakeholders to access **actionable insights** that support strategic and operational decision-making.
- Analyze and visualize data across multiple departments to drive performance and efficiency:

  - **Finance**:  
    - Analyze profit & loss statements  
    - Conduct product-level profitability assessments  
    - Track net sales trends  

  - **Sales**:  
    - Evaluate customer and product performance  

  - **Marketing**:  
    - Measure segment-wise profitability  

  - **Supply Chain**:  
    - Monitor forecast accuracy  
    - Assess operational efficiency  

  - **Executive Summary**:  
    - Provide leadership with high-level dashboards and KPIs for quick insights


📊 Dataset
Below is a breakdown of the datasets used for this project:

Source Type	Table Name	Description
MySQL (GDB041)	Fact_Forecast_Monthly	Forecasted demand for products by month
MySQL (GDB041)	Fact_Sales_Monthly	Actual sales data by month
MySQL (GDB056)	Fact_Manufacturing_Cost	Monthly manufacturing cost per product
MySQL (GDB056)	Fact_Freight_Cost	Freight or shipping cost details
MySQL (GDB056)	Fact_Gross_Price	Gross price assigned to products
MySQL (GDB056)	Fact_Pre_Invoice_Deduction	Discounts or deductions before invoicing
MySQL (GDB056)	Fact_Post_Invoice_Deduction	Discounts or deductions after invoicing
MySQL (GDB041)	Dim_Customer	Customer master data
MySQL (GDB041)	Dim_Product	Product master data
MySQL (GDB041)	Dim_Market	Market and region mapping
Excel	Target	Sales targets for comparison
Excel	Market_Share	Competitor-wise market share data
Excel	Operational_Expenses	Operating expenses for each region

## 🧩 Data Modeling

**Schema:**  
Utilized a **Snowflake Schema** to ensure optimal performance, scalability, and ease of maintenance.

**Key Steps:**

- Imported structured data from **MySQL** into **Power BI** for analysis and visualization.
- Performed comprehensive **data cleaning and transformation** using **Power Query** to prepare datasets for modeling.
- Established **logical relationships** between dimension and fact tables to support accurate data analysis.
- Created **calculated columns and DAX measures** to derive meaningful insights and enable advanced analytics.
![image alt](https://github.com/harishgraphics7/Excel-Atliq_Hardware_Sales_And_Finance_Performance_Report/blob/24d98b5ecaa31a54e6a957c4fe69e27d74035f30/relationship%20diagram.png)


## 📊 Dashboard Overview

The Power BI dashboard is composed of six distinct pages, each designed to provide insights into a specific business domain:

1. **Home Page** – Serves as a navigation hub, utilizing bookmarks for seamless page transitions.


  
