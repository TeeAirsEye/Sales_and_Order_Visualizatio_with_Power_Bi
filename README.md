# Sales_and_Order_Visualization_with_Power_Bi

# Interactive Sales & Order Performance Dashboard

## Overview
This project focuses on building a comprehensive **Sales & Order Performance Dashboard** using **Power BI**. The dashboard offers insights into various aspects of sales performance, order quantities, discounts, and profits across different dimensions like **Region**, **Ship Mode**, **Category**, and **Customer Segments**. The data used in this analysis includes information about **orders**, **ship dates**, **customer segments**, **sales**, **profits**, and **discounts**.

![Interactive Sales Dashboard](https://drive.google.com/uc?id=1bbe2226_3Zl1_zrmCmXc1G3bwiBfP33S)



## Key Metrics & Visualizations
### 1. Key Performance Indicators (KPIs)
- **Sum of Discounts:** `$1.56K`
  - This represents the total amount of discounts offered across all orders.
- **Sum of Sales:** `$2.3M`
  - Indicates the overall revenue generated from sales.
- **Sum of Profit:** `$286.4K`
  - Total profit earned after subtracting costs from sales revenue.
- **Max Profit per Transaction:** `$8.4K`
  - The highest profit recorded from a single transaction.

### 2. Visualizations
#### 2.1 Sales by Region
- **Regions:** West, East, Central, South
- **Sum of Sales:** 
  - **West:** `$0.73M`
  - **East:** `$0.68M`
  - **Central:** `$0.50M`
  - **South:** `$0.39M`
- This bar chart helps to identify the regions with the highest sales, with the **West** region leading in sales performance.

#### 2.2 Count of Orders by Ship Mode
- **Ship Modes:** Standard Class, Second Class, First Class, Same Day
- **Order Counts:**
  - **Standard Class:** `6K` orders
  - **Second Class:** `1.9K` orders
  - **First Class:** `1.5K` orders
  - **Same Day:** `0.5K` orders
- The chart reveals that most customers prefer **Standard Class** for their shipping needs.

#### 2.3 Sum of Sales by Customer Segment
- **Segments:** Consumer, Corporate, Home Office
- **Sales Values:** 
  - **Consumer:** `$1.16M` (53%)
  - **Corporate:** `$0.71M` (32%)
  - **Home Office:** `$0.43M` (15%)
- This analysis shows that **Consumer Segment** accounts for the majority of sales, making up over half of the total revenue.

#### 2.4 Sum of Profit by Region
- **Regions:** West, East, Central, South
- **Profit Distribution:**
  - **West:** `$108.42K` (37.86%)
  - **East:** `$91.52K` (31.96%)
  - **Central:** `$46.75K` (16.32%)
  - **South:** `$39.71K` (13.86%)
- The **West region** is the most profitable, contributing significantly to the overall profits.

#### 2.5 Sum of Discount by Category
- **Categories:** Office Supplies, Technology, Furniture
- This chart illustrates how discounts are distributed among different categories, with **Office Supplies** seeing the highest discount application.

#### 2.6 Sum of Sales by City
- Highlights key cities with the most significant contributions to sales, such as **New York City**, **Lafayette**, and **Seattle**.

## Data Model & Relationships
The data model consists of three primary tables:
1. **Orders:** Contains order details such as `Order ID`, `Order Date`, `Ship Date`, `Profit`, and `Sales`.
2. **People:** Represents sales representatives and their associated `Region`.
3. **Returns:** Tracks orders that were returned with a `Returned` status.

### Relationship Mapping:
- **People** table is linked to the **Orders** table using the `Region` field.
- **Returns** table is connected to **Orders** through the `Order ID`, enabling tracking of returned orders and their impact on profits.

## Insights & Recommendations
### Insights:
1. **High Sales Region:** The **West** region shows the highest sales and profit, indicating potential for further market penetration.
2. **Customer Segment Contribution:** The **Consumer** segment accounts for over 50% of sales, suggesting targeted marketing and loyalty programs could yield more growth in this segment.
3. **Shipping Preferences:** The preference for **Standard Class** shipping suggests that customers prioritize lower costs over faster shipping times.

### Recommendations:
1. **Increase Focus on High-Performing Regions:** Invest in targeted marketing campaigns for the **West** and **East** regions to maintain and potentially increase their profitability.
2. **Enhance Customer Experience for Corporate Segment:** The **Corporate** segment, though not the largest, contributes significantly. Focused strategies to boost **Corporate** client relationships could be beneficial.
3. **Reevaluate Discounts for Office Supplies:** Consider analyzing the impact of the high discounts offered in the **Office Supplies** category on overall profit margins to ensure sustainable growth.
4. **Improve Return Rate Management:** Monitor and reduce return rates by analyzing the reasons for returns in the **Returns** table and implementing corrective actions.

## Conclusion
This dashboard provides a holistic view of the sales and order performance, helping stakeholders make data-driven decisions. By focusing on regions and segments with high profitability and understanding shipping preferences, businesses can optimize their strategies for better outcomes. Power BI has proven to be a powerful tool for turning raw data into actionable insights.
