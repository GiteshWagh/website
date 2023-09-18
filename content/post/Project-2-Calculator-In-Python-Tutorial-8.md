+++
authors= "Gitesh Wagh"
title = " Project 2: Calculator - Python Tutorials For Beginners #8"
date = "2023-08-14"
categories = "Python"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
+++


# **Project 4 : Calculator In Python**

This Python project is a basic calculator that performs arithmetic operations on two numbers. The project employs fundamental programming concepts like functions, if-else statements, variables, and datatypes to provide a simple calculator interface.

Here's a description of the project in simple language:

1. **Introduction and Instructions**: The program begins by displaying a message to the user. It explains how to use the calculator by entering specific keywords like 'add', 'sub', 'multi', 'div', and 'power' for different arithmetic operations.

2. **Taking User Inputs**: The program prompts the user to enter two numbers and the desired arithmetic operation. These inputs are stored in variables `x`, `y`, and `o`, respectively.

3. **Conditions and Calculations**:
   - The program uses if-else statements to determine the operation to perform based on the value of `o` (operation keyword).
   - If the operation is 'add', the program adds the two numbers and prints the result.
   - If the operation is 'sub', it subtracts the second number from the first and prints the result.
   - If the operation is 'multi', it multiplies the two numbers and prints the result.
   - If the operation is 'div', it divides the first number by the second and prints the result.
   - If the operation is 'power', it calculates the first number raised to the power of the second number and prints the result.

4. **Invalid Input Handling**: If the input for the operation is not one of the specified keywords, the program prints "Invalid Input" to indicate that the input is not recognized.

In summary, this project demonstrates a simple calculator that performs arithmetic calculations based on user inputs. The user is instructed to use specific keywords for operations, and the program responds with the calculated result or an "Invalid Input" message. This project effectively utilizes programming concepts like functions for displaying instructions, if-else statements for decision-making, variables to store user inputs, and datatypes for numeric calculations.

*********************

### Code:

````python
# 1. Notice For User
print("""\nUse 'add' for Addition.
Use 'sub' for Substraction.
Use 'multi' for Multiplication.
Use 'div' for Division.
Use 'power' for Power Calculations.\n""")

# 2.Variables And Data
x = input("Enter The 1st Number : ")
y = input("Enter The 2nd Number : ")
o = input("Enter The Operation : ")

# 3.Conditions
if (o == "add"):
    print(float(x) + float(y))

elif (o == "sub"):
    print(float(x) - float(y))

elif (o == "multi"):
    print(float(x) * float(y))

elif (o == "div"):
    print(float(x) / float(y))

elif (o == "power"):
    print(float(x) ** float(y)) 

else:
    print("Invalid Input")
````


**************************************


