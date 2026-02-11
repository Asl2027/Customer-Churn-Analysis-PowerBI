Customer Churn & Revenue Impact Analysis

## Overview

This project analyzes customer churn patterns and their financial impact across subscription plans. The objective was to identify high-risk customer segments, evaluate revenue loss due to churn, and assess whether customer engagement influences churn behavior.

The analysis was performed using SQL for data structuring and Power BI for KPI modeling and dashboard development.

## Dashboard Preview
![Customer Churn Dashboard](dashboard_preview.png)

## Business Objectives

* Calculate overall churn rate
* Identify which subscription plans have the highest churn
* Measure revenue lost due to churn
* Compare active vs churned customers by plan
* Analyze whether higher customer usage reduces churn

## Dataset

The dataset simulates a telecom subscription business and includes:

* **customers** (customer details, plan type, churn status)
* **usage_data** (monthly usage activity)
* **payments** (monthly revenue data)

Data was structured in MySQL and connected directly to Power BI.

## Key KPIs Created (Using DAX)

* Total Customers
* Active Customers
* Churned Customers
* Churn Rate (%)
* Total Revenue
* Revenue Lost Due to Churn
* Average Usage by Plan

## Key Insights

* Overall churn rate is approximately 50%.
* Premium plans contribute the highest revenue loss due to churn.
* Revenue impact is more significant in higher-priced subscription tiers.
* Customer usage does not show a strong negative correlation with churn across plans.

## Business Recommendations

* Prioritize retention strategies for high-revenue plans.
* Investigate non-usage factors driving churn (pricing sensitivity, service quality).
* Implement targeted engagement strategies for mid-tier customers.
  
## Tools & Skills Used

* MySQL (Database creation & data structuring)
* Power BI
* DAX (CALCULATE, DIVIDE, COUNT, filter context)
* Data Modeling
* KPI Design
* Business Insight Development

## Skills Demonstrated

* Business problem framing
* KPI definition & performance tracking
* Revenue impact analysis
* Churn analysis
* Dashboard storytelling
* Data-driven recommendations


