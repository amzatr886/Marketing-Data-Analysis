# Marketing Data Analysis Using Power BI: Documentation
## Leveraging data-driven insights to optimize marketing strategies and drive impactful business decisions

### Introduction:
This documentation provides an overview of the marketing data analysis conducted using Power BI. It includes the methodology, key insights, and findings derived from the data analysis. The analysis aims to provide actionable insights into customer demographics, spending behaviour, and campaign performance to inform strategic decision-making.
### Methodology
#### Data Cleaning
- **Removed Duplicates:** Duplicates were removed using unique ID columns to ensure data integrity.
- **Trimmed White Spaces:** White spaces were removed using the Trim function in Power Query to maintain consistency.
- **Formatted Columns:** Columns were formatted to ensure data consistency across the dataset.
### Data Transformation
- **Calculated Column for Customer Age:** A new column was created to calculate customer age using the birth year column.
- **Unpivoted Columns for Aggregation:** 
  <br> - ***Products Table**: Unpivoted columns (MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds) to create a product column and aggregate the amount spent on each product.*
  <br>  - ***Purchases:** Unpivoted columns (NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases) to create a purchases column and aggregate purchases.*
  <br>  - ***Campaign Responses:** Unpivoted columns (AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, and Responses) to create a campaign type column and responses for each campaign.*
#### Data Modeling
- **Creation of Additional Data Tables:** Four additional data tables (Products, Campaign, Spending, and RFM tables) were created from the dataset to optimize model performance.
- **Star Schema Data Modeling:** Many-to-one relationships were established between the tables using customer details as the fact table.
### Key Insights and Findings
#### Overview Page:
- Total Customers: 2,216
- Total Purchases: 33k
- Average Income: $52k
- The last campaign performed the best.

- Campaign 4 was the second-best.
- Campaign 2 performed the worst.
- Campaign 1 was the second-worst.
- Website Traffic: Highest in August (702 visitors) and lowest in February.
#### Customer Demographic
- Children: 71% of customers have at least one child, while 29% have no children.
- Geography: Most customers are from Spain, followed by Saudi Arabia.
- Income: Most customers earn between $60,000 - $90,000.
- Education: Most customers have a B.Sc. degree, followed by a Ph.D. degree.
- Age: Most customers are aged 51-70 years, followed by those aged 28-50.
#### Spending Analysis
- Income and Spending Correlation: Higher income correlates with higher spending.
- Customers with children spend more on wines and gold products.
- Customers without children spend more on meat, fish, sweet, and fruit product
- Spending by Marital Status: Single people earn more and spend more than other marital statuses.
- Overall spending is higher on meat and wine products.
- Spending is lower on sweet and fruit products.
- High-income customers spend more on wine and gold products.
- Low-income customers spend more on meat and gold products.
#### Customer Segmentation
- Complaints: The company logged a total of 21 complaints throughout the year.
- Purchase Preference: Most customers prefer to buy from stores, followed by the web.
- Campaign Engagement: 72.5% of campaigns were ignored, indicating a need for re-strategizing.
- Customer Loyalty: Loyal customers have the highest purchases. The potential loyal segment has the least purchases.
- Segmentation: Most customers fall within the "needs attention" segment.
### Conclusion
The analysis provides valuable insights into customer demographics, spending behaviour, and campaign performance. These findings highlight areas for strategic improvement, such as campaign re-strategizing and targeted marketing efforts to different customer segments. The use of Power BI enabled the visualization of these insights, making it easier to derive actionable recommendations for enhancing marketing strategies and overall business performance.
### Appendices
#### Visuals and Dashboards
- Overview Page Dashboard
- Customer Demographic Dashboard
- Spending Analysis Dashboard
- Customer Segmentation Dashboard
#### Data Tables
- Fact Table: Customer Details
- Dimension Tables: Products, Campaign, Spending, RFM
#### Power BI DAX Formulas
- Calculated Columns
- And Measures used in the analysis
### Final Note
This documentation serves as a comprehensive guide to understanding the marketing data analysis conducted using Power BI. It is intended for stakeholders and team members involved in decision-making processes related to marketing strategies.

