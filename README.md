# Coffee Shop Sales - Analytics Project

### [Power BI -Dashboard Link](https://github.com/sachinbasyal/Coffee-Shop-Data-Analytics/blob/main/Power%20BI%20Dashboard%20%26%20Report/CoffeeShop-Insights.pbix)

## Project Background
The Coffee Shop Sales - Analytics Project was initiated to enhance operational efficiency and uncover actionable insights for a coffee shop. With the growing competitiveness in the food and beverage industry, data-driven decision-making is crucial for optimizing revenue streams, identifying sales trends, and improving business operations.

This project leverages SQL for data extraction and Power BI for visualization, providing stakeholders with a comprehensive, interactive dashboard to monitor key performance indicators (KPIs) and make informed business decisions.

- The primary dataset used for this analysis, which consists of detailed sales transaction information, can be found [here](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales?resource=download).
- The SQL queries used to clean, organize, identify, and prepare data for the dashboard can be found [here](https://github.com/sachinbasyal/Coffee-Shop-Data-Analytics/blob/main/SQL%20Queries.pdf).

## 1. Executive Summary
This project focuses on analyzing coffee shop sales performance using data-driven insights. A **Power BI Revenue Insights Dashboard** was developed to empower stakeholders with actionable insights to optimize revenue growth and operational efficiency.

## 2. Business Problem Statement
Coffee shops generate revenue from various products across multiple store locations. However, understanding sales trends, peak sales periods, top-performing products, and customer purchase behavior is critical for business optimization. This project aims to:

- Analyze **Total Sales, Orders, and Quantity Sold** across different time periods.
- Identify sales trends using **MoM (Month-over-Month) comparisons**.
- Provide insights on sales by **store locations, product categories, and customer behavior** by weekdays, weekends, and time of day.
- Utilize visual analytics (**heat maps, line charts, and bar charts**) to support data-driven decision-making.

## 3. Data Overview
The dataset includes key transaction-level sales data with the following key attributes:

- **Transaction Date & Time**: Timestamp of each transaction.
- **Store Location**: Geographic location of the store.
- **Product Category & Details**: Classification of sold products.
- **Quantity & Unit Price**: Number of units sold and corresponding price.
- **Revenue Calculation**: Derived as **Quantity * Unit Price**.

## 4. Key Performance Indicators (KPIs) Analysis
### 4.1 Total Sales Analysis:
- **Total Sales per Month**: Monthly revenue generated.
- **MoM Change**: Percentage increase/decrease in sales compared to the previous month.
- **Sales Difference**: Difference in revenue between the selected month and the prior month.

### 4.2 Total Orders Analysis:
- **Total Orders per Month**: Number of orders placed monthly.
- **MoM Change**: Percentage increase/decrease in order volume.
- **Order Difference**: Absolute difference in order volume from the previous month.

### 4.3 Total Quantity Sold Analysis:
- **Total Quantity Sold per Month**: Total items sold.
- **MoM Change**: Percentage increase/decrease in total quantity.
- **Quantity Difference**: Difference in total quantity sold month-over-month.

## 5. Steps Followed:
1. Requirement Gathering/Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layouts
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

## 6. Data Visualization & Insights
### 6.1 Calendar Heat Map for Daily Sales Performance:
- Displays daily sales performance where **darker shades indicate higher sales**.
- Interactive tooltips provide **daily revenue, order count, and quantity sold**.

### 6.2 Sales Analysis by Weekdays vs. Weekends:
- Identifies **differences in customer traffic patterns** on weekdays vs. weekends.
- Provides insights into **when peak sales occur**.

### 6.3 Sales by Store Location:
- Displays **sales distribution across different store locations**.
- **MoM Comparison**: Highlights which store locations are growing or declining in sales.

### 6.4 Daily Sales Trend with Average Sales Line:
- **Bar chart with an average sales line** to track daily performance.
- Identifies days with **exceptional sales spikes or dips**.

### 6.5 Sales by Product Category:
- Breakdown of sales by **coffee, tea, hot chocolate, and other categories**.
- Identifies **high-revenue product categories driving business success**.

### 6.6 Top 5 Best-Selling Products:
- Displays the **top 5 products based on total revenue**.
- Helps optimize **inventory and promotional strategies**.

### 6.7 Sales Heat Map by Day and Hour:
- Identifies **peak sales hours for targeted marketing and staffing optimization**.
- Tooltips provide **revenue, order count, and quantity sold per time block**.

# Report Snapshots (Power BI DESKTOP)
![Dashboard1_upload](https://github.com/sachinbasyal/Coffee-Shop-Data-Analytics/blob/main/Power%20BI%20Dashboard%20%26%20Report/dashboard-1.png)
![Dashboard2_upload](https://github.com/sachinbasyal/Coffee-Shop-Data-Analytics/blob/main/Power%20BI%20Dashboard%20%26%20Report/Dashboard-2.png)


## 7. Business Recommendations
- **Optimize Product Inventory & Pricing**: Increase stock for high-demand products and adjust pricing for slow-moving items.
- **Leverage High-Sales Time Periods**: Offer targeted promotions during peak weekday and weekend hours.
- **Store-Specific Strategy Implementation**: Enhance marketing efforts in underperforming store locations.
- **Drive Customer Retention & Engagement**: Implement loyalty programs and discounts to encourage repeat purchases.

## 8. Conclusion
The **Coffee Shop Revenue Insights Dashboard** provides a **comprehensive view of sales trends, peak performance periods, and key growth opportunities**. By leveraging these insights, stakeholders can make **data-driven decisions** to optimize sales, improve inventory management, and enhance the customer experience.

---
## 📌 **Contributions & Feedback**
If you have any suggestions or want to contribute, feel free to open a **pull request**!
#### 📧 Contact: sachinbasyal@gmail.com
---

