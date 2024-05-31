# Consumer-Goods-Ad_hoc-Insights

## About Company 
Atliq Hardware is a leading computer hardware manufacturer based in India, recognized for its extensive global reach, 
operating in 27 countries. 
Serving a large clientele of 74 customers, Atliq Hardware has firmly established its presence in Asia Pacific (APAC), 
Europe (EU), North America (NA), and Latin America (LATAM).

Specializing in three key product divisions – 
Peripherals and Accessories (P & A), Network and Storage (N & S), and Personal Computer (PC) – 
Atliq Hardware offers a diverse product portfolio, making it a versatile and dependable choice for consumers worldwide.

## Business Scenario

Atliq Hardwares' management wants to understand the sales performance across different regions to 
optimize inventory and marketing strategies. They have asked the data analytics team to provide insights 
into regional sales trends, top-selling products, and monthly revenue growth. Tony Sharma, the Data 
Analytics Director, has designed a SQL challenge for junior data analyst candidates to solve this ad hoc request, 
demonstrating their ability to extract and analyze data effectively.

## Database Overview

This file provides a comprehensive overview of the tables found in the 'gdb023' (atliq_hardware_db) database. It includes information for six main tables:

1. dim_customer: contains customer-related data
2. dim_product: contains product-related data
3. fact_gross_price: contains gross price information for each product
4. fact_manufacturing_cost: contains the cost incurred in the production of each product
5. fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
6. fact_sales_monthly: contains monthly sales data for each product.

## Ad_hoc requests


1. Provide the list of markets in which customer "Atliq Exclusive" operates its
business in the APAC region.

2. What is the percentage of unique product increase in 2021 vs. 2020? The
final output contains these fields,
      unique_products_2020,
      unique_products_2021,
      percentage_chg

4. Provide a report with all the unique product counts for each segment and
sort them in descending order of product counts. The final output contains
      2 fields,
      segment,
      product_count

6. Follow-up: Which segment had the most increase in unique products in
2021 vs 2020? The final output contains these fields,
      segment,
      product_count_2020,
      product_count_2021,
      difference

8. Get the products that have the highest and lowest manufacturing costs.
The final output should contain these fields,
      product_code,
      product,
      manufacturing_cost

9. Generate a report which contains the top 5 customers who received an
average high pre_invoice_discount_pct for the fiscal year 2021 and in the
Indian market. The final output contains these fields,
      customer_code,
      customer,
      average_discount_percentage

11. Get the complete report of the Gross sales amount for the customer “Atliq
Exclusive” for each month. This analysis helps to get an idea of low and
high-performing months and take strategic decisions.
The final report contains these columns:
      Month,
      Year,
      Gross sales Amount

13. In which quarter of 2020, got the maximum total_sold_quantity? The final
output contains these fields sorted by the total_sold_quantity,
      Quarter,
      total_sold_quantity

15. Which channel helped to bring more gross sales in the fiscal year 2021
and the percentage of contribution? The final output contains these fields,
      channel,
      gross_sales_mln,
      percentage

17. Get the Top 3 products in each division that have a high
total_sold_quantity in the fiscal_year 2021? The final output contains these
fields,
      division,
      product_code,
      product,
      total_sold_quantity,
      rank_order

