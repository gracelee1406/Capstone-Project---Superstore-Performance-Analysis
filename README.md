# Capstone Project on Interactive Dashboards with Power BI
## _Superstore Performance Analysis_

This is a data analysis project for an online superstore.  It is organized into several key sections - sales and profitability, customer behavior, product performance, shipping and logistics, geographical performance and findings and recommendations.  The goal is **_to improve business performance and profitability_** by gaining a deeper understanding of key operational areas.

---

### Performance Overview
![Dashboard Overview](https://i.imgur.com/6Z7uZVE.png)
![Sales and Profitability](https://i.imgur.com/2BwW6VA.png)
![Customer Behavior](https://i.imgur.com/xnJBbAb.png)
![Product Performance](https://i.imgur.com/Ey21RRd.png)
![Shipping & Logistics](https://i.imgur.com/BjTSZlu.png)
![Geographical Performance](https://i.imgur.com/cDXdhBa.png)

#

### Description of Dataset

The superstore dataset used in this capstone project is obtained from the above-mentioned link.  It consists of 9,994 rows with order dates from Jan 2014 to Dec 2017.  Dataset containing information related to Sales, Profits and other interesting facts of a Superstore giant including how sales are concentrated in key regions and cities across the United States.

### [Link to Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Files
- Sample - Superstore.csv
- Online Superstore.pbix

### Summary of the processes

- **Date Formatting:** standardized the order and ship dates from mm/dd/yyyy to dd/mm/yyyy by splitting the columns and merging into new date columns.
- **Calculated Fields:** added a new column to calculate the shipping duration in days for each order.
- **Currency Formatting:** all price columns are formatted as fixed-decimal numbers with a dollar sign.
- **Calendar Table:** created a new calendar table and established relationships with the main Superstore dataset in the data model. 
- **Hierarchies:** built hierarchies for both the dates in the calendar table and the product category and sub-category in the Superstore table for easier drill-down analysis.
- **Measures:** created several measures, such as profit margin percentage, top 5 customers sales ratio and a count of new customers.
- **Binning:** grouped the data into bins for both discount and shipping duration for analyzing trends and performance across different ranges.

### Findings

Sales consistently peak in the fourth quarter of each year, followed by the third, second, and first quarters.  This suggests a strong seasonal pattern, likely driven by holiday spending.

New customers dropped from 595 to 11 (98.15% decrease) decrease between 2014 and 2017 which poses a significant threat to long-term growth.

Although the top customer, Sean, generated the most sales, analysis reveals that these sales resulted in a total loss.

Technology sector led sales with $836K, followed by Furniture at $742K. Office Supplies had the lowest sales, totaling $719K.  Despite higher sales, the Furniture category generated significantly lower profits than Office Supplies. This was primarily due to the unprofitable sales of tables and bookcases, which may have been sold at a loss to clear out old stock.

A majority of the orders, totaling 3K, were shipped using the Standard Class mode. This was followed by Second Class at 1K, First Class at 0.8K, and Same Day at 0.3K.  This trend suggests that most customers are opting for the more affordable shipping option rather than paying for faster delivery.

The West region recorded the highest sales at $725K, driven primarily by California's $458K. This was followed by the East ($679K), Central $501K), and South ($392K) regions. Key contributors for these regions were New York ($311K), Texas ($170K), and Florida ($89K), respectively.

### Recommendations

**1. Capitalize on Seasonal Trends**
- **_Action Plan:_** Develop a strategic marketing and inventory plan centered around the Q4 sales peak.
- **_Details:_** Since Q4 is the strongest quarter, allocate a larger portion of the marketing budget to this period. Plan special promotions, holiday-themed campaigns, and product launches to maximize sales.  Also, ensure inventory levels are sufficient to meet the increased demand to avoid stockouts.
- **_Recommendation:_** Analyze the specific products that sell best in Q4 and prioritize their promotion and stock.

**2. Address the Decline in New Customers**
- **_Action Plan:_** Implement a targeted new customer acquisition campaign.
- **_Details:_** Focus on identifying and targeting potential new customers through digital marketing, social media campaigns, and partnerships. Offer a special introductory discount or promotion to attract new buyers.
- **_Recommendation:_** Investigate the reason for the drastic drop between 2014 and 2017 to understand and fix the underlying issue.

**3.  Address the loss generated from top customer**
- **_Action Plan:_** Identify the specific loss-making products and investigate the underlying reasons.
- **_Details:_** Focus on the discount policy and the customer relationship
- **_Recommendation:_** Conduct a quick audit of similar high-ticket or popular products to ensure they are protected by a discount policy and ensure a minimum profit margin is always maintained.

**4. Optimize Profitability in the Furniture Sector**
- **_Action Plan:_** Review and restructure the Furniture product line, focusing on profitability.
- **_Details:_** The insight highlights that Furniture, despite high sales, is less profitable due to losses on tables and bookcases. Conduct a thorough cost-benefit analysis of these specific products. Consider increasing their prices, finding a new supplier with lower costs, or discontinuing them if they remain unprofitable.
- **_Recommendation:_** Implement a strategy to liquidate old stock of these unprofitable items at a controlled discount rather than at a significant loss.

**5. Leverage Shipping Preferences**
- **_Action Plan:_** Re-evaluate the shipping strategy to improve customer value and potentially increase profits.
- **_Details:_** The high volume of Standard Class shipping suggests customers are price-sensitive.  Consider offering free standard shipping on orders above a certain value to incentivize larger purchases. 

**6. Expand Regional and State-Specific Strategies**
- **_Action Plan:_** Strengthen marketing and sales efforts in key regions while boosting performance in underperforming areas.
- **_Details:_** The West and East regions are the top performers. Increase marketing budgets in these areas, particularly in high-contributing states like California and New York, to maintain momentum. For the Central and South regions, develop targeted campaigns to address their lower sales.
- **_Recommendation:_** Study the customer demographics and purchasing habits in Texas and Florida to identify opportunities for growth and tailor product offerings or promotions accordingly.

### Created by
**Lee Lai Leng (Grace)** - Data Analyst *(Student Project)*



  
