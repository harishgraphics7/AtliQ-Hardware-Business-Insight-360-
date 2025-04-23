# AtliQ-Hardware-Business-Insight-360-
## 🏢 Company Overview
AtliQ Hardwares is a leading and fast-growing enterprise in the electronic goods sector, specializing in the design and distribution of high-performance PCs, keyboards, mice, and printers. With a strong commitment to quality, innovation, and customer-centricity, we cater to a diverse clientele across both consumer and business segments. Our product portfolio is engineered to deliver reliability, efficiency, and cutting-edge technology—positioning AtliQ Hardwares as a trusted partner in the evolving digital ecosystem

## Table of Contents
* [Problem Statement](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-problem-statement)
* [Objectives](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-objectives)
* [Datasets Overview](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-dataset)
* [Data Modeling](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-data-modeling)
* [Dashboard Overview](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-dashboard-overview)
* [Key Insights]()
* [Challenges and Learnings]()
* [Strategic Recommendations]()
* [Conclusion](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-conclusion)
* [Useful Links](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#useful-links)
* [Acknowledgement](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/README.md#-acknowledgment)

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


## 📊 Dataset
Below is a breakdown of the datasets used for this project:

Source Type	Table Name	Description
## 🗂️ Dataset Overview

Below is a structured breakdown of the datasets utilized in this project, sourced from both MySQL databases and Excel files:

| **Source Type**        | **Table Name**                    | **Description**                                             |
|------------------------|-----------------------------------|-------------------------------------------------------------|
| MySQL (GDB041)         | `Fact_Forecast_Monthly`           | Forecasted product demand by month                         |
| MySQL (GDB041)         | `Fact_Sales_Monthly`              | Actual monthly sales data                                  |
| MySQL (GDB056)         | `Fact_Manufacturing_Cost`         | Monthly manufacturing cost per product                     |
| MySQL (GDB056)         | `Fact_Freight_Cost`               | Freight and shipping cost details                          |
| MySQL (GDB056)         | `Fact_Gross_Price`                | Gross prices assigned to products                          |
| MySQL (GDB056)         | `Fact_Pre_Invoice_Deduction`      | Pre-invoice discounts and deductions                       |
| MySQL (GDB056)         | `Fact_Post_Invoice_Deduction`     | Post-invoice discounts and deductions                      |
| MySQL (GDB041)         | `Dim_Customer`                    | Customer master data                                       |
| MySQL (GDB041)         | `Dim_Product`                     | Product master data                                        |
| MySQL (GDB041)         | `Dim_Market`                      | Market and regional mapping                                |
| Excel                  | `Target`                          | Sales targets used for performance benchmarking            |
| Excel                  | `Market_Share`                    | Competitor-wise market share data                          |
| Excel                  | `Operational_Expenses`            | Regional operating expense details                         |


## 🧩 Data Modeling

**Schema:**  
Utilized a **Snowflake Schema** to ensure optimal performance, scalability, and ease of maintenance.

**Key Steps:**

- Imported structured data from **MySQL** into **Power BI** for analysis and visualization.
- Performed comprehensive **data cleaning and transformation** using **Power Query** to prepare datasets for modeling.
- Established **logical relationships** between dimension and fact tables to support accurate data analysis.
- Created **calculated columns and DAX measures** to derive meaningful insights and enable advanced analytics.
![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/SCHEMA.png)


## 📊 Dashboard Overview

The Power BI dashboard is composed of six distinct pages, each designed to provide insights into a specific business domain:



🏠 **Home Page** – Serves as a navigation hub, utilizing bookmarks for seamless page transitions.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/HOME%20VIEW.png)




💰 **Finance Dashboard** – Displays profit & loss statements, product-wise profitability, and sales trends.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/FINANCE%20VIEW.png)




📈 **Sales Dashboard** – Analyzes customer and product performance metrics.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/SALES%20VIEW.png)




📣 **Marketing Dashboard** – Showcases segment-wise profitability and campaign insights.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/MARKETING%20VIEW.png)




🚚 **Supply Chain Dashboard** – Highlights forecast accuracy and operational KPIs.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/d3f611f9a541be874d1ffeb42e939f52f027ff6e/SUPPLY%20CHAIN%20VIEW.png)




