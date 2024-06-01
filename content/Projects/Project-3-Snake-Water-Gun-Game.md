+++
title = "💻Project 3 : Snake-Water-Gun Game In Python"
authors= "Gitesh Wagh"
date = "2023-08-22"
categories = "Python Projects"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
+++

# **Project 3 : Snake-Water-Gun Game In Python**

This Python project is a simple game called "Snake-Water-Gun." It utilizes several fundamental programming concepts to create an interactive game where a player competes against the computer. The project showcases the use of the random module, if-else statements, lists, variables, and basic data types.

Here's an explanation of the code in easy-to-understand language:

1. **Introduction**: The program begins with a welcoming message, introducing the user to the "Snake-Water-Gun" game.

2. **Importing the Random Module**: The code imports the `random` module, which allows the program to randomly select an option for the computer's choice.

3. **Creating the List of Choices**: A list named `list1` is created containing the three choices: "Snake," "Water," and "Gun." These are the options available for both the player and the computer.

4. **Computer's Choice**: The computer's choice is generated randomly from the `list1` using the `random.choice()` function. This represents the computer's move in the game.

5. **Player's Choice**: The program prompts the player to enter their choice among "Snake," "Water," or "Gun." The player's choice is stored in the `Players_Choice` variable.

6. **Comparison and Result**:
   - The program compares the computer's choice and the player's choice using a series of `if-else` statements.
   - If both choices are the same, it results in a tie.
   - If the choices differ, the program checks different combinations of choices to determine the winner. For instance:
     - If the computer chose "Snake" and the player chose "Water," the computer wins.
     - If the computer chose "Snake" and the player chose "Gun," the player wins.
     - And similarly for other combinations.
   - Depending on the comparisons, the program prints out who won or if it's a tie.

7. **Outcome Printing**: The program displays the computer's choice and then prints the outcome of the game based on the comparison made earlier. If the player enters an option other than "Snake," "Water," or "Gun," the program indicates that the input is invalid.

In summary, this project demonstrates a basic interactive game where the player competes against the computer in the "Snake-Water-Gun" game. The code randomly selects the computer's choice, takes the player's input, compares the choices using `if-else` statements, and then displays the winner or a tie. This project effectively employs essential programming concepts like randomness, conditional statements, list handling, variables, and basic data types.

********************

### Code:

````python
import random

print("\nWellcome To Snake-Water-Gun Game !!!\n")


list1 = ["Snake", "Water","Gun"]
Computers_Choice = random.choice(list1)
print("{ Snake-Water-Gun }")
Players_Choice = input("Enter Option : ")
print(f"Computer choose : ",Computers_Choice)

if (Computers_Choice == Players_Choice):
    print("!!!Tie!!!")
   

elif (Computers_Choice == "Snake" and Players_Choice == "Water"):
    print("!!!Computer Won!!!") 

elif (Computers_Choice == "Snake" and Players_Choice == "Gun"):
    print("!!!You Won!!!")



elif (Computers_Choice == "Water" and Players_Choice == "Snake"):
    print("!!!You Won!!!") 

elif (Computers_Choice == "Water" and Players_Choice == "Gun"):
    print("!!!Computer Won!!!")


elif (Computers_Choice == "Gun" and Players_Choice == "Snake"):
    print("!!!Computer Won!!!") 

elif (Computers_Choice == "Gun" and Players_Choice == "Water"):
    print("!!!You Won!!!")

else :
    print("Invalid Input")
````

******