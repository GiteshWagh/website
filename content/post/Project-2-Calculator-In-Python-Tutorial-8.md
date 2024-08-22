+++
authors= "Gitesh Wagh"
title = "Project 2: Calculator - Python Tutorials For Beginners #8"
date = "2023-08-14"
categories = "Python"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
feautureimage = "/images/PythonTutorial8.png"
thumbnail = "/images/PythonTutorial8.png"
toc=true
codeMaxLines=32
featureImageAlt = "Project 2: Calculator - Python Tutorials For Beginners #8"
+++

## Introduction
  
In this tutorial, we’ll create a simple calculator program in Python. The calculator will take two numbers and an operator (+, -, *, /, **) as input and perform the corresponding mathematical operation.  
  
This Python project is a basic calculator that performs arithmetic operations on two numbers. The project employs fundamental programming concepts like functions, **[If-Else Statements](https://giteshwagh.com/post/if-else-statements-in-python-tutorial-6/)**, **[Variables](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)**, and **[Datatypes](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)** to provide a simple calculator interface.

Here's a description of the project in simple language:

## Code Implementation
  
````python
print("\nWellcome to Calculator.")

# Input System
x = input("Enter First Number :- ")
y = input("Enter Second Number :- ")
a = input("Enter The Symbol Of Operation(+,-,*,/,**) :- ")

# Calculation Processor
if (a == "+"):
        print("\nLet's Calculate !!!")
        print("Addition Of",x,"and",y,"is",eval(x)+eval(y))

elif (a == "-" ):
        print("\nLet's Calculate !!!")
        print("Subtraction Of",x,"and",y,"is",eval(x)-eval(y))

elif (a == "*"):
        print("\nLet's Calculate !!!")
        print("Multiplication Of",x,"and",y,"is",eval(x)*eval(y))

elif (a== "/"):
        print("\nLet's Calculate !!!")
        print("Division Of",x,"and",y,"is",eval(x)/eval(y))

elif (a=="**"):
        print("\nSolution = ",eval(x)**eval(y)) 

else :
        print("Error : Invalid Operation.")


print("Thank You.....")
````
  
## Explanation
  
### 1. Introduction and Instructions : 
    
The program begins by taking input from user.

### 2. Taking User Inputs :  
  
The program prompts the user to enter two numbers and the desired arithmetic operation. These inputs are stored in variables **x**, **y**, and **a**, respectively.

### 3. Conditions and Calculations : 
   
- The program uses if-else statements to determine the operation to perform based on the value of `a` (operation keyword).
- If the operation is **+**, the program adds the two numbers and prints the result.
- If the operation is **-**, it subtracts the second number from the first and prints the result.
- If the operation is , __*__ it multiplies the two numbers and prints the result.
- If the operation is __/__, it divides the first number by the second and prints the result.
- If the operation is __**__, it calculates the first number raised to the power of the second number and prints the result.

### 4. Invalid Input Handling : 
   
If the input for the operation is not one of the specified symbol, the program prints "Invalid Input" to indicate that the input is not recognized.

## Usage
  
1. Run the script.  
2. Enter the first number, second number, and the operator.  
3. The result of the calculation will be displayed.    

Feel free to customize and enhance this calculator as you like!.   
Remember to test your code thoroughly and handle any edge cases you encounter. Happy coding! 😊  

## Summary  
In summary, this project demonstrates a simple calculator that performs arithmetic calculations based on user inputs. The user is instructed to use specific symbol(+,_,*,/,**) for operations, and the program responds with the calculated result or an "Invalid Input" message. This project effectively utilizes programming concepts like functions for displaying instructions, if-else statements for decision-making, variables to store user inputs, and datatypes for numeric calculations.

## Watch Video Tutorial
  
{{< youtube IwQLjzpVdxE>}}

## Recommended Content
  
1. [Variables And DataTypes - Python Tutorials For Beginners #3](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)
2. [Operators In Python - Python Tutorials For Beginners #5](https://giteshwagh.com/post/operators-in-python-tutorial-5/)
3. [Type Casting In Python- Python Tutorials For Beginners #10](https://giteshwagh.com/post/type-casting-in-python-tutorial-10/)
  
