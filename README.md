# Power-BI-Python-Masterclass
## Day 3 Built-in Functions 

## What are Built-in Functions?

Python provides several built-in functions that allow us to perform common tasks without writing extra code. These functions enhance productivity and make code more readable.

## Some Key Built-in Functions I Learned Today:
✅ input function() – Returns the output of an object 
🔹 name = input("please enter your name")
 print("Hello", name)

 Output 
 please enter your name Ankit
 Hello Ankit

✅ len() – Returns the length of an object (string, list, tuple, etc.)
🔹 Example: len([10, 20, 30]) → 3

✅ Pow function() – Returns the power of an object (2, 3.)
🔹 result = pow(2,3)
 print(result)
 Output: 8

✅ type() – Returns the type of an object
🔹 Example: type(5.7) → float

✅ sum() – Adds all elements of an iterable (list, tuple, etc.)
🔹 Example: sum([10, 20, 30]) → 60

✅ sorted() – Sorts elements of a sequence in ascending order by default
🔹 Example: sorted([5, 2, 9, 1]) → [1, 2, 5, 9]

✅ zip() – Combines multiple iterables into tuples
🔹 Example: list(zip([1, 2, 3], ['a', 'b', 'c'])) → [(1, 'a'), (2, 'b'), (3, 'c')]

✅ max() & min() – Return the maximum and minimum values from an iterable
🔹 Example: max([5, 10, 3]) → 10, min([5, 10, 3]) → 3

✅ float() – Returns the float value of a number
🔹 Example: abs(6) → 6.0

✅ complex() – Returns the complex value of a number
🔹 Example: abs(2, 8) → 2+8j

✅ eval() – Returns the evaluate value of a number
🔹 Example: eval(5/2+3.5) → 6

✅ abs() – Returns the absolute value of a number
🔹 Example: abs(-7) → 7

✅ binary() – Returns the binary value of a number
🔹 Example: x = bin(18934672376973698752)
 print(x)
 Output: 0b10000011011000101011110000011010011100111111010110010011011000000


✅ round() – Rounds a number to the nearest integer or specified decimal places
🔹 Example: round(4.567, 2) → 4.57

✅ map() – Applies a function to all items in an iterable
🔹 Example: list(map(lambda x: x*2, [1, 2, 3])) → [2, 4, 6]

✅ filter() – Filters elements from an iterable based on a condition
🔹 Example: list(filter(lambda x: x > 5, [2, 8, 3, 10])) → [8, 10]


## Why Are These Important for Data Analytics?
In data analytics, built-in functions help in:
📊 Data manipulation (sorting, filtering, aggregating)
📈 Cleaning and transforming datasets
⚡ Improving efficiency in data processing


# Masterclass Day 4 : Conditional Statements

# What are Conditional Statements?

Conditional statements allow your code to make decisions based on whether certain conditions are true or false. They enable you to execute different blocks of code depending on these conditions.

# 🚀 Key Concepts and Examples:

## ✅ if statement: Executes a block of code if a condition is true.

## ✅ elif statement (else if): Checks another condition if the previous if condition is false. You can have multiple elif statements.

## ✅ else statement: Executes a block of code if none of the preceding if or elif conditions are true.

## ✅ Nested Conditional Statements: You can put if, elif, and else statements inside other conditional statements for more complex logic.

# 🔥 Why Are These Important for Data Analytics?

Day 4: Mastering Python Conditional Statements | #LearningJourney

I'm on Day 4 of my Python + Power BI Masterclass with Swati Dhote, and today's focus was on Conditional Statements in Python! These are fundamental for controlling the flow of execution in our code, allowing us to make decisions based on different conditions.

🔹 What are Conditional Statements?
Conditional statements allow us to execute specific blocks of code only if certain conditions are met.  They introduce logic and decision-making into our programs.

🚀 Key Conditional Statements I Learned Today:

✅ if statement: Executes a block of code if a condition is true.

Python

x = 10
if x > 5:
    print("x is greater than 5") 
✅ else statement: Executes a block of code if the if condition is false.

Python

x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
✅ elif statement (else if): Allows for multiple conditions to be checked sequentially.

Python

x = 7
if x > 10:
    print("x is greater than 10")
elif x > 5:
    print("x is greater than 5 but not greater than 10")
else:
    print("x is not greater than 5")
✅ Nested Conditional Statements: Placing conditional statements inside other conditional statements for more complex logic.

Python

x = 10
y = 5
if x > 5:
    if y < 10:
        print("x is greater than 5 and y is less than 10")
🔥 Why Are These Important for Data Analytics?

In data analytics, conditional statements are crucial for:

📊 Data cleaning: Handling missing values, outliers, or inconsistent data.
📈 Data transformation: Creating new columns based on conditions (e.g., categorizing data).
⚡ Data analysis: Performing calculations or aggregations based on specific criteria.
⚙️ Control flow: Implementing complex logic for data processing pipelines.
 