🧑‍💼 **Executive Summary** – Presents high-level metrics and key performance indicators for leadership review.

![image alt](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/EXECUTIVE%20VIEW.png)



## 💡 Key Insights

- **Finance View**:  
  Although sales are on an upward trend, net profit is declining—indicating a need for improved **expense management** and cost optimization.

- **Sales View**:  
  Major revenue contributors include key accounts such as **Amazon** and **Flipkart**, while smaller accounts are underperforming and require strategic attention.

- **Marketing View**:  
  **Margin inefficiencies** are evident across specific products and regions, particularly in the **Gaming category** and the **APAC region**. Focused marketing and pricing strategies are recommended.

- **Supply Chain View**:  
  **Forecast accuracy** remains reasonable; however, inventory challenges persist in regions like **LATAM** and **India**, affecting supply continuity and service levels.

- **Executive View**:  
  While **market share** is increasing, **profitability is under pressure**. Notable growth potential exists in the **PC segment** and regions such as **North America (NA)** and **India**.


## ⚙️ Challenges & 📘 Learnings

### 🔴 Challenges

1. **Handling Duplicate Subzones**  
   Encountered issues with duplicate subzone values in the *Market Share* and *Dim Market* tables, leading to inaccurate calculations and inconsistencies in the data model.

2. **DAX Calculations for Market Share**  
   Writing accurate DAX measures for market share was challenging. Initial formulas returned identical values across all subzones due to data model configuration issues.

3. **Data Cleaning and Transformation**  
   Managing large datasets with missing or inconsistent values was time-intensive, especially when dealing with multiple interconnected tables.

---

### ✅ Learnings

1. **Resolving Many-to-Many Relationships**  
   Gained practical experience in managing many-to-many relationships using **reference tables** and DAX functions like `ALLNOBLANKROW` to maintain calculation accuracy.

2. **Mastering DAX for Metrics**  
   Enhanced skills in crafting complex **DAX formulas** and understanding how minor syntax variations can significantly impact analytical results.

3. **Importance of Data Cleaning**  
   Recognized the critical role of systematic **data cleaning** in ensuring model consistency and the reliability of insights.

4. **Power BI Data Modeling**  
   Learned best practices for designing structured, scalable **data models** in Power BI to improve performance and dashboard responsiveness.

5. **Reporting with Excel and Power BI**  
   Developed the ability to create intuitive, **user-friendly reports** using both Excel and Power BI to effectively communicate trends and key business metrics.

## ✅ Strategic Recommendations

- **Optimize Operational Efficiency**:  
  Reduce operational and freight-related expenditures to enhance overall **profit margins**.

- **Strengthen Key Account Management**:  
  Prioritize investment in **high-performing accounts** (e.g., Amazon, Flipkart), while reassessing engagement strategies for underperforming clients.

- **Refine Marketing Strategies**:  
  **Reallocate marketing spend** to high-performing regions and product segments; implement cost controls in regions showing suboptimal returns.

- **Enhance Supply Chain Planning**:  
  Improve **demand forecasting** accuracy and streamline inventory management to minimize stockouts and excess inventory.

- **Portfolio Rationalization**:  
  Phase out **low-performing products** and strategically focus on **high-growth markets** and categories, such as PCs and emerging regions.

## 🧾 Conclusion

This project successfully transformed fragmented and unstructured data into meaningful, **actionable insights**, empowering AtliQ to transition from assumption-based decision-making to a **data-driven strategic approach**. The integration of Power BI enabled enhanced visibility across departments, supporting informed, agile, and impactful business decisions.

## Useful Links
- Project Presentation
- [Dashboard Preview](https://github.com/harishgraphics7/AtliQ-Hardware-Business-Insight-360-/blob/main/AtliQ%20Hardware%20BI%20360.pdf)
- [Live Dashboard](https://app.powerbi.com/groups/me/reports/63307588-e4ed-45be-ac55-b594437400a4?experience=power-bi)

## 🙏 Acknowledgment
This project is part of CodeBasics Data Analytics Bootcamp's Power BI course.

  
