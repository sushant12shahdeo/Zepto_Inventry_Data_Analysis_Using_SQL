# Zepto_Inventry_Data_Analysis_Using_SQL
Analyzed product catalog data, pricing structures, and inventory status for a quick-commerce platform (Zepto) using SQL (PostgreSQL). Cleaned and transformed raw data, resolved currency and unit anomalies, calculated key e-commerce KPIs, and generated actionable business insights for inventory and revenue optimization.


## Tools Used

* **SQL (MySQL)**: Schema creation, data cleaning, data transformation, unit economics, and business intelligence queries.

---

##  Project Workflow

1. **Loaded and explored the dataset** to understand schema structure and categorical distributions.
2. **Cleaned corrupted data**, removed zero-MRP items, and fixed unit pricing inconsistencies.
3. **Applied division-by-zero safeguards** and unit normalizations for price-per-gram analyses.
4. **Executed SQL queries for business insights** covering stockouts, category revenue, and package segmentation.
5. **Generated actionable business recommendations** for inventory management and discount strategies.


##  Key Insights

* **Currency Normalization**: Identified and converted catalog price metrics stored in paise to standard rupee values.
* **Category Revenue Potential**: Calculated total inventory revenue potential across product categories to pinpoint high-value stock.
* **High-Value Stockout Tracking**: Isolated premium items (MRP > ₹300) currently out of stock to highlight critical lost sales opportunities.
* **Unit Economics**: Calculated standardized pricing per 100g to identify best-value products regardless of package sizing.


## How to Run

1. Clone the repository.
2. Set up your **MySQL** database (v12+ recommended).
3. Execute `schema.sql` to create the `zepto` table.
4. Run `data_cleaning.sql` to apply currency fixes and data sanitization.
5. Run `analysis_queries.sql` to generate analytical business insights.
