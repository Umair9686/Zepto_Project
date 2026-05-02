📘 README.md Content
🔍 Overview

This project focuses on data exploration, cleaning, and analysis of a retail dataset modeled on quick-commerce platform Zepto.

The dataset contains product-level information such as pricing, discounts, stock availability, and weight. The goal is to derive actionable insights using SQL.

🗂️ Dataset Schema

The dataset includes the following fields:

sku_id – Unique product identifier
category – Product category
name – Product name
mrp – Maximum retail price
discountPercent – Discount applied (%)
availableQuantity – Stock available
discountedSellingPrice – Final selling price
weightInGms – Product weight
outOfStock – Stock status (TRUE/FALSE)
quantity – Units per package

⚙️ Key Steps Performed
1. Data Exploration
Row count and sampling
Null value detection
Unique category extraction
Stock availability analysis
Duplicate product identification

3. Data Cleaning
Removed invalid entries (MRP = 0)
Converted price units from paise → rupees
Ensured consistency across numeric fields

4. Data Analysis & Business Insights
📊 Pricing & Discount Analysis
Top 10 products with highest discounts
Products with high MRP but out of stock
Low discount on premium products

💰 Revenue Estimation
Estimated revenue per category using:
discountedSellingPrice * availableQuantity

🏷️ Category Insights
Categories with highest average discounts
Total inventory weight per category

⚖️ Value Analysis
Price per gram calculation for better value comparison
Identification of best-value products

📦 Product Segmentation
Categorized products based on weight:
Low (< 1kg)
Medium (1kg–5kg)
Bulk (> 5kg)

📈 Sample Insights
Certain categories offer significantly higher discounts, indicating competitive pricing strategies
High-MRP products going out of stock may indicate high demand or supply issues
Price-per-gram analysis highlights hidden value differences across products
Inventory weight distribution helps in logistics and warehouse planning

🛠️ Tech Stack
SQL (PostgreSQL / MySQL compatible)
Data Analysis using queries (no external tools required)
