# E-COMMERCE SALES AND CUSTOMER ANALYTICS DASHBOARD 

Dashboard:

![Image](https://github.com/quafiya-rahim/E-Commerce-Sales-And-Customer-Analytics-Dashboard/blob/main/sales_performance_overview.png)
![Image](https://github.com/quafiya-rahim/E-Commerce-Sales-And-Customer-Analytics-Dashboard/blob/main/customer_behaviour_analysis.png)
![Image](https://github.com/quafiya-rahim/E-Commerce-Sales-And-Customer-Analytics-Dashboard/blob/main/discount_pricing_analysis.png)
![Image](https://github.com/quafiya-rahim/E-Commerce-Sales-And-Customer-Analytics-Dashboard/blob/main/Screenshot%202026-01-15%20201501.png)

## 1. Data Overview

 This project analyzes e-commerce transactional data to evaluate sales performance, customer purchasing behaviour, and operational efficiency. The dataset covers orders, products,categories, revenue, discounts, payment modes, device types, delivery status, and customer feedback. The analysis highlights revenue trends, high-performing products, customer preferences, discount effectiveness, and service quality insights  to support data-driven business decisions.
 The dataset used for analysis contains several columns related to sales & customer's information as stated below:

* Transaction_id : Unique ID for each transaction
* User_id : Unique ID for individual customer
* Product_id : Unique code of each product
* Product_name : Name of product purchased
* Category : Product classification
* Price : Price before discount
* Qnatity : Number of units purchased 
* Discount : Discount applied
* Payment_method : Payment mode 
* Transaction_time : Date & time transaction occurred
* Delivery_status : Current order status
* Device_type : Device used to place an order
* Customer_feedback : Feedback after delivery
* Final_price : Price after discount
* Order_locations : Location where order delivered
* Day : Day of the week on which transaction occurred 


                
The primary objective is to derive data-driven insights by calculating critical metrics such as:

* Total revenue
* Average order value
* Total customers
* Returning customers
* Total discount
* Top countries for orders
* Revenue trend over time
* Product/category with highest revenue
* Most used device type
* Day with highest no. of transactions
* Quantity by product
* Most used payment method
* Average discount by category/product
* Average discount by device type
* Negative feedback by product
* Delivery status distribution
* Feedback by product/category

## 2. Data Cleaning & Transformation (Power BI – Power Query)

![Image](https://github.com/quafiya-rahim/E-Commerce-Sales-And-Customer-Analytics-Dashboard/blob/main/data_cleaning.png)

* Converted columns to appropriate data types to ensure consistency and accuracy.

* Handled missing values .

* Identified duplicate records to maintain data integrity.

* Removed irrelevant/unnecessary columns and added required calculated columns to make data meaningful.

* Standardized text formats by converting lowercase to uppercase and vice versa where required.


# 3. EDA - Exploratory data analysis Key Insights

SALES PERFORMANCE OVERVIEW

1️ Top countries for orders

* Sudan leads in order count, indicating the highest demand from this region.

* Italy and Malaysia follow closely, showing strong international reach.

* Multiple countries contribute nearly equal order volumes, suggesting geographically diversified demand.

![Image](https://github.com/user-attachments/assets/24699402-e84d-46d9-a83f-fcf4f02d8821)

2️ Revenue trend over time

* Revenue shows fluctuating trends across weeks, indicating inconsistent sales performance.

* A peak revenue of ~23K suggests successful campaigns, promotions, or seasonal demand during that period.

* The sharp dip (~7.9K) highlights possible issues such as stock shortages, or reduced customer engagement.

* Overall, the trend suggests sales volatility, emphasizing the need for consistent marketing and demand forecasting.

![Image](https://github.com/user-attachments/assets/f18b83f1-6a6a-4255-aa60-114ccbeaa5d3)

3️ Product/category with highest revenue
  
  📚 Books
      Magazines, comics and non-fiction generate moderate revenue, indicating stable but lower-margin sales.
  
  📱 Electronics
      Headphones, laptops, and smart phones contribute significantly to revenue.
      Electronics emerge as high-value and high-demand categories, making them key revenue drivers.
  
  👗 Fashion
     Jackets and Jeans perform better than other fashion items.
  
  🏠 Home & Appliances
     Vaccum cleaners and table lamps generate the highest revenue in this segment.

![Image](https://github.com/user-attachments/assets/76ca97bd-7deb-4cf3-857b-271768e75f3e)

CUSTOMER BEHAVIOUR ANALYSIS

4 Most used device type

* Mobile devices dominate usage with 56% (56 users), indicating that a majority of customers prefer shopping on mobile.

* Desktop usage accounts for 44% (44 users), shows a larger portion still relies on larger screens.

* This split suggests the platform should prioritize mobile-first optimization while maintaining desktop usability.

![Image](https://github.com/user-attachments/assets/8c1cdf07-e66b-4d8c-a8bc-85bfe9d9c7d8)

5 Day with highest number of transactions


* Wednesday records the highest number of transactions (19), making it the most active shopping day.

* Transaction volume declines toward the weekend, with Saturday and Sunday at 12 transactions each.

* Mid-week engagement appears stronger than weekends.

* Customers may shop more during weekdays.

![Image](https://github.com/user-attachments/assets/beae0091-9df4-4588-bc78-cc4e319e1c9c)

6 Quantity by product

* Electronics (87 units) and Home (81 units) are the highest-selling categories by quantity.

* Books (61 units) and Fashion (57 units) show consistent but moderate demand.

* Electronics has minimal contribution.

* Electronics and Home categories indicates strong customer preference for utility.

![Image](https://github.com/user-attachments/assets/1caf8c12-5389-4506-8ebf-1236c5759bae)


7 Most used payment method

* Debit Card is the most preferred payment method.

* Net Banking and UPI (20 transactions each) closely follow, indicating strong adoption of digital payments.

* Cash on Delivery (19 transactions) remains relevant, reflecting trust-building needs in e-commerce.

* Credit Card usage is slightly lower but still significant.

* Overall, customers show a strong preference for cashless and digital payment options.

![Image](https://github.com/user-attachments/assets/7a125cf9-ed20-4696-81c1-ca9c7d6ec8b5)

DISCOUNT AND PRICING ANALYSIS

8 Average discount by category/product

📚 Books
   Magazines (50) receive higher average discounts compared to Comics and non-fiction.

📱 Electronics
   Smartwatches (35) and Laptops (18) receive lower discount compared to Headphones.

👗 Fashion
   Jeans receive the highest average discount (130) across all categories.
   Jackets (6) have minimal discounts.

🏠 Home 
   Vacuum cleaners (58) and Table lamp (52) receive relatively higher discounts.
   Toasters (18) receive lower discounts, suggesting steady demand without heavy promotions.

![Image](https://github.com/user-attachments/assets/063c6d56-000e-4cca-b7b6-5998b5ddfdea)
   

9 Average discount by device type

* Mobile users receive higher average discounts (44.9) compared to desktop users.

* Desktop users account for (33.69) of the average discount share.

![Image](https://github.com/user-attachments/assets/b65a92b0-ba13-4b64-b923-7758726a3831)



OPERATIONAL AND CUSTOMER FEEDBACKS

10 Negative feedback by product

* Smartwatch, Table Lamp, and Vacuum Cleaner receive the highest number of negative feedback.

* Jackets also show relatively high dissatisfaction compared to other products.

* Products like Comics, Headphones, and Toaster (2 each) show moderate negative feedback.

* Several products such as Jeans, Magazine, Non-fiction Books, Shoes, Smartphone, and T-Shirt record minimal negative feedback (1 each).

* This indicates that specific products contribute disproportionately to customer dissatisfaction, highlighting priority areas for quality or expectation management improvements.

![Image](https://github.com/user-attachments/assets/a86b4570-694b-4dea-b297-754b208b2deb)


11 Delivery status distribution

* In Transit orders account for the largest share (32.1%), suggesting delays or longer fulfilment cycles.

* Delivered orders (28.6%) form a significant portion, but not the majority.

* Cancelled orders represent 25%, indicating a notable level of order drop-off before completion.

* Returned orders (14.3%) show post-delivery dissatisfaction or mismatch with customer expectations.

![Image](https://github.com/user-attachments/assets/474a953c-4313-49c6-b038-94a199d2a722)


12 Feedbacks by product/category

📚 Books
   Majority of feedback falls under Excellent (5) and No Feedback (6).
   Poor feedback (4) indicates room for improvement in content quality or delivery expectations.

👗 Fashion
   Fashion shows balanced feedback distribution, with notable Poor feedback (6).

🏠 Home
   Highest number of Poor feedback (10) among all categories.
   Despite strong sales, this suggests product performance or durability issues.

📱 Electronics
   High Average and Good feedback, but also 7 Poor feedback entries, indicating mixed customer experiences.

![Image](https://github.com/user-attachments/assets/a7361d2a-a83c-4552-bb14-e0cc50892590)


## 4.Insights and Report :


* Sudan records the highest order volume, indicating strong regional demand. Italy and Malaysia follow closely, reflecting the platform’s growing international reach. The relatively even
  distribution across multiple countries suggests diversified geographic demand, reducing dependency on a single market.

* Revenue trends fluctuate significantly across weeks, highlighting inconsistent sales performance. A sharp revenue peak (~23K) suggests the impact of promotions, campaigns, or seasonal demand, while the           noticeable dip (~7.9K) indicates possible stock shortages or reduced customer engagement. This volatility emphasizes the need for stable demand-generation strategies.

* Electronics and Home & Appliances emerge as the strongest revenue-generating categories, driven by high-value products such as headphones, laptops, vacuum cleaners, and table lamps. Books and Fashion
  contribute moderate revenue, supporting volume but at lower margins.

* Most customers shop using mobile devices (56%), while desktops are still used by a large group (44%), especially for detailed or high-value purchases. This shows the platform should work smoothly on both         mobile and desktop.

* Wednesday records the highest number of transactions, with a gradual decline toward weekends. This pattern indicates stronger weekday shopping behaviour, possibly influenced by work-week browsing habits and      mid-week promotions.

* Electronics and Home products are sold the most, showing high customer demand. Books and Fashion have steady but lower sales, helping maintain product variety and customer interest.

* Most customers prefer paying by debit card, followed by Net Banking and UPI. Cash on Delivery is still used by some customers. Overall, customers are comfortable with digital payment  methods.

* Discounts are heavily concentrated in Fashion (especially Jeans) and selected Home products.
  Mobile users get higher discounts than desktop users, which helps increase mobile sales and app usage.

* A large proportion of orders remain “In Transit,” along with notable cancellation and return rates. This indicates inefficiencies in fulfilment cycles and delivery timelines, directly
  impacting customer satisfaction.

* Products such as Smartwatches, Vacuum Cleaners, and Table Lamps receive the highest negative feedback, while Home and Electronics categories show elevated “Poor” ratings despite strong sales. This highlights   a gap between sales performance and customer experience, possibly driven by quality, durability, or expectation mismatches.


# Overall Conclusion:

  This e-commerce analytics project provides a clear understanding of how customers interact with the platform, which products drive revenue, and where operational gaps exist. The analysis shows that Electronics   and Home categories are the main growth drivers, supported by a strong shift toward mobile shopping and digital payments. However, fluctuations in revenue, heavy reliance on discounts, and delivery-related       issues highlight areas that require immediate attention.
     By combining sales, customer behaviour, pricing, and feedback analysis into a single dashboard, the project enables data-driven decision-making to improve profitability, operational efficiency, and customer   satisfaction. The insights generated can directly support strategic planning, marketing optimization, and service quality improvement.


# Final Recommendations:

✅ Stabilize Revenue Performance
Run regular marketing campaigns and plan demand better to reduce weekly sales fluctuations and reliance on short-term offers.

✅ Strengthen Mobile Experience
Improve the mobile shopping experience while keeping the desktop version smooth for high-value purchases, so overall sales increase.

✅ Optimize Discount Strategy
Reduce heavy discounts on Fashion and Home products so sales increase without hurting profits.

✅ Improve Operational Efficiency
Speed up deliveries and reduce cancellations by improving logistics and order tracking.

✅ Enhance Product Quality Control
Improve quality checks for products that receive more negative feedback, especially in Home and Electronics.

✅ Leverage Mid-Week Demand
Run more offers and promotions on high-activity days like Wednesdays to boost sales.

✅ Strengthen Customer Feedback Loop
Collect and use customer feedback to fix issues and increase repeat purchases.








