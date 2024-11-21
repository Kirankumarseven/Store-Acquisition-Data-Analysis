# Store Acquisition and Sales Analysis: Understanding Product and Discount Trends

# Description:

This project explores sales transactions from multiple stores, focusing on understanding the relationship between product purchases, discounts, and customer behavior 
to gain insights into store acquisition and performance. By analyzing key features like sales value, discount types, and product quantities, we aim to provide actionable insights for improving store strategies and customer acquisition.

# Dataset Overview:
The dataset contains the following columns, representing transactional data:

household_key: Unique identifier for a customer or household making the purchase.
BASKET_ID: Unique identifier for a specific purchase (basket).
DAY: Date of the transaction.
PRODUCT_ID: Unique identifier for the product purchased.
QUANTITY: Quantity of the product purchased in a specific transaction.
SALES_VALUE: Total monetary value of the purchase.
STORE_ID: Identifier for the store where the purchase was made.
RETAIL_DISC: Discount offered by the retailer on the product.
WEEK_NO: Week number of the year when the transaction occurred.
COUPON_DISC: Discount provided via a coupon used by the customer.
COUPON_MATCH_DISC: Additional discount if the coupon matches certain conditions or products.
Key Objectives:
# Analyze Sales Performance:

Explore trends in sales values, quantities, and product performance across different stores.
Identify the products contributing the most to overall sales and those underperforming.
Understand Discount Impacts:

Assess how different types of discounts (retail, coupon, and coupon match) influence customer purchasing behavior.
Analyze the correlation between the level of discount and the quantity or sales value of purchased items.
Customer Behavior Analysis:

Investigate how frequently households make purchases and how these purchases vary by day, week, and store.
Study customer response to discount promotions and coupon usage to optimize marketing strategies.
Store Acquisition Insights:

Compare sales data across stores to determine the most successful stores in terms of sales value and customer retention.
Evaluate the effectiveness of discount strategies in attracting and retaining customers across different stores.
Data Preparation for Predictive Modeling:

Clean the data to remove any inconsistencies and missing values.
Create aggregated features, such as weekly total sales, average discount per transaction, and customer purchasing frequency.
Prepare the data for machine learning models focused on predicting sales, customer acquisition, and optimal discount strategies.
Analysis Techniques:
# Exploratory Data Analysis (EDA):

Visualizations of sales trends over time, product popularity, and the impact of discounts.
Heatmaps and correlation matrices to identify relationships between variables like sales, discounts, and quantities.
Discount Effect Analysis:

Statistical testing (e.g., ANOVA) to understand if there’s a significant difference in sales when different types of discounts are applied.
Regression models to predict sales value or quantity based on discount levels.

# Customer Segmentation:

Segmentation of households based on their purchasing behavior, frequency, and responses to promotional offers.
Clustering techniques (e.g., K-means) to identify high-value customers and target them with personalized discount offers.
Tools and Technologies Used:
Programming Language: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
Tools: Jupyter Notebook, Tableau (for visualizations, if applicable)
# Expected Outcomes:
Insights into Store Performance:
Understand how different stores perform in terms of sales, customer engagement, and discount effectiveness.

Optimal Discount Strategy:
Identify which types of discounts (retail, coupon, coupon match) drive the most sales and customer retention.

# Customer Acquisition and Retention:
Develop recommendations for customer acquisition strategies based on discount effectiveness and customer behavior trends.

# Conclusion:
This project provides valuable insights into the relationship between product sales, discounts, and customer behavior, 
particularly focusing on store acquisition strategies. By understanding how different discount strategies impact sales and customer retention, 
businesses can optimize their marketing efforts, improve customer acquisition rates, and ultimately drive more revenue.
