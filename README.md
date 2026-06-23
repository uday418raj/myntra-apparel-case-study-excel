# myntra-apparel-case-study-excel
Data cleaning, analysis, and lookup functions performed on a 500k+ product dataset from Myntra to derive pricing, discount, and rating insights.

**Myntra Fashion Analytics**

**Overview**

Data cleaning, analysis, and lookup implementation on a 500k+ product dataset from Myntra to uncover pricing, discount, and rating insights.

**Key Objectives**

Clean and standardize dataset (duplicate removal, missing value imputation)/n
Analyze pricing strategies and discount structures
Identify correlations between price and customer ratings
Build zero-latency retrieval system using Excel lookup functions

**Dataset Scale**

526,564 Products | 2,087 Brands
8 Categories | 92 Sub-categories
Zero duplicate rows

**Methodology**

**Data Cleaning**

Removed duplicates (none found)
Standardized DiscountOffer format to numeric percentages
Imputed missing DiscountPrice using category averages
Validated SizeOption data (no nulls found)

**Data Analysis**

High-rated products (>4 stars) average price: ₹1,966.67 (vs. catalog avg ₹2,414)
230,261 products have discounts >50%
308,460 products available in size "M"
Created DiscountStatus column (High/Low Discount)

**Retrieval System**

XLOOKUP: Instant brand, price, rating retrieval
INDEX/MATCH: Precise attribute extraction
Nested XLOOKUP: 360-degree product profile reconstruction

**Key Insights**

Pricing Strategy: Median discount of 50% across catalog
Sentiment Driver: Price sensitivity drives positive ratings
Data Gap: 64% of products (336,152) lack user reviews
Category Discounts: Indian Wear (57%), Plus Size (58%), Sports Wear (46%)

**Technologies Used**

Microsoft Excel (XLOOKUP, INDEX/MATCH, AVERAGEIF, COUNTIF)

**Repository Contents**

Cleaned dataset (.xlsx/.csv)
Analysis workbook with all formulas
Presentation with visual insights
