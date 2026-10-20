Week 1 · Day 2 — User Input and Type Conversion
Lesson 2
 60 minutes

Today you'll learn how to make your programs interactive.
Part A — Understanding input()
Until now, you've written programs where values are already defined:
name = "Alex"age = 25



But what if you want someone using your program to enter their own name or age?

Python provides the input() function.
name = input("What is your name? ")print("Hello,", name)



When the program runs, it waits for the user to type something.

Example:
What is your name? Alex
Hello, Alex


The important thing to remember is that input() always returns a string (str), even when the user types a number.
Part B — Type conversion
Consider this code:
age = input("Enter your age: ")next_year = age + 1



It produces an error because age is a string, while 1 is an integer.

We can fix it using int():
age = int(input("Enter your age: "))next_year = age + 1print("Next year you will be:", next_year)



Here are three useful conversion functions:
Function	Purpose	Example
int()	Convert to an integer	int("25") → 25
float()	Convert to a decimal number	float("3.5") → 3.5
str()	Convert to text	str(25) → "25"
Note that int() and float() require valid numerical input. Typing something like "hello" will cause a ValueError. We'll learn to handle those errors later.
Part C — Your first interactive calculator
income = float(input("Enter your monthly income: "))expenses = float(input("Enter your monthly expenses: "))savings = income - expensesprint("Your monthly savings are:", savings)



Now the program works with values entered by the user instead of fixed numbers.
Part D — Your exercises
Complete these three exercises without copying a full solution.

Exercise 1 — Personal greeting

Write a program that asks for someone's name and country, then prints a personalised greeting.

Exercise 2 — Age calculator

Write a program that asks for the user's age and calculates how old they'll be in five years.

Exercise 3 — Interactive salary calculator

Improve yesterday's salary calculator so it asks the user for their monthly income and expenses, then calculates monthly and annual savings.
Part E — Quick quiz
1. What data type does input() return?

int

float

str



2. Which function converts '25' into the number 25?

str()

int()

print()



3. What should you use for a salary of £2500.50?

float()

str()

bool()


Check answers
For GitHub, save today's work under week-01/lesson-02/ when you're ready. We can organise your existing files later, so don't let that interrupt your coding practice.

Your next step: Send me your code for Day 2 Exercises 1–3. I'll review it before we progress to comparison operators and conditional statements.
