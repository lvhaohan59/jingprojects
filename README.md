# Data Driven Insights for Coupon Acceptance 
Dataset explored [here:](https://github.com/lvhaohan59/jingprojects/blob/main/data/coupons.csv)
Jupyter Notebook with Code [here:](https://github.com/lvhaohan59/jingprojects/blob/main/coupon_acceptance_analysis.ipynb) 

## Objective
Customers can receive coupons via mobile phone while driving through town to attract business to local businesses. This analysis is conducted to gain insights on the customer characteristics that tend to accept these couponsfor bars and coffee businesses. The insights can be used to target specific customers to increase chances of coupon acceptance, leading to potentially increased revenue to these two type of businesses. 

## Data
The coupon dataset contains 5 different types of coupons that were sent to customers. These types include:  
**Bar**: Coupon for businesses that serves alcohol  
**Coffee House**: Coupon for businesses that serves coffee  
**Carry out & Take away**: Coupon for restaurants that provides food for takeout   
**Restaurant(<20)**: Coupon for restaurants that cost less than $20 per person per meal  
**Restaurant(20-50)**: Coupon for restaurants that cost range from $20 to $50 per person per meal  
![Barplot of coupon types and their counts](https://github.com/lvhaohan59/jingprojects/blob/main/images/coupon_barplot.png) 

***Each of the 5 coupon types have average customer acceptance rates ranging from 41% to 74% as shown below: 
![Barplot of coupon types and their average acceptance rates](https://github.com/lvhaohan59/jingprojects/blob/main/images/barplot_accept_rate.png) 

## Findings 
### Bar Coupons
1. Customers that have been to bar more than 4 times a month have acceptance rate of 76.9%, vs 37.1% for others.
2. Customers that have atleast 1 bar visit and over age of 25 have acceptance rate of 54.6%, vs 30.7% for others.
3. Customers that have atleast 1 bar visit, not traveling with kids and occupation other than farming, fishing or forestry have acceptance rate of 59.49%, vs 20.4% for others.
4. Customers that have atleast 1 bar visit, not traveling with kids and were not widowed have acceptance rate of 71.3%,
   vs 72.2% for customers that have atleast 1 bar visit and under the age of 30,
   vs 45.4% for customers who goes to cheap restaurants more than 4 times a month and has income less than 50K.
### Coffee House Coupons
1. Customers that have been to coffee shop atleast 1 times per month and has income level lower than 50K have acceptance rate of 69.8%, vs 43.1% for others.
2. Customers that have atleast 1 coffee shop visit and has atleast some college or higher education have acceptance rate of 65.5%, vs 37.3% for others.
3. Customers that have atleast 1 coffee shop visit and are not driving home have acceptance rate of 69.5%, vs 38.4% for others. 

## Actionable Insights
Given the average customer acceptance rate for Bar and Coffee coupons are 41.0% and 50.0% respectively, there are opportunities to imprve these acceptance rates by targeting customers with specific characteristics: 
1. For Bar coupons: customers that are frequent bar patrons, not driving with kids, have income level higher than 50K, and under the age of 30 have significantly higher acceptance rate than average.
2. For Coffee coupons: customers that are past coffee shop patrons, with income level lower than 50K, have college or higher education and are not driving home have significantly higher acceptance rate than average.  




