Part 1 — Reviewing your Python exercises
Exercise 1: Personal information
Logic correct
You wrote:
name = "alex"
age = 25
country = "uk"
print(name)
print(age)
print(country)



This is valid Python when each statement is on a separate line, as shown above.

You successfully used:
- Strings for name and country.
- An integer for age.
- print() to display values.
To match the requested output format, you could improve it using:
print("Name:", name) print("Age:", age) print("Country:", country)


This produces:
Name: alex
Age: 25
Country: uk


Exercise 2: Salary calculator
Monthly calculation correct
Your solution:
income = 2800 expenses = 1650 savings = income - expenses



The calculation is correct, but you haven't yet calculated annual savings or printed the results.

Here's the completed version:
income = 2800 expenses = 1650 
monthly_savings = income - expenses
annual_savings = monthly_savings * 12

print("Monthly savings:", monthly_savings)
print("Annual savings:", annual_savings)



Monthly savings
£1,150

Annual savings
£13,800


Exercise 3: Daily sales analysis
Needs correction
Your idea of adding sales and dividing by the number of days is correct. However, there are three things to fix.
1. Python variable names cannot contain spaces. Use total_sales, not total sales.
2. We only have five days of sales, Monday through Friday, not seven.
3. Expressions like monday.sales refer to an attribute named sales on an object called monday. For this exercise, we haven't created such objects, so use simple variables instead.
Here's the corrected version:
monday = 120tuesday = 150wednesday = 90thursday = 200friday = 140total_sales = monday + tuesday + wednesday + thursday + fridayaverage_daily_sales = total_sales / 5print("Total sales:", total_sales)print("Average daily sales:", average_daily_sales)



Total sales
£700

Average daily sales
£140


Sales by day
Your first example of visualising a dataset.

This is an early example of data analysis: calculate a total, calculate an average, and compare the observations.

Your next challenge: Can you modify your Exercise 3 code to calculate the difference between Thursday's sales and Wednesday's sales?










Part G — Your first mini-project
Project 1: Monthly Budget Analyser

Build a Python program that stores monthly income, rent, food, transport, and entertainment costs, then calculates:
- Total monthly expenses
- Money remaining after expenses
- Percentage of income saved
Starter code:
income = 3200 rent = 1100 food = 350 transport = 180 entertainment = 120
# Your task:# 1. Calculate total expenses # 2. Calculate savings # 3. Calculate savings percentage # 4. Print all three results



Hint: Savings percentage = savings / income * 100. Assume income is greater than zero.

income = 3200
rent = 1100
food = 350
transport = 180 
entertainment_costs = 120

monthly_expenses = rent + food + transport + entertainment_costs
annual_expenses = monthly_expenses * 12
savings = income - monthly_expenses 
savings_percentage = savings / income * 100 


print("Monthly_expenses:", monthly expenses)
print("Savings:", savings)
print("Savings percentage:", savings percentage)

Monthly Budget Analyser
Your code review
Almost correct

Calculation logic
Correct

Python syntax
2 errors



Your calculations are all correct:
monthly_expenses = rent + food + transport + entertainment_costsannual_expenses = monthly_expenses * 12savings = income - monthly_expensessavings_percentage = savings / income * 100



You've even added annual_expenses, which wasn't required. That's a useful extension.
The two mistakes
You wrote:
print("Monthly_expenses:", monthly expenses)print("Savings percentage:", savings percentage)



Python does not allow spaces in variable names. You defined monthly_expenses and savings_percentage, so you must use those exact names.
Corrected code
income = 3200rent = 1100food = 350transport = 180entertainment_costs = 120

monthly_expenses = rent + food + transport + entertainment_costs
annual_expenses = monthly_expenses * 12
savings = income - monthly_expenses
savings_percentage = savings / income * 100
print("Monthly expenses:", monthly_expenses)
print("Annual expenses:", annual_expenses)
print("Savings:", savings)
print("Savings percentage:", savings_percentage)



Your expected output:
MONTHLY BUDGET RESULTS
Monthly expenses
£1,750

Annual expenses
£21,000

Monthly savings
£1,450

Savings rate
45.31%



Your program prints the unrounded savings percentage, 45.3125. Later, I'll show you how to format it as 45.31%.
