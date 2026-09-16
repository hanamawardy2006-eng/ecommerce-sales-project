Ecommerce Sales Analysis ProjectA comprehensive data analysis project evaluating 34,500 order records (Sept 2023 – Sept 2025) to identify sales growth opportunities

,
margin performance, fulfillment speed, and return rates.  

📊 Dataset OverviewThe project contains 34,500 transactions across 7,903 customers and 24,912 products.

Key Performance Indicators (KPIs)Total Revenue: $5,865,293.05  Total Profit: $970,019.41

(16.54% Profit Rate)  Total Orders: 34,500 orders  Average Order Value (AOV): $170.01 

Overall Return Rate: 5.52% (1,903 returned orders) 

Avg Delivery Time: 4.81 days 

🗂️ Data Dictionary (Main Fields)Field NameTypeDescriptionorder_idStringUnique identifier for each order 

customer_idStringUnique identifier for each customer 

product_idStringUnique identifier for each product  

categoryStringProduct category (Electronics, Fashion, Home, etc.)  priceFloatItem unit price before discount  discountFloatDiscount percentage applied


quantityIntegerUnits ordered per transaction  total_amountFloatFinal net payment amount  profit_marginFloatEstimated order profit value 

returnedStringReturn indicator (Yes / No)  regionStringCustomer location (North, South, East, West, Central) 

delivery_time_daysIntegerFulfillment time in days  

Engineered Fields Added: gross_amount (price × qty), discount_amount, discount_tier, age_group, order_year, order_month_name.  

💡 Key FindingsElectronics: Drives 56.6% of sales ($3.32M) but has a low profit margin (10.38%) and high return rate (7.30%).  Grocery: Loss-making category (-$9,187.96 profit / -11.20% rate) requiring immediate pricing review.  Fashion: Highest return rate at 8.28%.  East Region: Weakest operational performance with slowest delivery (5.99 days) and highest return rate (5.91%).  Customer Retention: 94.0% of customers are repeat buyers (averaging 4.36 orders per customer).  
