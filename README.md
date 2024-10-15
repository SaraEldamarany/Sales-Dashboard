# Sales Data Overview, Process, and Analysis

## 1. Data Overview:
- The dataset tracks sales in 2020, including customers, order details, discounts, and profits.
- **Key Columns:**
  - **Consumer ID:** Unique customer identifier.
  - **Order ID:** Unique order transaction identifier.
  - **Total Order Value:** Gross transaction value.
  - **Discount:** Discounts applied to the order.
  - **Profit:** Revenue generated after deducting costs.
  - **Product:** Product categories (e.g., Bags, Sandals).
  - **Product Cost:** Cost associated with each product.

## 2. Process Details:
- **Data Cleaning:**
  - Remove duplicates based on `Order ID` or `Consumer ID`.
  - Check for missing data in critical columns.
  - Convert currency columns to numeric by removing the euro (€) symbol.
  
- **Metrics Calculation:**
  - `Net Revenue = Total Order Value - Discount`
  - `Profit Margin = Profit / Total Order Value`
  
- **Tools:**
  - Use **Pivot Tables** for grouping data by products, customers, and months.
  - **Sorting/Filtering** for analyzing high-value orders or high-profit items.

## 3. Key Insights:
- **Customer Analysis:**
  - Identify top customers based on profit and repeat purchases (using `Consumer ID`).
  
- **Product Performance:**
  - Determine best-selling products by analyzing `Total Order Value` and `Profit`.
  - Assess product profitability by comparing `Profit - Product Cost`.
  
- **Seasonality:**
  - Analyze monthly sales trends and identify peak sales periods.
  - Evaluate the impact of discounts on sales and profits.
  
- **Financial Analysis:**
  - Review how discounts influence overall profit margins.
  - Focus on products or customers contributing the most to total revenue.
 
![Sales Dataset Analysis](https://github.com/SaraEldamarany/Sales-Dashboard/blob/main/DASHBOARD.png)
