# databricks-retail-sales-analysis
Retail sales analysis using Databricks, SQL, Genie, and AI/BI Dashboards.
# 📊 Retail Sales Data Analysis Using Databricks

## 📌 Project Overview

This project focuses on analyzing retail sales data using Databricks, SQL, Unity Catalog, Databricks Genie, and AI/BI Dashboards.

The objective is to organize the dataset, perform SQL-based business analysis, explore AI-assisted insights, and develop an interactive dashboard to understand sales performance and support data-driven decision-making.

## 🎯 Project Objectives

- Organize and access sales data using Unity Catalog.
- Analyze overall sales performance using SQL.
- Identify the top five products by sales.
- Compare sales performance across regions.
- Analyze monthly sales trends.
- Calculate product category sales contributions.
- Explore business questions using Databricks Genie.
- Build an interactive AI/BI dashboard with KPIs, charts, and filters.
- Present key business insights and recommendations.

## 🛠️ Tools and Technologies

- **Databricks:** Data analysis and workspace environment
- **SQL:** Data querying and business analysis
- **Unity Catalog:** Data organization and management
- **Databricks Genie:** Natural-language business data exploration
- **AI/BI Dashboards:** Data visualization and interactive reporting

## 📂 Dataset Information

**Catalog:** `innomatics`  
**Schema:** `default`  
**Table:** `sales_data`  
**Full Table Name:** `innomatics.default.sales_data`

The dataset includes information related to:

- Region
- Sales Amount
- Quantity Sold
- Product Category
- Unit Cost
- Unit Price
- Customer Type
- Discount
- Payment Method
- Sales Channel

## 🔍 SQL Analysis

Five SQL analyses were performed to answer key business questions.

### 1. Overall Sales Performance

**Business Question:** What is the overall sales performance?

**Results:**
- Total Sales Revenue: **$5,019,265.23**
- Total Quantity Sold: **25,355**
- Total Sales Records: **1,000**
- Distinct Products: **100**

These metrics provide an overview of the sales dataset.

### 2. Top 5 Products by Sales

**Business Question:** Which five products have the highest sales?

The analysis identifies top-performing products based on sales values and helps compare product performance.

### 3. Regional Sales Performance

**Business Question:** Which regions perform best in sales?

The analysis identified the **North** region as the highest-performing region and the **South** region as the lowest-performing region.

### 4. Monthly Sales Trends

**Business Question:** How do sales change from month to month?

The analysis examines monthly sales performance to help understand changes in sales over time.

### 5. Product Category Contribution

**Business Question:** What percentage of sales does each product category contribute?

**Results:**
- Clothing: **26.17%**
- Furniture: **25.11%**
- Electronics: **24.77%**
- Food: **23.94%**

Clothing recorded the highest sales contribution among the four categories. Percentages may not total exactly 100% because of rounding.

## 🤖 Databricks Genie Analysis

Databricks Genie was used to explore business questions in natural language.

The questions included:

1. What is the total sales revenue and quantity sold?
2. Which product category contributes the most to sales?
3. Which region has the highest and lowest sales?

The overall sales revenue and quantity reported by Genie were compared with the SQL results. The analysis confirmed total sales revenue of **$5,019,265.23** and total quantity sold of **25,355**.

Genie also identified Clothing as the leading product category and North as the highest-performing region, with South as the lowest-performing region.

## 📈 AI/BI Dashboard

An interactive dashboard titled **Retail Sales Performance Dashboard** was created and published.

### Key Performance Indicators (KPIs)

- Total Sales Revenue
- Total Quantity Sold
- Total Sales Records
- Distinct Products

### Dashboard Visualizations

- Monthly Sales Trend
- Regional Sales Performance
- Sales by Product Category
- Top 5 Products by Sales

### Interactive Filters

- Region
- Product Category
- Customer Type

🔗 **Published Dashboard:**  
https://dbc-f9964a2c-ce6c.cloud.databricks.com/dashboardsv3/01f1d23313ad107d8ca0df0c40acb720/published?o=7474655349553641

*Dashboard availability depends on sharing permissions.*

## 💡 Key Business Insights

- The dataset recorded total sales revenue of **$5,019,265.23** across **1,000 sales records**.
- The analysis covered **100 distinct products**.
- Clothing contributed the highest category sales share at **26.17%**.
- North recorded the highest regional sales, while South recorded the lowest.
- Interactive filters allow users to explore sales by region, product category, and customer type.

## ✅ Business Recommendations

- Investigate regional sales differences to identify opportunities for improvement.
- Monitor monthly sales trends to support planning and inventory decisions.
- Review top-performing products to inform product-level strategies.
- Track category contributions to understand sales performance.
- Use interactive dashboard filters to explore different customer and sales segments.

These recommendations provide starting points for further analysis and should be evaluated using additional business context.

## 📰 Medium Article

Read the complete article describing the project workflow, SQL analysis, Genie exploration, dashboard development, and business insights.

🔗 **Read the Full Article:**  
https://medium.com/@omkaramanusha05/databricks-in-action-sales-data-analysis-using-sql-genie-and-ai-bi-dashboards-20f7e2e559bf

## 🎓 Learning Outcomes

This hands-on project helped strengthen my understanding of SQL-based data analysis, Unity Catalog, natural-language data exploration, dashboard development, and business insight generation.

## 🏷️ Technologies and Topics

`Databricks` `SQL` `Data Analytics` `Unity Catalog` `Databricks Genie` `AI/BI Dashboards` `Business Intelligence` `Data Visualization`
