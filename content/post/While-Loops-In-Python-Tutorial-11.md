+++
authors= "Gitesh Wagh"
title = "While Loops In Python- Python Tutorials For Beginners #11"
date = "2024-07-22"
categories = "Python"
tags = [
    "while loops in python",
    "while loops in python program",
    "while loops",
    "python",
    "Python While Loops",
    "What is the while loop in Python?",
    "What is a while loop example?",
    "What are loops in Python?",
    "What is the difference between a for and while loop?",
    "What is called do-while loop?",
    "What is the syntax of loop?"
]
description = ""
featureImage = "/images/PythonTutorial11/PythonTutorial11.png"
thumbnail = "/images/PythonTutorial11/PythonTutorial11.png"
toc=true
featureImageAlt = "While Loops In Python- Python Tutorials For Beginners #11"
+++

## What Is The While Loops In Python ?

In [Python](https://www.python.org/), The **WHILE LOOP** works on the **CONDITION** given by the coder and the loop runs until the condition is **TRUE**. Whenever the condition becomes false, Then the loop will stop. So this is the mechanism of While Loop.

  

## How To Create While Loops In Python ?
  
So first of all, We use the **"while"** Keyword to define the type of loop. After that, enter the condition in the **parenthesis bracket** or use **space** after the keyword. Both methods work exactly the same.


After the condition, **Use a semicolon** and press enter to enter in the code block of the while loop. Here, You will write a code that runs when the condition of the while loop is **True**, But it is important to check the **Indentation** of the code block. These are some practical examples that teach you way better than me.

<img title="Graph of While Loops In Python" alt="Graph of While Loops In Python" src="/images/PythonTutorial11/WhileLoops.png">

  

## Components Of While Loops
  

### Condition: 
Condition is a boolean expression. The loop continues to run as long as this condition evaluates to True.
  

### Code Block: 
Code Block is the set of statements that will be executed repeatedly if the contion is true. Make sure to update the variables involved in the condition within this block to eventually make the condition False, otherwise, you’ll create an infinite loop.
  

## Examples Of While Loop
  

### Example 1 : Infinite Loop

````Python
# Infinite Loops

a=2
while a==2:
    print("Hello")
```` 
  
In this example, I created an infinite loop when I ran it, This code prints the **"hello"** word again and again until you close or kill your Python terminal. To create an infinite loop, I made an "a" variable whose value is 2 and I created a while loop. Here, **(a==2)** this condition is always True, There are **no increments** and **decrements** in the value of "a" so the value of Variable "a" will never change and conditions remain always true.
  
  
### Example 2 : Finite Loop
  
````Python
# Finite Loops

a = 1
while(a<=10):
     print(a,"Hello")
     a=a+1
print(a)
````

This is a finite loop. After running the while loop the **value of Variable "a" increases by 1.** So, After some time the value of 'a' becomes more than 10 and the loop will stop, So this is a concept of a finite loop.
  

### Example 3 : While Loop With Pass Keyword
````Python
# Pass KeyWord

while(a>=10):
     pass

# Pass Keyword works as placeholder in Loops & Functions
````

This is an example of a while loop with a pass keyword. The **pass keyword** works as a placeholder in **functions** and **loops**. With the help of pass keyword Python does not show any error because of incomplete loop. Now, we add code here whenever we want. Similarly, the pass keyword works in functions.
  

### Example 4 : While Loop With Else Statements
````Python
# While Loops With Else
a = 0
while(a<=2):
    print('Hello')
    a=a+1

else:
    print("Ended")

# Else always runs for finite loops
````

We learnt about the if-else statement in previous blogs and the Else statement runs whenever the condition of while loops becomes false. Every time else statement will executes if the loop is finite.
  

## What is the difference between a for and while loop?
  

### For Loop
* **Initialization:** Typically, the initialization is done within the loop statement.
  
* **Condition:** The condition is checked before each iteration.
  
* **Update:** The update statement is optional and executed after each iteration.
  
* **Use Case:** Best used when the number of iterations is known in advance, such as iterating over a range or a collection.
  
**[Click Here To Learn More About For Loops In Python](https://giteshwagh.com/post/for-loops-in-python-tutorial-9/)**
  

### While Loop 
  
* **Initialization:** The initialization is done outside the loop.
  
* **Condition:** The condition is checked before each iteration.
  
* **Update:** The update statement is typically inside the loop body and must be handled explicitly.
  
* **Use Case:** Ideal when the number of iterations is not known beforehand and depends on a condition.
  

### Key Differences
  
* **Scope of Initialization and Update:** In a for loop, the initialization and update are part of the loop structure, while in a while loop, they are handled separately.
  
* **Flexibility:** While loops offer more flexibility as they can handle more complex conditions and update statements.
  

## Recommended Content:
  
1. [For Loops In Python- Python Tutorials For Beginners #9](https://giteshwagh.com/post/for-loops-in-python-tutorial-9/)  
2. [Project 2: Calculator - Python Tutorials For Beginners #8](https://giteshwagh.com/post/project-2-calculator-in-python-tutorial-8/)  
3. [Match Cases - Python Tutorials For Beginners #7](https://giteshwagh.com/post/match-cases-in-python-tutorial-7/)  
  

## Watch Video Tutorial
   
{{< youtube 09TdpUBfb9Y >}}
