+++
title = "💻Project 1 : Stone-Paper-Scissor Game In Python"
authors= "Gitesh Wagh"
date = "2023-08-20"
categories = "Python Projects"
tags = [
"Programming",
"Coding",
"python",
"PythonTutorial"
]
+++

--------

This Python project is a simple game known as "Stone-Paper-Scissor." It's a game of chance where a player competes against the computer in making choices among three options: "Stone," "Paper," and "Scissor." The code makes use of several fundamental programming concepts:

**1. Random Module**: The code imports the `random` module to generate a random choice for the computer. This randomness adds an element of unpredictability in this game, Which is really exciting.

**2. If-Else Statements**: The heart of the game is the series of `if-else` statements that determine the winner based on the choices made by the player and the computer. These statements create a decision tree that leads to different outcomes.

**3. Lists**: A list named `list1` is created to hold the three choices: "Stone," "Paper," and "Scissor." This list is used to randomly select the computer's choice.

**4. Variables**: The code uses variables to store the player's choice, the computer's choice, and the outcome of the game. These variables (`Players_Choice`, `computers_choice`) hold different values as the game progresses.

**5. Datatypes**: The code uses data types like strings and integers to represent and compare the choices made by the player and the computer. It also involves printing messages to the console, which involves string data types.

**How the Game Works:**

- The player is welcomed to the game, and the rules are explained.
- The computer randomly selects one of the three choices (Stone, Paper, or Scissor).
- The player is able to enter their choice.
- The code compares the player's choice and the computer's choice using `if-else` statements:
- If both choices are the same, it's a tie, and a "Tie" message is displayed.
- If the choices differ, the code checks various combinations to determine the winner. For example:
- If the computer chose "Stone" and the player chose "Paper," the player wins.
- If the computer chooses "Stone" and the player chooses "Scissor," the computer wins.
- The code prints messages indicating who won or lost based on these comparisons.

In summary, this project demonstrates a basic interactive game where the player competes against the computer in the classic game of "Stone-Paper-Scissor." The outcome is determined by a series of `if-else` statements based on the choices made by both the player and the computer. It's a simple yet engaging example of using programming concepts to create a fun and interactive experience.

*****************

### Code:

```python
print("\nWellcom to Stone-Paper-Scissor\n")
import random
list1 = ["Stone","Paper","Scissor"]
computers_choice = random.choice(list1)
print("Choose Stone-Paper-Scissor.")
Players_Choice = input("Enter Your Choice : ")
print("computer choice :",computers_choice)

if (computers_choice == Players_Choice):
print("!!!Tie!!!")

elif (computers_choice == "Stone" and Players_Choice == "Paper"):
print("!!!You Won!!!")

elif (computers_choice == "Stone" and Players_Choice == "Scissor"):
print("!!!Computer Won!!!")

elif (computers_choice == "Paper" and Players_Choice == "Stone"):
print("!!!Computer Won!!!")

elif (computers_choice == "Paper" and Players_Choice == "Scissor"):
print("!!!You won!!!")

elif (computers_choice == "Scissor" and Players_Choice == "Stone"):
print("!!!You Won!!!")

elif (computers_choice == "Scissor" and Players_Choice == "Paper"):
print("!!!Computer Won!!!")
```

********