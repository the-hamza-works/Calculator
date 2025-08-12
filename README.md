# Calculator made by Hamza

print("Calculator")

num1 = float(input("Enter your first digit: "))
operator = input("Choose operator? (*, +, -, /): ")
num2 = float(input("Enter your second digit: "))

if operator == "+":
    result = num1 + num2
elif operator == "-":
    result = num1 - num2
elif operator == "*":
    result = num1 * num2
elif operator == "/":
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error! Division by zero."
else:
    result = "Invalid operator!"

print("Result:", result)

# Simple Calculator (Made by Hamza)

## 📌 Description
This is a basic calculator program made in Python.  
It allows the user to perform simple arithmetic operations: addition, subtraction, multiplication, and division.

## 🚀 How to Run
1. Make sure you have Python installed on your computer.
2. Save the file as `calculator.py`.
3. Open a terminal in the folder where the file is saved.
4. Run the program:
   ```bash
   python calculator.py
# Simple Calculator (Made by Hamza)

## 📌 Description
This is a basic calculator program made in Python.  
It allows the user to perform simple arithmetic operations: addition, subtraction, multiplication, and division.

## 🚀 How to Run
1. Make sure you have Python installed on your computer.
2. Save the file as `calculator.py`.
3. Open a terminal in the folder where the file is saved.
4. Run the program:
   ```bash
   python calculator.py
example   
Calculator
Enter your first digit: 10
Choose operator? (*, +, -, /): /
Enter your second digit: 2
Result: 5.0
















