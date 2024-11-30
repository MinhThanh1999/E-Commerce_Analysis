# E-Commerce_Analysis
## I.INTRODUCTION
### 1.Background
- We are an agency who want to become the 1-stop technological interface to grow online sales in South East Asia
- We are serving companies ranging from top-tier international brands to small purely online businesses providing them each with the right services and tech to address the issues that impact their growth including online marketing, marketplace platform sales optimization, social commerce ...

### 2.Datasets
- We have 2 dataset was recorded from 01-07-2024 to 31-07-2024 as following:  
    - (1): Historical sales performance data from internal Order Management System
      
    ![image](https://github.com/user-attachments/assets/503bf474-74f6-4b8d-8836-98feeaadd607)

    - (2): Traffic source performance data from Google Analytics

    ![image](https://github.com/user-attachments/assets/3a4c68f2-e4d3-4691-87ab-4286a4140c11)

### 3.Business Request: 
  We have received a request from one of our clients as follows: 
  - They achieved 10Bils+ VND for gross revenue in July. In August, they want to double this achievement.
###  So we have to solve these challenges:
  - Give a summary on the key findings from given dataset.
  - Propose a few actions we need to take, why and how we should implement it to achieve the above KPI.

## II. Visualization
### 1. Order Management
![image](https://github.com/user-attachments/assets/8551da00-5585-4848-9fe8-3dee94276060)

### 2. Traffic Analysis
![image](https://github.com/user-attachments/assets/fdbeb37a-184b-4bc5-be98-a4b13b8d8f7e)

## III. Insights
### Key Findings: What Do We Have in the Order Management System?
- First of all, we recorded $10 billion in gross revenue, but the actual revenue is only $8 billion. This discrepancy is due to $2 billion in refunds for canceled orders. The cancellation rate is nearly 20% daily, which significantly impacts our total gross revenue. We need to address this issue.
- We observed that customers typically purchase only one item per order. To encourage upselling, we should introduce promotions, such as offering a discount of X% on the second item purchased.
- Another area of concern is the Selling Price versus Original Price. Even without applying any vouchers, the selling price is consistently lower than the original manufacturer’s price, which reduces gross revenue. We need to investigate and identify the root cause.
- The highest number of orders was placed on July 12th, accounting for over 36.23% of total gross revenue. This day seems to have something special driving customer purchases, and we should leverage it further.
- The monthly retention rate is low. We need to track this over time and, if no improvement is observed, identify the root causes.

### Key Findings: Key Information About Traffic from Google Analytics
- Total users recorded in Google Analytics are much higher than the number of customers in the Order Management System, with about 90% of users being new. Notably, the top 5 sources contribute over 90% of total users, including new users. Google is the most effective source, generating over 50% of total revenue across all sources.
=> These insights show that the top 5 sources have significant potential for converting users into customers.
However, our bounce rate is high, and the conversion rate is low. This suggests that the website is not attractive or fails to meet customer expectations, limiting the total revenue.
- Retention of users from each source is also quite low. We need to monitor this over time, and if retention rates remain stagnant, improvements will be necessary.

### Conclusion: What Should We Do to Achieve the Target?
1. Address the High Cancellation Rate: Collect customer feedback and improve products to better meet their needs.
2. Encourage Upselling: Apply promotions such as "Buy 1 item and get X% off on the second item" to increase the average items per order and drive sales.
3. Leverage Peak Days: Boost advertising and stimulate demand on the busiest day of each month by offering special promotions on that day.
4. Enhance the Website: Fix issues on the website or landing pages to improve the user experience and better meet customer expectations, increasing the buying rate.
5. Focus on Top Sources: Strengthen strategies to attract more customers from the top 5 sources by segmenting and targeting key customer groups effectively.
