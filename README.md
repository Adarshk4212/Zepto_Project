📌 Project Title

Zepto Inventory, Pricing & Discount Analysis (SQL Project)

📌 Problem Statement

Quick commerce companies like Zepto operate with thin margins and high inventory turnover.
This project aims to analyze product availability, discount strategy, and inventory distribution to identify operational risks and revenue-impacting patterns using SQL.

📌 Dataset Overview

Source: Simulated Zepto product catalog

Records: 3,732 SKUs

Key Columns:

category

name

mrp

discountPercent

discountedSellingPrice

availableQuantity

outOfStock

weightInGms

quantity

📌 Tools & Technologies

SQL (PostgreSQL syntax)

Excel / CSV for data storage

GitHub for version control

📌 Key Business Questions Answered

How many products are in-stock vs out-of-stock?

Which categories face the highest stock-out risk?

Are there duplicate products with multiple SKUs?

How aggressive are discounts across categories?

Which products combine high discount + low weight, increasing fulfillment cost risk?

📌 Key Insights (Quantified)

📦 ~18% of total SKUs were out-of-stock, posing direct revenue loss risk.

🥦 Fruits & Vegetables category showed the highest SKU concentration, making it the most inventory-sensitive segment.

💸 Discounts ranged up to 30%, with clustering around 15–16%, suggesting standardized discounting rather than demand-based pricing.

🧾 Multiple products appeared under the same name but different SKUs, indicating catalog duplication and operational complexity.

📌 Business Recommendations

Improve demand forecasting for high-frequency categories to reduce stock-outs.

Consolidate duplicate SKUs to simplify catalog and reduce inventory overhead.

Shift from flat discounting to category-specific pricing optimization.

Monitor low-weight, high-discount SKUs due to higher fulfillment cost per unit.

📌 Outcome

This project demonstrates end-to-end SQL analytics capability, combining data cleaning, exploration, and business insight generation for quick commerce operations.
