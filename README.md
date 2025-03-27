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

In data analytics, conditional statements are crucial for:

📊 Data cleaning: Handling missing values, outliers, or inconsistent data.
📈 Data transformation: Creating new columns based on conditions (e.g., categorizing data).
⚡ Data analysis: Performing calculations or aggregations based on specific criteria.
⚙️ Control flow: Implementing complex logic for data processing pipelines.



# Day 7: Mastering Strings in Python | #LearningJourney

## 🧩 What Are Strings?
A string is a sequence of characters enclosed in single (‘ ’), double (“ ”), or triple (“”” “””) quotes. Strings are immutable, meaning once created, they cannot be changed.

In data analytics, strings are widely used for handling textual data, extracting information, and preparing data for analysis.

## 🚀 Key Concepts and Examples:

✅ 1️⃣ Creating Strings
python
Copy
Edit
# Using different types of quotes
single_quote = 'Hello'
double_quote = "Hello"
triple_quote = """Hello, this is a multi-line string."""
print(single_quote, double_quote, triple_quote)
✅ 2️⃣ String Indexing & Slicing
Strings are zero-indexed, meaning the first character starts at index 0.

Negative indexing helps access characters from the end.

python
Copy
Edit
text = "Data Analytics"

# Accessing first and last character
print(text[0])   # Output: D
print(text[-1])  # Output: s

# Slicing (Extracting a substring)
print(text[0:4])  # Output: Data
print(text[-9:])  # Output: Analytics
✅ 3️⃣ String Methods & Manipulation
Python provides several built-in string methods for data cleaning and transformation.

python
Copy
Edit
text = "  Power BI is Amazing!  "

print(text.upper())       # Output: "  POWER BI IS AMAZING!  "
print(text.lower())       # Output: "  power bi is amazing!  "
print(text.strip())       # Output: "Power BI is Amazing!" (removes leading/trailing spaces)
print(text.replace("Amazing", "Powerful"))  # Output: "  Power BI is Powerful!  "
print(text.split())       # Output: ['Power', 'BI', 'is', 'Amazing!']
✅ 4️⃣ String Formatting (Dynamic Strings)
When working with data-driven reports, string formatting helps in presenting dynamic content.

python
Copy
Edit
name = "Vrinda Store"
sales = 15000

# Using f-strings (Recommended)
print(f"Total sales for {name} are ${sales}.")

# Using .format()
print("Total sales for {} are ${}.".format(name, sales))

# Using % formatting (Old method)
print("Total sales for %s are $%d." % (name, sales))
✅ 5️⃣ Joining & Splitting Strings
These methods are useful for cleaning and restructuring textual data.

python
Copy
Edit
words = ["Python", "Power", "BI"]
joined_text = " ".join(words)
print(joined_text)  # Output: "Python Power BI"

text = "Python,Data,Analytics"
split_text = text.split(",")
print(split_text)  # Output: ['Python', 'Data', 'Analytics']
✅ 6️⃣ Regular Expressions (RegEx) for Pattern Matching
RegEx is a powerful tool for searching and manipulating strings in datasets.

python
Copy
Edit
import re

text = "Order ID: 12345, Customer: John Doe"

# Extracting Order ID using RegEx
order_id = re.findall(r'\d+', text)
print(order_id)  # Output: ['12345']
🔥 Why Are Strings Important in Data Analytics?
✅ Data Cleaning: Removing unwanted characters, whitespace, and correcting case formats.
✅ Feature Engineering: Extracting important text-based features from raw data.
✅ Search & Pattern Matching: Finding keywords, extracting numerical values, and standardizing data.
✅ Report Automation: Dynamically generating text-based summaries for Power BI dashboards.

💡 Real-World Use Case in Power BI & Pandas
When working with Power BI or Pandas, string manipulation is crucial for data preprocessing before analysis.

Example: Cleaning Customer Data with Pandas
python
Copy
Edit
import pandas as pd

# Sample dataset
data = {'Customer Name': [' Alice  ', 'BOB', 'John DOE  ']}
df = pd.DataFrame(data)

# Cleaning string values
df['Customer Name'] = df['Customer Name'].str.strip().str.title()

print(df)
🔹 This ensures that all names are properly formatted before analysis.

# 🚀 Key Takeaways:
🔹 Strings are fundamental for data preprocessing in Python.
🔹 Methods like strip(), replace(), split(), and join() help clean and transform textual data.
🔹 F-strings and RegEx improve efficiency when handling dynamic data.
🔹 String operations are heavily used in Power BI, Pandas, and automation scripts for analytics.


 



