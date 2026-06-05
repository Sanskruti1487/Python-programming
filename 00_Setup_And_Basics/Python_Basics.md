✅ Python Programming Basics 🐍💻

📌 Step 1: Install Python & VS Code
• Download Python 3.11+ from python.org
• During install, check ✅ Add Python to PATH
• Install VS Code
• In VS Code, install the Python extension
To check:
Open terminal → Type: python --version
You should see something like: Python 3.x.x

📌 Step 2: Your First Python Program
Create a file: hello.py
Paste this code:

print("Hello, Python")

Run it in terminal: python hello.py
🧠 Python runs code top to bottom
🖨️ print() displays output on the screen

📌 Step 3: Variables
Variables store values.

age = 25    
name = "Shyam"    
height = 5.11    
print(age, name, height)

✔️ No need to declare types — Python figures it out
✔️ Use lowercase names with underscores

📌 Step 4: Data Types
• int → Whole numbers (e.g., 10)
• float → Decimals (e.g., 3.14)
• str → Text (e.g., "hello")
• bool → True / False

To check type:

x = 10    
print(type(x))

📌 Step 5: Input & Output
Take input from user:

name = input("Enter your name: ")    
print("Hello", name)

Convert string input to number:

age = int(input("Enter age: "))    
print("Next year you'll be", age + 1)

📌 Step 6: Arithmetic Operators

a = 10    
b = 3    
print(a + b)      # Add    
print(a - b)      # Subtract    
print(a * b)      # Multiply    
print(a / b)      # Divide    
print(a // b)     # Floor division    
print(a % b)      # Remainder

📌 Step 7: String Operations

first = "Data"    
second = "Analyst"    
print(first + " " + second)     # Concatenate    
print("Hi " * 3)                # Repeat    
print(len(first))              # Length

📌 Step 8: Practice Programs
1️⃣ Simple Calculator
→ Input 2 numbers, show sum, difference, product, division

2️⃣ Temperature Converter
→ Input Celsius, convert to Fahrenheit
F = (C * 9/5) + 32

3️⃣ Age After 5 Years
→ Input current age, print age after 5 years

Here is the detailed code for each project:

📌 Project 1. Simple Calculator

num1 = float(input("Enter first number: "))  
num2 = float(input("Enter second number: "))  
  
print("Addition:", num1 + num2)  
print("Subtraction:", num1 - num2)  
print("Multiplication:", num1 * num2)  
  
if num2 != 0:  
    print("Division:", num1 / num2)  
else:  
    print("Division not possible")

📌 Project 2. Temperature Converter (Celsius to Fahrenheit)

celsius = float(input("Enter temperature in Celsius: "))  
fahrenheit = (celsius * 9 / 5) + 32  
print("Temperature in Fahrenheit:", fahrenheit)

📌 Project 3. Age After 5 Years

age = int(input("Enter your age: "))  
future_age = age + 5  
print("Your age after 5 years:", future_age)

🎁 Bonus Practice – Area of a Rectangle

length = float(input("Enter length: "))  
width = float(input("Enter width: "))  
area = length * width  
print("Area of rectangle:", area)

💡Useful Tips
• Run each program
• Change input values
• Break it on purpose and fix it

🧠 Daily Rule:
• Code at least 60 mins
• Type every line manually
• Don’t copy-paste — build muscle memory

