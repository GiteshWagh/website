+++
title = "💻Project 2 : Secure Profile Management System In Python"
authors= "Gitesh Wagh"
date = "2023-08-21"
categories = "Python Projects"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
+++

# Project 2 : Secure Profile Management System

Description:
The "Secure Profile Management System" is a Python project that demonstrates essential programming concepts, including functions, if-else statements, variables, and data types, to create a secure login and profile management system. This project provides users with the ability to set up their profiles, including an ID and password, and then log in securely using the provided credentials.

Key Concepts Utilized:  

(1) Functions: The project uses functions to encapsulate and organize code blocks, enhancing readability and maintainability.  

(2)If-Else Statements: If-else statements are used to make decisions based on the provided input, enabling the system to validate user credentials and determine access rights.  

(3 )Variables and Data Types: Variables are employed to store and manipulate data, including user IDs and passwords. The project utilizes data types effectively for user input and comparison.  

Features:  

Profile Setup: Users can set up their profiles by entering a unique ID and a secure password.  

Secure Login: The system validates user input and provides access only to authorized users with correct credentials.  

User Feedback: The project offers clear feedback to users about successful profile setup, login, and any errors encountered, improving user experience.  

Conditional Control: The use of if-else statements enables conditional control flow, allowing the system to respond differently based on input conditions.  

Target Audience:  
 
Beginner Python learners looking to understand and practice fundamental programming concepts.
Individuals interested in building simple authentication systems using Python.  

Usage:  
1. Run the program.  
2. Set up your profile by entering a unique ID and a secure password.  
3. Log in by providing the previously set ID and password.  
4. Experience the program's responses based on the entered credentials.  

By exploring this project, users can gain hands-on experience in applying functions, if-else statements, variables, and data types to create a basic yet functional profile management and authentication system in Python.  

*************

### Code:

````python
print("\nSet Your Profile.")
ID = input("Enter Your ID 👉 : ")
password = input("Set The Password 👉 : ")

print("✔ Account Setup is complete ✔")

print("\nLog In Now,")
x = input("Enter ID Here 👉 : ")
y = input("Enter Passcode Here 👉 : ")

if (x == ID):
    print("Wellcome",ID,'👋,')

else:
    print("❌Invalid ID❌")

if(y==password):
    print("✔Correct password. Access Allowed✔")

else:
    print("❌Invalid Password❌")
````

******************