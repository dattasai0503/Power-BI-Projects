# Amazon Sales Insights Analysis using Power BI

### Dashboard Link : [https://github.com/dattasai0503/Power-BI-Projects/blob/main/Amazon%20Sales%20Analysis.pbix](https://github.com/dattasai0503/Power-BI-Projects/blob/main/Amazon%20Sales%20Analysis/Amazon%20Sales%20Analysis.pbix)

## Problem Statement

This dashboard helps the  Amazon sales data to uncover trends, monitor sales performance, and generate actionable 
insights to enhance decision-making and optimize business strategies.


### Steps followed 

- Step 1: Load data into Power BI Desktop, dataset is a CSV file.
- Step 2: Open Power Query Editor & in the View tab under the Data Preview section, check "Column Distribution," "Column Quality," & "Column Profile" options.
- Step 3: Also, since by default, profiling will be opened only for 1000 rows, you need to select "Column Profiling Based on Entire Dataset."
- Step 4: It was observed that none of the columns had errors & empty values except for the column named "rating_count."
- Step 5: For calculating average product ratings, null values were not taken into account as only less than 1% of values are null in this column (i.e., column named "rating_count").
- Step 6: In the Report View, under the View tab, a theme was selected.
- Step 7: Since the data contains various product ratings, a new visual was added using the three ellipses in the Visualizations pane in Report View to represent ratings.
- Step 8: Visual filters (Slicers) were added for four fields named "category," "discount_percentage," "rating," & "rating_count."
- Step 9: Two card visuals were added to the canvas, one representing Total Revenue & the other representing Total Revenue Without Discounts.
Using Visual Level Filter from the Filters pane, basic filtering was used & null values were unselected for consideration into the total revenue calculation.





# Snapshot of Dashboard 

![https://github.com/dattasai0503/Power-BI-Projects/blob/main/Dashboard.png](https://github.com/dattasai0503/Power-BI-Projects/blob/main/Amazon%20Sales%20Analysis/Dashboard.png)

 

Based on the Amazon Sales Dashboard, the following insights can be drawn:

### [1] Total Revenue

   The total revenue generated is ₹79,76,911.28.

   The total revenue excluding discounts is ₹45,78,580.43.
           
### [2] Top Performing Product Categories & Subcategories

    Top revenue-generating subcategories:
        Smart Televisions (~₹1.56M)
        Smartphones (~₹1.07M)
        Smart Watches (~₹177.82K)
    Highest-selling subcategory by quantity:
        USB Cables (233 units)
        Smart Watches (76 units)
        Smartphones (68 units)

 
  
  ### [3]Revenue Distribution by Category
  
     Electronics is the highest revenue-generating category (~₹3.14M).
     Home & Kitchen follows (~₹1.04M).

     Other categories like Computers & Accessories, Office Products, and Care & Motorbike
     contribute comparatively less.   

 ### [4] Top Products

    Most profitable product: Sony Bravia 65-inch 4K Ultra HD Smart TV.
    Highest-rated product: AmazonBasics Flexible Premium HDMI Cable with a rating count 
    of  8,53,945.

 ### [5]    Top Selling Products & Prices

The most expensive product in the top sales list is B09WN33RC7 (Electronics) at ₹1,39, 900 with a rating of 4.7.

Other top-selling products fall in the price range of ₹65,000 – ₹1,39,900, all within the Electronics category.
 

