# global-superstore-sales-analysis
### Business Intelligence & Sales Performance Dashboard

An interactive Business Intelligence project developed using Microsoft Power BI to analyze sales performance, profitability, customer segments, product categories, regional performance, market performance, and sales trends using the Global Superstore dataset.
---

## 📊 Dashboard Preview
<img width="810" height="344" alt="Global superstore dashboard" src="https://github.com/user-attachments/assets/e961dd18-17f2-4273-aa94-eb85c0d04e6a" />


## 📌 Project Overview

This project analyses the Global Superstore dataset to evaluate business performance across sales, profitability, customer segments, product categories, regions, and markets.

The analysis was developed using **Microsoft Power BI**, with data preparation and transformation performed using **Power Query**.

The project focuses not only on revenue generation but also on the relationship between sales and profitability, highlighting areas where strong sales performance does not necessarily result in strong profit.

---
## 🎯 Business Objective

The objective of this analysis is to evaluate sales and profitability performance and identify factors that can support improved business decision-making.

The analysis aims to:

- Measure overall sales and profit performance
- Monitor transaction activity
- Identify high-performing product categories
- Analyze customer segment performance
- Compare regional and market performance
- Identify sales trends over time
- Evaluate the relationship between sales and profitability
- Identify business risks and opportunities
- Provide actionable recommendations for management

---
## 🗂️ Dataset

The Global Superstore dataset contains transaction-level business information covering orders, customers, products, sales, profit, discounts, regions, markets, and shipping information.

### Key Fields

- `Row ID`
- `Order ID`
- `Customer ID`
- `Product ID`
- `Order Date`
- `Ship Date`
- `Ship Mode`
- `Customer Name`
- `Segment`
- `City`
- `State`
- `Country`
- `Postal Code`
- `Market`
- `Region`
- `Category`
- `Sub-Category`
- `Product Name`
- `Sales`
- `Quantity`
- `Profit`
- `Discount`
- `Shipping Cost`
- `Order Priority`

The dataset contains **51,290 transaction records**.

> **Note: ** A single Order ID can contain multiple products or transaction lines. Therefore, the dashboard presents 51,290 records as **Total Transactions** rather than treating each transaction line as a unique order.

## 🧹 Data Preparation

Data preparation was performed using **Microsoft Power Query** before developing the Power BI dashboard.

### Data Preparation Activities

- Reviewed the dataset structure
- Checked for missing values
- Checked for duplicate records
- Reviewed and corrected data types
- Cleaned and transformed relevant fields
- Prepared the dataset for analysis and visualization
- Created measures required for the dashboard KPIs

<img width="960" height="510" alt="power query" src="https://github.com/user-attachments/assets/c7c272d5-b8b1-4b25-8962-438abff1d19d" />

## 📈 Dashboard Development

The Power BI dashboard was designed to provide an interactive overview of business performance.

### Dashboard Components

- Total Sales
- Total Profit
- Total Orders
- Average Sales
- Profit Margin
- Regional Performance
- Product Category Analysis
- Customer Segment Analysis
- Market Performance
- Monthly Sales Trends
- Monthly Profit Trends
- Top Profitable Products
- Geographical Analysis
- Interactive Slicers and Filters

### Interactive Dashboard
<img width="810" height="344" alt="Global superstore dashboard" src="https://github.com/user-attachments/assets/243496ce-daa5-42f8-a8e0-1274a393811b" />
---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Sales** | ₦12.64M |
| **Total Profit** | ₦1.47M |
| **Total Orders** | 51,290 |
| **Average Sales** | ₦246 |
| **Profit Margin** | 11.61% |

---

## 💡 Key Business Finding

> **High sales performance does not always translate into high profitability.**

The analysis identified areas where sales performance is strong while profit remains comparatively low.

For example, **Furniture generated approximately ₦4.11M in sales but only ₦285.20K in profit**, while **Southeast Asia generated approximately ₦884.42K in sales but only ₦17.85K in profit**.

This highlights the importance of evaluating both **revenue and profitability** when making business decisions.

---

## 🔍 Key Business Insights

### 1. Consumer Customers Are the Largest Revenue Contributor

Consumer customers generated approximately **₦6.51M**, representing about **51.48% of total sales**.

### 2. Technology Is the Highest-Performing Category

Technology generated approximately **₦4.74M in sales** and **₦663.78K in profit**, making it the strongest category by sales.

### 3. Central Is the Strongest Region by Sales

The Central region generated approximately **₦2.82M in sales**, making it the highest-performing region.

### 4. High Sales Do Not Always Mean High Profit

Furniture generated approximately **₦4.11M in sales but only ₦285.20K in profit**, demonstrating a significant gap between revenue and profitability.

### 5. Sales Performance Varies Across the Year

November and December recorded some of the strongest sales performance in the dataset, indicating periods of increased demand.

---

## ⚠️ Business Risks

### 1. Revenue Concentration

Consumer customers account for approximately **51.48% of total sales**, creating a risk if Consumer demand declines significantly.

### 2. High Sales With Weak Profitability

Some categories and regions generate substantial sales while contributing comparatively little profit.

### 3. Discount and Cost Pressure

High discounts and other cost pressures can reduce the profit retained from sales, particularly in areas where revenue is strong but margins are weak.

---

## 🚀 Business Opportunities

### 1. Expand High-Performing Technology Products

The strong sales and profit performance of Technology products provides an opportunity to expand profitable product offerings and targeted marketing.

### 2. Improve Profitability

Low-margin categories and regions provide opportunities to improve performance through better pricing, discount management, product selection, and cost control.

### 3. Replicate Successful Regional Strategies

Central's strong performance provides an opportunity to identify successful strategies and adapt them to weaker-performing regions.

---

## 📋 Management Recommendations

1. **Prioritise profitable growth** by evaluating both sales and profit when allocating business resources.

2. **Review pricing and discount strategies** in areas where strong sales are accompanied by weak profitability.

3. **Increase focus on high-performing Technology products** while maintaining healthy profit margins.

4. **Diversify customer-segment revenue** by developing targeted strategies for Corporate and Home Office customers.

5. **Improve regional performance** by analysing successful practices in Central and adapting suitable strategies to weaker-performing regions.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualisation
- **Power Query** — Data cleaning and transformation
- **Microsoft Excel** — Dataset management
- **GitHub** — Project documentation and version control

    └── dashboard-interactive-analysis.png
