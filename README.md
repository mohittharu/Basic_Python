# Basic_Python
Learning and Revising  basic python concepts .
🐍 Python Basics
📌 Introduction
Python is a high-level, interpreted programming language known for its simplicity and readability. It is widely used in web development, data science, automation, artificial intelligence, and more.
This README covers the basic concepts of Python for beginners.
⚙️ Installation
Download Python from the official website: https://www.python.org
Verify installation:

python --version
or

python3 --version
▶️ Running Your First Python Program
Create a file called hello.py:

print("Hello, World!")
Run it:

python hello.py

🧱 Basic Concepts:
1️⃣ Variables
Variables store data values.

name = "Alice"
age = 25
height = 5.6
Python is dynamically typed, so you don’t need to specify data types explicitly.

2️⃣ Data Types
Common built-in data types:

int # Integer (10, -3)
float # Decimal (3.14)
str # String ("Hello")
bool # Boolean (True, False)
Example:

is_student = True

3️⃣ Input and Output

name = input("Enter your name: ")
print("Hello,", name)

4️⃣ Operators
Arithmetic: + - * / %
Comparison: == != > < >= <=
Logical: and or not
Example:

x = 10
y = 5
print(x > y and y < 10)

5️⃣ Conditional Statements

age = 18

if age >= 18:
 print("You are an adult")
else:
 print("You are a minor")

6️⃣ Loops
For Loop

for i in range(5):
 print(i)
While Loop

count = 0
while count < 5:
 print(count)
 count += 1

7️⃣ Functions
Functions help reuse code.

def greet(name):
 return "Hello " + name

print(greet("Alice"))

8️⃣ Lists
Lists store multiple values.

fruits = ["apple", "banana", "cherry"]
print(fruits[0])

9️⃣ Dictionaries
Store data as key–value pairs.

student = {
 "name": "John",
 "age": 20
}
print(student["name"])

🔟 Error Handling

try:
 x = int(input("Enter a number: "))
except ValueError:
 print("Invalid input")
📂 Project Structure (Example)

python-basics/
│
├── hello.py
├── variables.py
├── loops.py
├── functions.py
└── README.md
