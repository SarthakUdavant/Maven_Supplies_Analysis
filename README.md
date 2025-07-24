# Maven_Supplies_Analysis

## Objective:
- To analyze sales, product demand, and customer behavior for a quick-commerce platform, and deliver insights to improve inventory, revenue, and operational efficiency.

## Key Areas of Analysis:
- Sales performance by city, product, and category
- Product demand & profitability
- Order patterns (hourly/daily trends)
- Delivery times and customer service levels

## Data Sources:
- Sales transactions dataset
- Product catalog (category, brand, price)
- Customer and outlet location data

## Dashboards
![image](https://github.com/SarthakUdavant/Maven_Supplies_Analysis/blob/main/Screenshots/1.png)
![image](https://github.com/SarthakUdavant/Maven_Supplies_Analysis/blob/main/Screenshots/2.png)
![image](https://github.com/SarthakUdavant/Maven_Supplies_Analysis/blob/main/Screenshots/3.png)
![image](https://github.com/SarthakUdavant/Maven_Supplies_Analysis/blob/main/Screenshots/4.png)
![image](https://github.com/SarthakUdavant/Maven_Supplies_Analysis/blob/main/Screenshots/5.png)


## Tools Used:
- Tableau (dashboard creation & data visualization)
- Excel/CSV (data source format)

## Data Cleaning (ETL Process):
 -Removed duplicates & nulls
- Standardized product/category names
- Date-time formatting and extraction (e.g., hour, weekday)
- Merged datasets for full analysis (sales + products + location)

## Data Modeling:
- Star schema style: Fact table (Sales) linked to Dimension tables (Products, Cities, Time)
- Relationships established via Product ID, City, and Order Date

## Key Highlights:
- Top-selling products and categories identified
- Peak sales hours and best-performing cities
- Inventory issues flagged by low-performing SKUs or OOS items
- Geo-level delivery time analysis

## Top Insights:
- Certain cities contribute 60%+ of total revenue
- Snacks & beverages dominate orders but have lower margins
- Weekends and evenings see peak order volumes
- Delays concentrated in specific locations or time bands

## Sales & Revenue Recommendations:
- Focus marketing on top-selling time slots & cities
- Push high-margin alternatives in low-profit categories
- Bundle products to increase AOV (Average Order Value)

## Inventory & Product Recommendations:
- Increase stock for fast-moving items with frequent stockouts
- Reduce or re-strategize slow-moving SKUs
- Use city-level demand forecasts to optimize regional inventory
