🐍 Python Programming Basics

«A beginner-friendly guide to start your Python programming journey from zero.»

---

📖 Table of Contents

1. Python & VS Code Setup
2. First Python Program
3. Variables
4. Data Types
5. Input & Output
6. Arithmetic Operators
7. String Operations
8. Mini Projects
9. Practice Challenges
10. Learning Tips

---

🚀 Step 1: Python & VS Code Setup

Install Python

- Download Python 3.11+ from the official website.
- During installation, enable:

☑ Add Python to PATH

Install VS Code

- Download and install Visual Studio Code.
- Install the Python extension.

Verify Installation

python3 --version

Expected Output:

Python 3.x.x

---

👋 Step 2: Your First Python Program

Create a file named:

hello.py

Write:

print("Hello, Python!")

Run:

python3 hello.py

Output:

Hello, Python!

What Happens?

- Python executes code from top to bottom.
- "print()" displays output on the screen.

---

📦 Step 3: Variables

Variables store information that can be used later.

age = 25
name = "Deepak"
height = 5.11

print(age)
print(name)
print(height)

Best Practices

✅ Use meaningful names

student_name = "Shyam"

❌ Avoid

x = "Shyam"

---

🔢 Step 4: Data Types

Type| Description| Example
int| Whole Numbers| 10
float| Decimal Numbers| 3.14
str| Text/String| "Hello"
bool| True/False| True

Example:

age = 18
pi = 3.14
name = "Python"
is_learning = True

Check Type:

print(type(age))

---

⌨️ Step 5: Input & Output

Taking User Input

name = input("Enter your name: ")
print("Hello", name)

Numeric Input

age = int(input("Enter your age: "))
print("Next year you'll be", age + 1)

---

➕ Step 6: Arithmetic Operators

a = 10
b = 3

print(a + b)    # Addition
print(a - b)    # Subtraction
print(a * b)    # Multiplication
print(a / b)    # Division
print(a // b)   # Floor Division
print(a % b)    # Modulus
print(a ** b)   # Exponentiation

Operator| Meaning
+| Add
-| Subtract
*| Multiply
/| Divide
//| Floor Division
%| Remainder
**| Power

---

🔤 Step 7: String Operations

first = "Data"
second = "Analyst"

print(first + " " + second)
print("Hi " * 3)
print(len(first))

Output:

Data Analyst
Hi Hi Hi
4

---

🎯 Step 8: Mini Projects

1️⃣ Simple Calculator

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)

if num2 != 0:
    print("Division:", num1 / num2)
else:
    print("Division not possible")

---

2️⃣ Temperature Converter

celsius = float(input("Enter Celsius: "))

fahrenheit = (celsius * 9 / 5) + 32

print("Fahrenheit:", fahrenheit)

---

3️⃣ Age After 5 Years

age = int(input("Enter your age: "))

future_age = age + 5

print("Age after 5 years:", future_age)

---

🎁 Bonus Project: Area of Rectangle

length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print("Area =", area)

---

🏆 Practice Challenges

Try creating these on your own:

- BMI Calculator
- Number Guessing Game
- Currency Converter
- Simple Interest Calculator
- Student Grade Calculator

---

💡 Learning Tips

✅ Code every day

✅ Type code manually

✅ Experiment with examples

✅ Read error messages carefully

✅ Practice at least 10 coding questions daily

---

🎯 Learning Roadmap

Python Basics
    ↓
Functions
    ↓
OOP
    ↓
File Handling
    ↓
DSA
    ↓
SQL & DBMS
    ↓
Machine Learning
    ↓
NLP
    ↓
Transformers
    ↓
LLM Engineering

Happy Coding! 🚀