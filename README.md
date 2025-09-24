# Freshli EoY Trend Analysis - Project Overview

## The Project

Freshli is a relatively new supermarket trying to make a name for itself among other well-established supermarket giants. In order to grow and stay competitive, stakeholders want an EoY Power BI report to be created for the marketing team so that they can spot trends and opportunities for next year. To maximise their efforts across email campaigns, social media posts, website promotions and in-store promotions it is important to analyse: high performing categories vs low performing categories, footfall vs online orders and peak times for shopping. Combining the insights they get from the dashboard, along with a calendar of marketing campaigns executed throughout the year, the team can cross-reference which campaigns drove in the most traffic and if there are categories or promotions they can push. They can also spot days and months where sales are low to get more customers in with incentives.
 
## Dataset

The dataset consisted of one table, including information about sales, purchase categories and whether they purchased the items in-store or online. There were a lot of cells with missing values so I had to clean the data and ensure it was prepared for loading. Two tables were created by myself, a date table with a one-to-many relationship and a measures table which included time intelligence and business KPI measures as seen below.
![dataset](https://github.com/natacha-dasilva/Data-Cleaning-Challenges/blob/main/Assets/Freshli%20Table%20Relationships.png)
 
## Dashboard

https://github.com/user-attachments/assets/2cab2504-c522-4bbf-8916-b7d9d4979b29
 
## Insights

**In order to evaluate trends, we focused on the following key metrics:**
- **YoY Growth:** Change in sales this year vs. last year, in-store and online.
- **Sales Performance:** Best and worst days, months, quarters, product categories, and payment methods.
- **Customer Journey:** Shopping behaviour in-store vs. online and discounted vs. non-discounted transactions.

**YoY Growth**
- Across all months, December had the highest sales this year (£48k) with November seeing the highest growth (19.08%). February saw the lowest sales this year (£37k) with July seeing the lowest growth (-9.26%) - the huge drop in sales YoY for July needs to be investigated.
- Across all quarters, Quarter 4 saw the highest sales this year (£135k) and it saw the highest growth (14.30%). Quarter 3 saw the lowest sales this year (£126k) and the lowest growth (1.30%).
- Across all months January had the highest footfall, whereas November saw the highest number of online orders.

**Sales Performance**
- Beverages saw the highest sales for the year (£74k) and Milk Products had the lowest sales (£56k).
- Throughout the week Tuesday, Friday and Thursday see the highest average sales.
- Cash transactions outperform other methods of spend.

**Customer Journey**
- The number of store visits and online orders that had a discount applied was double than those without a discount.
- When looking at the customer journey of the top 5 customers the average highest spend category for online orders was Electric Household Essentials, whereas for in-store shopping it was Beverages.
- There is a large portion of sales that are categorised as ‘Unknown’ so it is difficult to gather the overall true figures for discounted or non-discounted transactions - something that needs to be fed back to the Data Operations team.

## Recommendations

- **Priorities** - Beverages does the best out of all the categories. Digital and print marketing budgets should be lowered for beverage products and put towards Patisserie and Milk Products as these two categories are the lowest performers both online and in-store.
- **Seasonality** - In-store from June to November sales are low, identifying national and international days that relate to our products to push sales would be beneficial. November in particular needs more marketing efforts as it is the month with the lowest in-store sales - a focus on Black Friday and sneak peeks of what discounts could be coming their way may drive sales. We get double the number of transactions where discounts were applied so we know this is already a great way to bring in more customers.
- **Campaigns** - Both in-store and online, July was one of the slowest months in terms of sales. It also saw a huge drop in sales compared to last year so we would benefit from planning a huge summer campaign to bring sales back up. Perhaps identifying trending summer items that can be sold at Freshli and discussing it with the merchandising team in order to bring excitement and freshness to the store to compete alongside other supermarket giants.
 
## Beyond the Dashboard

The presentation created for the marketing team walks through the insights and recommendations above. Some extracts from the presentation are presented below for easy viewing.
![Presentation Slide Example 1](https://github.com/natacha-dasilva/Data-Cleaning-Challenges/blob/main/Assets/Presentation%20Slide%20Example%201.png)
![Presentation Slide Example 2](https://github.com/natacha-dasilva/Data-Cleaning-Challenges/blob/main/Assets/Presentation%20Slide%20Example%202.png)
![Presentation Slide Example 3](https://github.com/natacha-dasilva/Data-Cleaning-Challenges/blob/main/Assets/Presentation%20Slide%20Example%203.png)
