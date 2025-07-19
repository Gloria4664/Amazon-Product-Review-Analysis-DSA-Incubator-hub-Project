# Amazon-Product-Review-Analysis-DSA-Incubator-hub-Project
A comprehensive Excel focused analytical project on Amazon product reviews, discounts,and prices. My very first data analysis project with DSA (incubator hub). This project requires the usage of pivot tables, slicers, interactive dashboards and calculated fields to extract actionable insigts that will lead to a drive in the e-commerce world.

#### Objectives: Carry out analysis on Amazon products and review data inorder to extract actionabale business insights with the use of pivot table, slicers, calculated fields and data visualizations.

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




   
  
