# myntra-apparel-case-study-excel
Data cleaning, analysis, and lookup functions performed on a 500k+ product dataset from Myntra to derive pricing, discount, and rating insights.

**Myntra Fashion Analytics**

**Overview** :
 Data cleaning, analysis, and lookup implementation on a 500k+ product dataset from Myntra to uncover pricing, discount, and rating insights.

**Key Objectives**
1. Clean and standardize dataset (duplicate removal, missing value imputation)
2. Analyze pricing strategies and discount structures
3. Identify correlations between price and customer ratings
4. Build zero-latency retrieval system using Excel lookup functions

**Dataset Scale** :
 526,564 Products | 2,087 Brands
 8 Categories | 92 Sub-categories |
 Zero duplicate rows

**Methodology**

**Data Cleaning** 
1. Removed duplicates (none found)
2. Standardized DiscountOffer format to numeric percentages
3. Imputed missing DiscountPrice using category averages
4. Validated SizeOption data (no nulls found)

**Data Analysis** 
1. High-rated products (>4 stars) average price: ₹1,966.67 (vs. catalog avg ₹2,414)
2. 230,261 products have discounts >50%
3. 308,460 products available in size "M"
4. Created DiscountStatus column (High/Low Discount)

**Retrieval System**
1. XLOOKUP: Instant brand, price, rating retrieval
2. INDEX/MATCH: Precise attribute extraction
3. Nested XLOOKUP: 360-degree product profile reconstruction

**Key Insights**
1. Pricing Strategy: Median discount of 50% across catalog
2. Sentiment Driver: Price sensitivity drives positive ratings
3. Data Gap: 64% of products (336,152) lack user reviews
4. Category Discounts: Indian Wear (57%), Plus Size (58%), Sports Wear (46%)

**Technologies Used** :
Microsoft Excel (XLOOKUP, INDEX/MATCH, AVERAGEIF, COUNTIF)

**Repository Contents** 
1. Cleaned dataset (.xlsx/.csv)
2. Analysis workbook with all formulas
3. Presentation with visual insights
