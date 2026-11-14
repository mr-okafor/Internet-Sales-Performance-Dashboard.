# Internet Sales Performance Dashboard

A Business Intelligence project focused on analysing internet sales performance, understanding product and customer contributions, evaluating salesperson performance, and comparing actual sales against budget.

## 1. Business Overview

The sales management team currently relies on static reports to monitor internet sales performance. These reports offer limited flexibility when investigating sales trends, identifying top-performing products and customers, or evaluating individual salesperson contributions.

The objective is to transform existing sales data into an interactive Power BI dashboard that provides management with a clearer view of business performance and supports data-driven decision-making.

The dashboard should enable users to explore sales performance across different dimensions, identify trends, and measure actual results against the 2021 sales budget.

## 2. Project Objectives

The analysis focuses on answering the following business questions:

- How much revenue is generated from internet sales?
- Which products and product categories contribute the most to sales?
- Who are the highest-value customers?
- How has sales performance changed over time?
- How are individual sales representatives performing?
- How does actual sales performance compare against the allocated budget?
- Which products, customers, and sales representatives are driving business performance?

## 3. Dataset Overview

The project uses historical internet sales data alongside a separate Excel spreadsheet containing the 2021 sales budget.
The analysis covers a two-year historical period, as requested by the sales management team.

The dataset contains information relating to:

- **Sales Transactions:** Sales amounts, order dates, products sold, and customer information.
- **Products:** Product names, categories, and other product attributes.
- **Customers:** Customer details and purchasing information.
- **Sales Representatives:** Salesperson information associated with different products and customers.
- **Budget:** Allocated sales targets for 2021.

## 4. Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI | Data modelling, DAX calculations, and dashboard development |
| Power Query | Data cleaning and transformation |
| SQL Server | Data cleaning and transformation |
| DAX | Creating measures and calculating business KPIs |
| Microsoft Excel | Budget data preparation and integration |

## 5. Data Preparation & Modelling

The data preparation process involved:

- Inspecting the available datasets and understanding their structure.
- Cleaning and transforming raw sales data.
- Handling missing values and correcting data types where necessary.
- Preparing the budget spreadsheet for integration.
- Establishing relationships between relevant tables.
- Developing a data model to support cross-filtering and interactive analysis.
- Creating DAX measures for sales performance and budget comparisons.

## 6. Dashboard Preview

The Power BI dashboard is organised into three main sections to provide different perspectives on internet sales performance.

### 6.1 Sales Overview

Provides a high-level summary of internet sales performance, highlighting key performance indicators, revenue trends, and overall business performance.

![Sales Overview](./images/Sales_overview.png)

### 6.2 Product Details

Provides a detailed analysis of product performance, allowing users to explore sales contributions across individual products and product categories.

![Product Details](./images/Product_details.png)

### 6.3 Customer Details

Examines customer purchasing behaviour and sales contributions, helping identify valuable customers and understand how revenue is distributed across the customer base.

![Customer Details](./images/customer_details.png)

## 7. Interactive Features

The dashboard includes interactive filtering capabilities that allow users to investigate sales performance from different perspectives.

Users can filter and explore data by:

- Salesperson
- Product
- Customer
- Date and sales period

These filters make it easier to investigate specific areas of the business without relying on separate static reports.

## 8. Key Business Insights

This section highlights the most important findings identified during the analysis.

Insights will cover:

- Overall internet sales performance and historical trends.
- Top-performing products and product categories.
- Customer contributions and purchasing patterns.
- Salesperson performance.
- Actual sales performance against budget.
- Areas of strong performance and potential improvement.

## 9. Business Recommendations

Based on the findings, recommendations will focus on:

- Identifying opportunities to improve sales performance.
- Prioritising high-performing products and categories.
- Strengthening relationships with high-value customers.
- Identifying areas where sales representatives may need additional support.
- Investigating significant budget variances.
- Improving future sales planning and budget allocation.

## 10. Project Deliverables

- Interactive Power BI dashboard.
- Data cleaning and transformation.
- Data modelling and DAX calculations.
- Sales performance analysis.
- Product and customer analysis.
- Budget performance analysis.
- Business insights and recommendations.

## 11. Repository Structure

```text
Internet-Sales-Performance-Dashboard/
│
├── Dataset/
│   ├── Sales Data
│   └── Budget Data
│
├── Dashboard/
│   └── Internet Sales Dashboard.pbix
│
├── Images/
│   ├── sales_overview_1.png
│   ├── sales_overview_2.png
│   ├── sales_overview_3.png
│   ├── product_details_1.png
│   ├── product_details_2.png
│   ├── product_details_3.png
│   ├── customer_details_1.png
│   ├── customer_details_2.png
│   └── customer_details_3.png
│
└── README.md
```

---

**Project:** Internet Sales Performance Dashboard  
**Category:** Business Intelligence & Data Analytics  
**Primary Tool:** Microsoft Power BI
