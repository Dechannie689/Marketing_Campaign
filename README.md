# Marketing Campaign Analysis - Power BI
![](https://github.com/Dechannie689/Marketing_Campaign/blob/main/Marketing%20Campaign%20Analysis.png)
## Abstract
The Marketing Campaign Dashboard visualizes key insights to provide a comprehensive overview of campaign performance in Power BI, leveraging a dataset sourced from marketing_campaign.csv. It provides a centralized hub for dissecting and optimizing the performance of marketing campaigns, enabling data-driven decision-making and helping businesses maximize their marketing ROI. 
## Data Manipulation
Prior to analysis, I imported the dataset into Power BI and transformed it on Power Query Editor. Here are the step-by-step manipulations done on the source datasets:
### Step 1: Creation of Product & Amount Spend Column
- To better analyze the data, I used the Unpivot Columns feature in Power Query to transform "MntWines" column, "MntFruits" column, "MntMeatProducts" column, "MntFishProducts" column, "MntSweetProducts" column and "MntGoldProds" column into "Product" and "Amount Spend" column.
- Then, I used the Replace Values function to make the “Product” column more readable.
### Step 2: Creation of Campaign & Accepted Status Column
- Similarly, I used the Unpivot Columns feature to transform "AcceptedCmp1" column, "AcceptedCmp2" column, "AcceptedCmp3" column, "AcceptedCmp4" column, "AcceptedCmp5" column into "Campaign" and "Accepted Status" column.
- Then, I used the Replace Values function to make the “Campaign” column more readable.
### Step 3: Creation of Purchase and Number of Purchase Column
- Likewise, I used the Unpivot Columns feature to transform "NumWebPurchases" column, "NumCatalogPurchases" column, "NumStorePurchases" column, "NumDealsPurchases" column into "Purchase" and "Number of Purchase" column.
- Then, I used the Column from examples function to make the “Purchase” column more readable.
## Data Visualization
Visual representation of data offers intuitive insights. The following visuals will be incorporated in the report:
#### Cards
- Displaying the number of customers.
- Showcasing total amount spend in 2 years.
- Representing the toal products and campaigns.
- Representing the average of recency.
#### Slicer
- Representing the age range/ Marital Status/ Education/ Kid Home/ Teen Home/ Product.
#### Charts
- Stacked bar chart for showing Total Spending by Product and Number of Purchase.
- Pie charts for Accepted Campaign.
- Stacked column chart for the Average Spending by Income & Product and the Average Spending by Age & Education.
- Line and Stacked column chart for showing the Average Spending by Marital Status.

Gratitude for your time!
