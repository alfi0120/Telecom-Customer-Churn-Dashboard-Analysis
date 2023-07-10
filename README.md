# Telecom-Customer-Churn-Dashboard-Analysis

##Table of Contents
- [Introduction](#Introduction)
- [Data Source](#Data Source)
- [Data Preprocessing](#Data Preprocessing)
- [Data Visualization](#Data Visualization)
- [Analysis](#Analysis)
- [Recommendations](#Recommendations)

## Introduction
Customer churn refers to when customers stop using a product or service from a company. Reducing customer churn can help the company's business by understanding the key factors that contribute to customer churn therefore the company can take action to retain the customers in other words reducing the churn. In this case, we have churn data from a fictional Telecommunications company in California. 

## Data Source
The dataset for this task was obtained by [Maven](https://mavenanalytics.io/data-playground?page=2&pageSize=5) 

## Data Preprocessing
Before the analysis process, I created some calculated fields which contain:
- Checking whether the customer status is churned or not: IF [Customer Status] = "Churned" THEN 1 ELSE 0 END
- Count the number of customers: COUNTD([Customer ID])
- Calculate the percentage of customers churn: SUM([Is Churn])/[Number of Customers]*100

## Data Visualization
Here is the dashboard I have created using Tableau:
| Overview |
| ----------- |
|![Customer Churn Overview](https://github.com/alfi0120/Telecom-Customer-Churn-Dashboard-Analysis/blob/d75a3138ad6648279f1aeec34b827905d3f1d2e3/Customer%20Churn%20Overview.png)|
| Customer Account Information |
| ----------- |
|![Customer Account Information](https://github.com/alfi0120/Telecom-Customer-Churn-Dashboard-Analysis/blob/d75a3138ad6648279f1aeec34b827905d3f1d2e3/Customer%20Account%20Information.png)|
| Customer Demographic Information |
| ----------- |
|![Demographic Information](https://github.com/alfi0120/Telecom-Customer-Churn-Dashboard-Analysis/blob/d75a3138ad6648279f1aeec34b827905d3f1d2e3/Demographic%20Information.png)|
| Customer Service Information |
| ----------- |
|![Service Information](https://github.com/alfi0120/Telecom-Customer-Churn-Dashboard-Analysis/blob/d75a3138ad6648279f1aeec34b827905d3f1d2e3/Service%20Information.png)|

## Analysis
From the dashboard above, there are many insights that we can get:
- The churn rate is 26.54%.
- The top 5 customer churn reasons are competitor had better devices, competitor made better offer, attitude of support person, competitor offered more data, competitor offered higher download speeds.
- Telecom lost approximately 21% of revenue due to churned customers.
- Only a few people joined with telecom since the revenue is significantly less than another customer category which is a bad sign. Besides preventing customer churn, they need to attract new customers.
- Customers who stay with telecom give higher referrals than churned customers.
- Most of the churned customers choose month-to-month contracts which is a bad sign since month-to-month contracts attract more new customers.
- Most of the churned customers are new customers. This is a bad sign since the company needs to attract new customers.
- Churned customers have fewer referrals than customers who stay.
- The age group of 65 – 80 has the highest churn rate, but they also contain the least churn rate.
- A lot of customers had an issue with fiber optic internet since it has a high customer churn rate of 40.72% and offer E whose churn rate is 52.92%.
- Most of the churned customers did not sign up for premium tech support, unlimited data, and device protection.

## Recommendations
- Convince the customers to upgrade the subscription from month-to-month to one year contract and one year contract to two years contract.
- Persuade customers to recommend telecom products to others.
- Educate the customers to subscript premium tech support and device protection.
-	Gives better offers like higher download speeds than its competitor.
-	Evaluate Offer E to the customer.
-	Solve the fiber optic internet issue.
-	Try to give a discount to the customers in order to retain the month-to-month contract customers.
