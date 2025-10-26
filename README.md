# E-Commerce Data Analysis using MySQL

## Project Overview
This project analyzes e-commerce sales data to gain insights into product performance, category-wise revenue, and pricing trends. Using SQL queries, we explored top-selling products, revenue distribution, and patterns in pricing and sales volume.

## Dataset Used
The analysis uses a subset of the Kaggle e-commerce dataset with the following tables:
- **products**: Product IDs, names, and category information.
- **order_items_**: Order IDs, product IDs, and product prices.

## Key Findings
- **Top-Selling Products**: Products with the highest total sales and quantity sold were identified.
- **Revenue by Category**: Categories like `beleza_saude`, `relogios_presentes`, and `cama_mesa_banho` generated the highest revenue.
- **Product Pricing**: Most expensive and cheapest products were determined; average price per product calculated.
- **Sales Distribution**: Number of times each product was sold across categories analyzed.
- **Above-Average Products**: Products with total sales above the dataset’s average were identified.
- **Top Product per Category**: The top-selling product in each category was determined using ranking queries.

## SQL Queries Included
- Listing products by category
- Top-selling products
- Revenue per category
- Average and total price per product
- Products with sales above average
- Creating views for top-selling products
- Ranking top products per category
