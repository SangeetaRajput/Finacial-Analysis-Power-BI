# Finacial-Analysis-Power-BI

# Overview
This repository contains a comprehensive analysis of financial and credit card usage data, utilizing Power BI and advanced DAX calculations. The project focuses on analyzing customer behavior, credit risk, and financial performance, providing actionable insights to improve financial management and customer retention.

# Key Highlights
1.Customer Behavior Analysis

 &#8226; Identified high-risk clients with average utilization ratios exceeding 80%.

 &#8226; Created churn indicators for clients with no transactions in the past 6 months.

2.Financial Metrics

 &#8226; Running totals, 4-week moving averages, and MoM/WoW growth trends.

 &#8226; Customer Acquisition Cost (CAC) analyzed as a ratio of transaction amounts.
 
 3.Risk Indicators

 &#8226; Calculated delinquency rates and created credit risk scores for clients.

 &#8226;Flagged high-risk clients exceeding 90% of their credit limits.

4.Correlation Insights

 &#8226; Analyzed income vs. credit limit relationships.

 &#8226; Evaluated average customer satisfaction scores by card category.

# Key Questions Addressed

1.Running Total of Credit Card Transactions

2.Calculate the 4-week moving average of the creditLimit for each client.

3.Calculate the mom% growth and wow% groth on transaction amount.

4.Calculate Customer Acquisition Cost (CAC) as a Ratio of Transaction Amount.

5.Calculate the yearly average of avg_utilization_ratio for all clients.

6.Calculate the percentage of Interest_Earned compared to Total_Revolving_Bal for each client.

7.Calculate Top 5 Clients by Total Transaction Amount.

8.Identify clients whose Avg_Utilization_Ratio exceeds 80%.

9.Customer Churn Indicator: Create a KPI that flags clients who have not made any transactions (Total_Trans_Amt = 0) in the last 6 months.

10.Delinquency Rate: Calculate the percentage of clients with Delinquent_Acc > 0.

11.Credit Risk Score: Create a score for each client based on their Avg_Utilization_Ratio, Delinquent_Acc, and Total_Revolving_Bal.

12.Income vs Credit Limit Correlation: Show the correlation between Income and Credit_Limit for all clients.

13.Average Customer Satisfaction Score by Credit Card Category: Calculate the average Cust_Satisfaction_Score by Card_Category.

14.Loan Approval vs Credit Limit: Analyze how Credit_Limit affects Personal_loan approval by calculating the average credit limit for clients with and without loans.

15.High Risk Clients Flag: Create a flag for clients whose Total_Revolving_Bal exceeds 90% of their Credit_Limit and who have a high Avg_Utilization_Ratio.
 
# Tools & Technologies Used
 
 &#8226; Power BI: For creating interactive dashboards and data visualizations.
 
 &#8226; DAX: Used for advanced calculations and deriving key metrics.

 &#8226; Datasets: Combined customer and credit card data for in-depth analysis.

