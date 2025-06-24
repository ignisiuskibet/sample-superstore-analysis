# Power BI Dashboard: Sample Superstore Analysis

This project analyzes the **Sample Superstore** dataset using Microsoft Power BI to uncover sales, profit, and regional trends. The dashboard provides interactive visual insights that can guide business decisions for growth and efficiency.

---

##  Dataset

- **Source**: Sample Superstore dataset 
- **Type**: CSV
- **Records**: ~10,000
- **Fields**: Order Date, Ship Date, Sales, Profit, Category, Region, Segment, etc.

---

##  Business Insights

###  Key Takeaways:

- **Top Regions**: The **West** region generates the most profit.
- **Profitable Segments**: The **Consumer** segment leads in total sales and net profit.
- **Product Categories**:
  - **Technology** is the highest-selling category.
  - **Office Supplies** underperforms in profit despite high sales.
- **Profitability Issues**:
  - Some sub-categories like **Tables** result in losses across multiple regions.
- **Shipping Delays**: Small but notable delay between `Order Date` and `Ship Date` in high-volume months.
- **Seasonality**: Strong Q4 sales patterns, likely due to holiday season demand.

---

##  Dashboard Preview

![Dashboard] (images\dashboard-preview.png)

---

##  Power BI Features Used

- Power Query Editor (data cleaning, unpivoting, transformation)
- Calculated columns (Year, Month, Quarter from Order Date)
- Custom visuals: Line Chart, Bar Chart, Scatter Plot, Card Visuals

---

##  How to Use

1. Clone the repository
  
