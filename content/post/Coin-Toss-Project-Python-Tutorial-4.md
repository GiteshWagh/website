+++
authors= "Gitesh Wagh"
title= "Project 1: Coin Toss - Python Tutorials For Beginners #4"
date="2023-06-04"
categories = "Python" 
Tags = [
     "Visual Studio",
     "python",
     "Python Prgramming",
     "Python Project"
] 
thumbnail = "/images/CoinTossProject.png"
+++

**Let’s Create Something Amazing With Python!**

In this blog, we’ll be learning how to create a Python program to make a simple 
coin toss project. This project is perfect for beginners. Today, We all learn 
about the **practical application of concepts in Python**.  
This program will allow the computer to randomly choose one of two outcomes and 
display it.     

### Concepts Used In This Project
**(1) Variables**  
**(2) Datatypes**  
**(3) Random Module**  
**(4) Print Function**  

*****

We import the Random module to use its function. The module is a pre-defined code in programming. Here, We use **random.choice()** function to choose one element in the list. 

```python
# Project 1: Coin Toss In Python
import random                     
```

Now, I create a list called **List**, Which contains **Heads** and **Tails**. 

```python
List = ["Heads", "Talis"]
```

Here, I use the print function to **display randomly chosen value from the list** by Python.

```python
print(random.choice(List)) 
```

******

### Whole Code
```python
# Project 1: Coin Toss In Python
import random                     
List = ["Heads", "Talis"]  
print(random.choice(List))        
```

*******
# Watch Video Tutorial On Youtube
{{< youtube AhYxvgrPvJY >}}

*****