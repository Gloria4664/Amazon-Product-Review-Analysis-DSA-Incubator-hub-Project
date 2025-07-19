# Amazon-Product-Review-Analysis-DSA-Incubator-hub-Project
##### A comprehensive Excel focused analytical project on Amazon product reviews, discounts,and prices. My very first data analysis project with DSA (incubator hub). This project requires the usage of pivot tables, slicers, interactive dashboards and calculated fields to extract actionable insigts that will lead to a drive in the e-commerce world.

 Objectives: Carry out analysis on Amazon products and review data inorder to extract actionabale business insights with the use of pivot table, slicers, calculated fields and data visualizations.

## Project Context
**Company Name**: RetailTech Insights

**Industry**: E-commerce.

**Role**: Junior Data Analyst

 **Tools used**: Microsoft excel(slicer, pivot table, charts, conditional formatting etc)
 
## Dataset Description
+ **Total records**: 1,465
+ **Columns**: 16
+ **Source**: Web- scrapped amazon product review data
+ **Each row represents**: A unique products fields which includes:
     + Product name
     + category
     + Actual price & discounted price
     + Discount percentage
     + Rating
     + Rating count
     + Review content
     + Revenue potential fields(created)

 ## Key Analytics and solutions.

| S/N | Analyticics | Excel tools/ formula used |
|-----|-------------|---------------------------|
| 1 | What is the average discount % by product category | Pivot table + avarage formula |
| 2 | How many products are listed under each category | pivot table + count |
| 3 | What is the total number of reviews per category | SUM of rating count by category |
| 4 | which products have the highest avaerage ratings | sorting based on calculated average rating |
| 5 | What is the average actual price vs the discounted price by category | Grouped bar chart + pivot summary |
| 6 | Which products have the highest number of reviews | Top-R analysis usinf sorting + pivot table |
| 7 | How many products have a discount of 50% or more | filter logic on discount column |
| 8 | What is the distribution of product ratings (e.g, 3.0,4.0, etc.) | grouped bar chart +pivot table count |
| 9 | What is the total potential revenue (actual_price × rating_count) by category | New calculated column + pivot table **sum**
| 10 | What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500) | IF formulas + bar chart |
| 11 | How does the rating relate to the level of discount | scatter line chart |
| 12 | How many products have fewer than 1,000 reviews | COUNTIF formula + bar chart |
| 13 | Which categories have products with the highest discounts | sorted pivot table by discount % |
| 14 |Identify the top 5 products in terms of rating and number of reviews combined | Ranking formula using **SUM**( rating plus review counting) |

## Analysed Files

[Amazon product review dashboard.xlsx](https://github.com/user-attachments/files/21327597/Amazon.product.review.dashboard.xlsx)

### Visuals and Dashboard

<img width="1325" height="445" alt="dashboard 2" src="https://github.com/user-attachments/assets/a84ce2d7-1fe5-48f8-be62-d33dea297246" />

<img width="1346" height="532" alt="Insight table" src="https://github.com/user-attachments/assets/dcb574cb-ab54-4ced-8ec1-bd790082b32c" />

<img width="1353" height="479" alt="Raw Data" src="https://github.com/user-attachments/assets/382d587a-8f9c-42d3-9ab4-e345adb9a771" />

### Key Highlights deduced from the dashboard:
+ **Discount vs rating**: discount products don't always have higher rating.
+ **Revenue**: categories like home kitchen and electonics tend to generate more revenue.
+ **Discount percentage**: Health and home products tends to offer more discounts
+ **Reviews**: the total number of products with review less than 1000 is 308
+ **Top 5 Products**: analysis based on high review count and strong rating(e.g, AmazonsBasics FI, RealmeX, etc)

## Skills and competency applied
+ **Data cleaning**: removed nulls, corrected inconsistent formats and trimmed texts.
+ **Data aggregation**: used pivot tables and grouping to summarise key insights.
+ **Excel Formulas**: utilized _IF_, _COUNTIF_, _AVERAGEIF_, _PROPER_, and _calculated columns_ functions.
+ **Visualization**: visualized with bar chart, pie chard, line chart, and scattered chard
+ **Slicers**: Enabled dynamic filtering and KPI display.
+ **Business Reasoning**: deducted conclusion based on data and business logic

## Buiness Insights(Summary)
1. Product with moderate ratings but high reviews may benefit from improved quality and targeted feedback campaigns
2. Few products drive massive engagement. Promoting products like this helps in cross-selling
3. Electonics has the most reviews
4. A lot of discounted products received poor rating which implies that price cut alone can't satisfy customers.
5. Marketing should more focused on product low sales and ratings

## Tools and Environment.

**Microsoft Excel**
+ Pivot tables
+ Data visualization(Bar, scattered, line and pie chart.)
+ Slicers and filters
+ Conditional formatting.
+ Name Ranges and Table Referencing.


