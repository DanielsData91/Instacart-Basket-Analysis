# CareerFoundry-Project-Instacart-Basket-Analysis

![Instacart](https://brittainladd.com/wp-content/uploads/2023/09/Instacart-Logo-scaled.jpg)

This project focuses on uncovering hidden sales patterns using Python through exploratory data analysis of demographic information. The sales behavior of different customer profiles was descriptively analyzed and compared using a heatmap.

## 1. Project Description
As a data analyst in this Project, I conducted an exploratory analysis of customer purchasing behaviors to uncover sales patterns. The objective was to help the marketing and sales teams develop targeted strategies based on customer segmentation. Key questions included identifying the busiest shopping times, analyzing spending habits by time of day, understanding product popularity, and exploring customer loyalty and demographic trends. The insights provided informed targeted marketing campaigns and sales strategies to optimize Instacart's offerings and improve customer engagement.

## 2.Master Folder - Instacart Basket Analysis
The master folder contains 5 subfolders which store information about the project brief, the data, scripts in Jupyter Notebook, visualizations, and final reports for the client.
### 2.1. Folder - Project Management
This folder stores the project brief:

#### 2.1.2 Objective
The objective is to perform an exploratory analysis of Instacart's sales data to uncover patterns and provide insights that will help develop strategies for better customer segmentation, enabling more targeted marketing efforts.

#### 2.1.2 Context
Instacart stakeholders are interested in understanding the variety of customers and their purchasing behaviors to develop a targeted marketing strategy. They want to tailor campaigns to different customer segments to see if it impact product sales. The analysis will guide this strategy by identifying the right customer profiles and matching them with appropriate products.

#### 2.1.3 Key Questions
●The sales team seeks to identify the busiest days and hours for orders to optimize ad scheduling.

●They aim to determine peak spending times to tailor product advertisements accordingly.

●Marketing and sales want to simplify product pricing into manageable groupings.

●They are interested in identifying which product categories are most popular based on order frequency.

●Additionally, the teams want to analyze customer types and their ordering behaviors, including:

  Brand loyalty distribution among users.
  
  Variations in ordering habits based on loyalty status.
  
  Regional differences in ordering patterns.
  
  Connections between age, family status, and ordering habits.
  
  Insights from demographic data, such as age, income, and family status.
  
  Differences in ordering behaviors across various customer profiles, including order price, frequency, and product preferences.


### 2.2. Data
#### 2.2.1 Original Data
The original data sets

● Customer Data: Information about customers like name, age, family status, etc.

● Orders Data: Information about the order_id, user_id, etc.

● Products: Information about the product like product name, department_id, price, etc.

● Department: Information about the different departments at Instacart

#### 2.2.2 Prepared Data

● This folder contains data sets after wrangling and merging the original data sets


### 2.3. Scripts

This folder stores the scripts written inside Jupyter Notebooks.

### 2.4 Analysis

This folder stores the visualizations addressing the key questions of the project

### 2.5 Sent to client

This folder stores the final report in Excel format which includes

● Title Page

● Population Flow

● Consistency Checks

● Wrangling steps

● Column Derivations

● Visualizations

● Recommendations

## 3. Data Set and Sources of the Project
Data Source: The Instacart Online Grocery Shopping Dataset 2017

The data can be accessed on Kaggle here [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data)

## 4. Processing, analyzing, and modeling the data

Please refer to the script section for more details

[Script Section](https://github.com/DanielsData91/Instacart-Basket-Analysis/tree/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/03%20Scripts)

## 5. Insights to the Key Questions

### 5.1 Key Question 1: What are the busiest days of the week and hours of the day?

The busiest days of the week are Sunday, Monday, and Saturday. Considering the busiest hours of the day (between 10 am and 4 pm), let me recommend that Instacart schedule ads from 6 am to 8 am and 5 pm to 10 pm when customers place fewer orders on Wednesday and Thursday. Before 6 am and after 10 pm is not recommended, because of less traffic of customers due to their sleeping hours.

![budiest hours](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/busiest_hour_day.png)

![busiest day](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/busiest_weekday.png)

### 5.2 Key Question 2: What are particular times when people spend their money?

People spend the most money between 10 am and 4 pm. The expenditure line graphs follow the busiest hours. This time frame will inform Instacart of the type of products they advertise at these times.

![Expenditure](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/expenditure_hour.png)

### 5.3 Key Question 3: What are the most popular products?

The top 5 products are produce, dairy and eggs, snacks, beverages, and frozen food. Therefore, Instacart should provide special offers on those categories to keep drawing customers' attention and activity. Instacart should also promote and provide discounts on poorly performing departments like products from the department bulk, pets, and alcohol to increase the total revenue.

![frequency department](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/frequncy_department.png)

![Top 10 products](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Top_10_dep.png)

![Proportion](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Proportion_10_dep.png)

### 5.4 Key Question 4: What is the distribution among users in regard to their brand loyalty?

Loyal customers usually return after 8 days, whereas new customers (17 days) and regular customers  (14 days) need almost twice as long. Instacart can undertake some special activities to support customers returning, e.g:

1: Offering a certain discount to customers who come back within 10 days on the next order.
2: Customers can earn points when they order certain products, in certain time frames. Then they can use these points on the total order price of their choice or buy products with points if enough is collected.
3: Create special offer weekends, certain products are on discount but just during this time.

![loyalty](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/days_total_order_loyalty.png)

![loyalty_2](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Loyalty.png)

### 5.5 Key Question 5: Are there differences in ordering habits based on a customer's loyalty status?

Looking closely indicates that there is a difference between the count of order and loyal status (Regular = most, Loyalty = second most). Another indicator of that is that loyal customers have the lowest avg. total order price whereas regular customers the most.

Recommendation: 
Considering the order habits during the day let's recommend Instacart keeps promoting especially the high-range products in the evening (see key question 1) since they make less of the revenue. In addition to gaining more revenue due to promoting high range products as well. 
Promoting them every week more effectively can assure that regular customers (return 14 days) who place the most orders and loyal customers (return 8 days) who place the second most orders can see the advertisements.

![Count of orders](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Count_Order_Hour_loyalty.png)

![Count of orders](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/product_range_loyalty.png)

![Count of orders](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/order_loyalty.png)

### 5.6 Key Question 6: Are there differences in ordering habits based on a customer's region?

Customers based in the southern regions place the most orders in general, followed by the west and midwest. The products which are ordered amongst all regions follow the same pattern, mid. --> low --> high range products. Neither is there a big difference when looking at the avg. total order price. 

Recommendation:
Considering the order habits during the day let's recommend Instacart keeps promoting especially the high-range products in the evening (see key question 1) since they make less of revenue. In addition to gain more revenue due to promoting high range products as well across all regions.

Customers living in the southern region could be rewarded for their high spending habits by a lottery, where they can win small gifts. Customers from the northeast on the other hand could be motivated by a friendship promotion campaign e.g: they could get a discount on products or collect points when recruiting new customers. That could help to raise the total count of customers in this region, which leads to higher revenue over time.

![Region](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Count_Order_Hour_Region.png)

![Region_price](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/product_range_region.png)

![Region_loyalty](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/region_loyalty.png)

### 5.7 Key Question 7: Are there differences in ordering habits based on a customer's region?

Elderly individuals who are divorced/widowed tend to spend more on orders, possibly for convenience instead of going to the supermarket themselves. Young adults who are living with parents and siblings or single are active in ordering and spending, likely due to lifestyle choices or convenience needs.

Married customers, particularly adults and old adults, also show a strong ordering pattern, but ordering lower price products considering the avg. spending variable

Overall, there is a clear relationship between age, family status, and ordering habits, reflecting lifestyle and life stage factors. Elderly customers, young adults, and married individuals seem to have distinct patterns, with younger people and married couples placing more frequent

![Fam_age_fre](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/frequency_fam_age.png)

![Fam_age_spend](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/order_fam_age.png)

### 5.8 Key Question 8: What different classifications does the demographic information suggest?

Age classification: Observing the age group demographic reveals a clear relationship between age and income group due to the growing experience on the job, which comes along with a higher salary. Older adults have the strongest spending capacity among all age groups. Looking at the other variables,  there seems to be no relationship between family status, order frequency, and region. 

![age_income](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/age_income_comparison.png)

Income classification: Upper-income individuals are the most prevalent in Instacarts customer base. Married couples living in a middle household (1-2 dependents) account for the strongest spending force of Instacart customers.
Interesting to see is that low-spender individuals (orders below avg. purchase price of 10) are accounting 97% of the distribution in income ranges. That means, even so there is significant spending power, customers tend to buy cheaper products.

![income_fam](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/income_fam_status_comparison.png)

![income_spending](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/income_spending_comparison.png)

![income_spend_2](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/Spending.png)

Department classification: There is no difference in departments amongst region, household, age, and income

![department](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/age_dept_comparison.png)

Recommendation: 
Summarizing the insides of all classifications suggests targeting married adults and elderly customers in the middle-income range to gain more revenue by focusing on products market suitable for these two classifications to bridge between the spending capacity and actual expenditure

### 5.9 Key Question 9: What differences are the ordering habits of different customer profiles?

The heatmap suggests that age is the strongest difference between the top customer groups.

![customer_beh_freq](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/customer_behav_frequency.png)




![customer_beh_pro](https://github.com/DanielsData91/Instacart-Basket-Analysis/blob/main/Master%20Folder%20-%20Instacart%20Basket%20Analysis%2009.09.2024/04%20Analysis/Visualizations/Task%2010/customer_behav_product.png)

Recommendation:
1: Target Older Married Customers (40+):
Since they account for the highest purchase frequency, particularly in Food & Groceries and Beverages & Alcohol, focus on marketing and promotions tailored to this group. Offering loyalty programs, subscription services, or discounts on frequently purchased items could enhance retention and spending.

2: Personalized Promotions by Age Group:
Create age-specific promotions. For example, offer different bundles or deals for the 40-65 age group compared to younger customers, as their spending habits differ.

3: Cross-Sell Opportunities:
As food and beverages are popular categories, explore opportunities for cross-selling related items (e.g., household & personal care products, ) to these high-spending customer groups.

4: Encourage Higher Spending in Younger Age Groups:
The 25-40 age group has lower purchase frequency. Target them with personalized incentives, such as family-friendly offers or discounts on larger quantity purchases, to encourage more frequent buying behavior.

