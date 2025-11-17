# Finance-Analysis-Bank-Statement-dashboard
## project overview
This project analyses a personal monthly bank statement containing income, expenses, transaction categories, and running balances. It helps identify spending habits, recurring expenses, monthly income patterns, and overall financial trends.

## Dataset used
- Excel <a href= "https://github.com/vishnuwin/Finance-Analysis-Bank-Statement-dashboard/blob/main/BankStatement_ExcelProject.xlsx">Download here</a>
- Dashboard screenshort <a href= "https://github.com/vishnuwin/Finance-Analysis-Bank-Statement-dashboard/blob/main/Screenshot%202025-11-14%20130032.png">Download here</a>

## Data Cleaning & Preparation
During preprocessing, some transformations were applied for clarity and analytical convenience:

The original Description field, which contained mixed or unstructured text, was converted into a standardized Category column.
This allows transactions to be grouped clearly under categories such as Salary, Rent, Utilities, Groceries, etc.
The Date field was simplified into a Month column (Jan, Feb, Mar…).
This makes monthly grouping, summaries, and trend analysis much easier.
These transformations were done to improve the consistency, readability, and usability of the dataset for financial analysis.

The dataset contains the following columns: 
- Month
  - Month of the transaction (Jan, Feb, Mar…)  
- Category
  - Type of transaction (Salary, Rent, Utilities, Groceries, etc.)
- Pay in (£)
  - Money deposited into the account (income)  
- Withdraw in (£)
  - Money removed from the account (expense)  
- Balance (£)
  - Running balance after each transaction  

## Questions KPIs
- Which months have the highest income?
- Which categories contribute most to expenses?
- What is the saving/loss each month?
- Which spending categories occur most frequently?
- How does the balance change across months?

## Data Insights & Explanation
- January

Main income: Salary (£781.60) + Gift (£400)

Major expenses: Installment, Mobile Expense, Groceries, Entertainment, Appliances

Groceries (£1740.53) was the largest single January expense

Closing trend: Month ends with £5614.27 → £5795.27 → £5614.27 (fluctuating)

- February

Expenses increase sharply due to Rent (£2400) and multiple Utilities payments

One income row: Rent refund? (£650)

Many utility charges appear across the month

Ending balance decreases significantly to £3599.92

- March

Income: Salary (£781.60)

Expenses: Installment, Council Tax, Shopping

Council Tax (£359) is the largest

Month ends around £3559 → £3200 → £3982 → £3952

- April

Good income month: Salary + 2 Gifts

Heavy shopping and groceries

Groceries (£1740.53) is again the largest spend

Ending balance rises to £7023.65

- May

Income: Salary + Gift

Major spends: Groceries (£1740.53), Mobile Expense repeated, Installment

Appliances (£150) and Entertainment present

Ending balance approx. £9604.78

## Summary of Findings

Groceries is the most expensive recurring category (often £1740.53).

Salary (£781.60) is the primary source of income each month.

Rent and Utilities cause major balance drops in February.

Mobile Expense appears very frequently but in smaller amounts (£20–£100).

April and May show the highest final balances due to multiple income entries.

February is the most expense-heavy month due to rent and utilities.

## Conclusion

The financial activity includes a mix of necessary expenses (utilities, rent, groceries) and optional ones (entertainment, shopping).

February is the highest-expense month, significantly reducing the balance.

Groceries repeatedly account for the highest cost category across months.

Months with multiple income entries (like April, May) show a strong upward balance trend.

Tracking categories and expenses monthly helps control overspending and identify patterns


