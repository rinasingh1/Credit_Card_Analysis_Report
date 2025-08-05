# Credit_Card_Analysis_Report
Power BI
## Credit Card Weekly Status Report
## Content
<br>

•	Project Objective
<br>
•	 Data from SQL
<br>
•	 Dax
<br>
•	 Dashboard
<br>
•	 Insights

## Objective 
To develop a comprehensive credit card weekly dashboard that provides real time insights into key performance metrics and trends enabling stakeholders to monitor and analyse credit card operations effectively.
## Data from SQL
<br>
•	creating tables in SQL
<br>
•	preparing a CSV file
<br>
•	Importing a  CSV file into SQL

## DAX 
Calculated columns 
<br>

Two calculated columns are created in the credit_card_detail Table
<br>
•	Revenue: annual_fees + total_trans_amt + interest_earned
<br>
•	Week_num2: using weeknum function – date[week_start_date]
<br>

Using Switch() function two calculated columns are created in the customer_detail Table
<br>
•	a) Age_group – the ages are kept in a bucket 
<br>
•	b) Income_group – incomes are kept in a bucket

Measures:
<br>
•	Current_customer_count
<br>
•	Current_transaction_amount
<br>
•	Current_transaction_count
<br>
•	Current_week_revenue
<br>
•	Previous_customer_count
<br>
•	Previous_transaction_amount
<br>
•	Previous_transaction_count
<br>
•	Previous_week_revenue
<br>
•	WoW_customer_count
<br>
•	WoW_revenue
<br>
•	WoW_transaction_amt
<br>
•	WoW_transaction_count

<img width="909" height="498" alt="Screenshot 2025-08-05 094743" src="https://github.com/user-attachments/assets/b1519b14-a8f9-4daa-ae9d-22468effa4a4" />

## Dashboard 
<img width="2000" height="1156" alt="image" src="https://github.com/user-attachments/assets/020f6e01-21ea-4908-bbfa-54dbbd64f565" />




## Project Insights

Week on Week changes
<br>

•	Revenue increased by 28.8%
<br>
•	Total transaction amt and count increased by 35.04% and 3.39%
<br>
•	Customer count increased by 12.80%
<br>
•	Overall revenue is 57M
<br>
•	Total interest is 8M
<br>
•	Total transaction amount is 46M
<br>
•	Male customers are contributing more to revenue that is 31M than female customers that is 26M
<br>
•	Blue and Silver credit cards are contributing 93% of overall transactions.
<br>
•	TX, NY and CA contributing to 73.05%
<br>
•	Overall activation rate is 56.3%
<br>
•	Overall delinquent rate is 6.06%

<img width="909" height="498" alt="Screenshot 2025-08-05 094743" src="https://github.com/user-attachments/assets/b1519b14-a8f9-4daa-ae9d-22468effa4a4" />










