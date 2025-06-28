# retail-sales-analysis
End-to-end data analysis project using Python, MySQL and Tableau. From [raw retail order data](https://github.com/Anuraj-96/retail-sales-analysis/blob/main/orders.csv) to cleaned insights, visualizations, and a professional dashboard highlighting sales performance and profitability metrics.

## Project Overview
This project explores and analyzes a retail dataset to uncover key insights about sales, revenue, and customer behavior across the United States. It combines Python (Pandas) for data cleaning, MySQL for KPI calculation and transformation, and Tableau for creating dynamic, interactive dashboards.

## Steps Taken 
1 Loaded the Raw CSV into Python  
- Inspected using python
- Checked for missing values
- Handled Nulls and Fixed Data Types

2 Exported Cleaned CSV
- Final file saved as retail_cleaned.csv

3 Imported into MySQL
- Created new analytical columns using SQL  
Additional calculated columns:  
discount_amount  = List Price * Discount % / 100  
sale_price       = List Price - Discount Amount  
revenue          = Sale Price × Quantity  
profit           = (Sale Price - Cost Price) × Quantity  

These new columns made it easier to analyze: Revenue trends , Profit margins , Discount impact

## Tools used
- Python 
- MySql
- Tableau

## Dashboards

 *Business Performance Dashboard* 
<img width="1440" alt="Business Performance Dashboard" src="https://github.com/user-attachments/assets/8f9067d8-3b7f-4a9e-a5c2-20015df6f0bf" />

### Key Insights:

- 💰 Total Revenue: $11.08M | 📈 Total Profit: $1.04M | 🛒 Total Orders: 9,994

- 📊 Strongest Sales Months: Highest revenue spikes observed in February 2023 and Q1 2023

- 📈 Profit Growth by Category:  
Furniture profit dropped 15%  
Technology increased by 12%  
Office Supplies improved by 8%  

- Customer Segments:    
Home Office customers had the highest average order value: $1.16K    
Consumer segment drove most consistent revenue across time

- 🌎 Top Cities by Revenue:  
New York City leads with $1.22M, followed by Los Angeles and Seattle

- 🚚 Shipping Preferences:  
Most orders were via Standard Class (6K+ orders)



*Sales and Performance Dashboard*
<img width="1438" alt="Sales and Performance Dashboard" src="https://github.com/user-attachments/assets/0302ee05-5acd-46ce-a421-b87d5feabaaa" />

- Top Revenue Product: TEC-CO-10004722 contributed $245K

- Top States by Sales:  
California ($2.22M), New York ($1.50M), Texas ($0.80M)

- 🏙️Top Cities by Revenue:  
New York City, Los Angeles, Seattle

- Profit Growth by Sub-Category (2022 vs 2023):  
Supplies up 79%, Machines up 65%, Binders up 42%  
Fasteners down 76%, Appliances down 53%

- Top Selling Products by Region: Top 5 products shown per region using quantity sold

- 📅 Best Month & Year per Category:  
Furniture: August 2023 ($231K)  
Office Supplies: February 2023 ($287K)  
Technology: October 2023 ($296K)  

## KPIs Calculated
- Total Revenue  
- Total Profit  
- Total Orders  
- Average Order Value  
- [SQL QUERIES](https://github.com/Anuraj-96/retail-sales-analysis/blob/main/Retail-orders%20sales%20analysis%20SQL%20queries.pdf)

## Key Charts in Tableau
1. **Revenue vs Profit**
2. **Top 10 Highest Revenue Generating Products**
3. **Top 5 Highest Selling Products In Each Region**
4. **Top 5 Sales by State**
5. **Top 10 Cities by Revenue**
6. **Average Order Value by Segment**
7. **Comparative Profit Analysis: Sub-Categories (2022 vs 2023)**
8. **Comparative Profit Analysis: Categories (2022 vs 2023)**
9. **Best Year and Month for Each Category**
10. **Customer Segment Performance Over Time**
11. **Shipping Mode Analysis**
12. **Month Over Month Sales Growth (2022 vs 2023)**

## Tableau Profile
[BUSINESSPERFORMANCESUMMARY](https://public.tableau.com/app/profile/anuraj5859/viz/RetailSalesBusinessPerformanceDashboard/BUSINESSPERFORMANCESUMMARY)
[SALESPROFITINSIGHTSDASHBOARD](https://public.tableau.com/app/profile/anuraj5859/viz/RETAILSALESDASHBOARD_17511095262380/SALESPROFITINSIGHTSDASHBOARD)

