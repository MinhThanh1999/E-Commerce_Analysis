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
![image](https://github.com/user-attachments/assets/d2b315bd-e9d7-407f-8c66-1dc8bdbf2e72)

### 2. Traffic Analysis
![image](https://github.com/user-attachments/assets/0aca475d-b978-422d-9082-db839d41d62e)

## III. Insights
### Key finding: What we have in Order Management System?
- First of all, we was recorded 10 billion dollards for gross revenue but the actual revenue is only 8 billions, 2 billions from cancelled order have to refund for customers. The cancelled rate is almost 20% every day, which affect significant on our total gross revenue so we need to improve it.
- We can see that one person only purchase one item, we need to digest in this point to up sale by giving promotion such as buy 1 item the next one will discount x%
- Another thing need to focus is Selling Pirce versus Original Price, without any voucher but the selling price is still slower than the original price from manufacturer. Which make gross revenue was decrease so we need to figure what is the root.
- The quantity of orders is highest on July 12th, it takes over 36,23% of total gross revenue, this day must have something special to push our customer to buy.
- Retention rate is low in a month, which need tracking over month to see if it is not change then we should figure out the root causes.

### Key finding: What is key informationa about traffic from Google Analytics?
- Total users were recorded, which is much higher than number of customers were recorded by Order Manaagement System with about 90% users are new. Notably, Top5 sources take over 90% total Users of all source and so are new users. Google is the most attractive Source, it took over 50% total revenue of all source.
=> All of that show top 5 source are potential to convert users to our customer.
- Besides that, our bounce rate is high and conversion rate is low, which means the site is not attractive and not yet meet customer's expectation, leading Conversion rate is low, limit total revenue.
- Retention user is quite low per source, need tracking over month, if the average rentention overlap so we need to improve it.

### Conclusion:
What should we do to achieve the target?
