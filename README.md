# Credit card user segmenter

## Goal
The goal of the project is to *make suggestions on benefits that the credit card company may want to offer to its users based on their credit card activity*

## Strategy
I use PCA and K-Means clustering to find clusters of users with differential patterns of credit card usage.

## Data
The data consists of a csv file with 8950 rows (one for each cardholder) organized in columns with descriptive headers.

Key to column labels: 
* CUST_ID : Credit card holder ID
* BALANCE : Monthly average balance (based on daily balance averages)
* BALANCE_FREQUENCY : Ratio of last 12 months with balance
* PURCHASES : Total purchase amount spent during last 12 months
* ONEOFF_PURCHASES : Total amount of one-off purchases
* INSTALLMENTS_PURCHASES : Total amount of installment purchases
* CASH_ADVANCE : Total cash-advance amount
* PURCHASES_ FREQUENCY : Frequency of purchases (percentage of months with at least one purchase)
* ONEOFF_PURCHASES_FREQUENCY : Frequency of one-off-purchases
* PURCHASES_INSTALLMENTS_FREQUENCY : Frequency of installment purchases
* CASH_ADVANCE_ FREQUENCY : Cash-Advance frequency
* AVERAGE_PURCHASE_TRX : Average amount per purchase transaction
* CASH_ADVANCE_TRX : Average amount per cash-advance transaction
* PURCHASES_TRX : Average amount per purchase transaction
* CREDIT_LIMIT : Credit limit
* PAYMENTS : Total payments (due amount paid by the customer to decrease their statement balance) in the period
