# Zepto Inventory Data Analysis Using SQL

Analyzed 3,731 SKUs from a Zepto-style e-commerce inventory using MySQL to uncover 
pricing, stock, and revenue insights across 14 product categories.

## Tools
MySQL

## Workflow
1. Designed schema and imported raw CSV data using `LOAD DATA LOCAL INFILE`
2. Cleaned data — removed zero-price records, converted prices from paise to rupees
3. Wrote 8 business-focused SQL queries covering pricing, stock, and revenue

## Key Insights
- Estimated total inventory revenue: **₹22.4 lakh** across 14 categories
- **Cooking Essentials and Munchies** were the top revenue-generating categories 
  (₹3.37 lakh each), together accounting for ~30% of total revenue
- **453 of 3,731 products (12%) are out of stock**, including high-value items 
  like Patanjali Cow's Ghee (₹565 MRP)
- **Fruits & Vegetables had the highest average discount** (15.5%), likely due 
  to perishability-driven markdowns
- **1,214 products exist as multiple SKUs** (different pack sizes/weights) — 
  reflecting real-world catalog duplication
- Dukes Waffy Wafers had the steepest discount in the catalog at **51% off**

## How to Run
1. Import `zepto_v2.csv` into MySQL using the schema in `schema.sql`
2. Run `queries.sql` for the full set of business insights
