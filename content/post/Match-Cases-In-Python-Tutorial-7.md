+++
authors = "Gitesh Wagh"
title = "Match Cases - Python Tutorials For Beginners #7"
date = "2023-07-06"
categories = "Python"
thumbnail = "/images/PythonTutorial7.png"
toc = "true"
tags = [
    "Python",
    "PythonTutorial",
    "Match Cases In Python",
    "Match Cases"
]

description = "Match Cases is a method or way for writing conditions in Python programming. In Python, Match case and switch case are not the same. They are to each other similar."
+++

## Introduction
Python is a popular programming language that offers many features and benefits for developers. One of these features is the ability to use **match cases,** which are a **new way of writing conditional statements** in **Python 3.10** and above.

In this blog post, we will learn how to use match cases in Python, and see some examples of how they can simplify and improve your code.

<img title="Conditions In Python" alt="Markdown Synatx Conditions In Python" src="/images/PYTHON CONDITION.png">


## What Are Match Cases In Python?  
**Match Cases** is a method or way for writing conditions in Python programming. Here, We create conditions related to the **value of a variable.** In **If-Else statements,** We define the condition with the help of **conditional operators.** But, In Match Cases the value of the variable is a condition. In Match Cases we program that, What will happen when the value of a variable is 1, 2, 3, etc... This is only for example. You will create a condition on any value of variable.
  
## Is match case the same as switch case?  

In Python, **Match case and switch case are not the same.** They are **similar** in that they both allow you to **compare a value** against different cases and execute different blocks of code depending on the match. However, **match case is more powerful and expressive than switch case,** because it can do the following things that switch case cannot:

* Match on types, attributes, and patterns, not just literals and constants.
* Use ranges, bindings, guards, and wildcards to make the cases more flexible and concise.
* Be used as an expression that returns a value, not just a statement that performs an action.
* Ensure that the cases are exhaustive and cover all possible values, or raise an exception otherwise.

In other languages, Match cases are similar to **switch cases**. but they are **more powerful and expressive.** They allow you to match a value or an expression against different patterns, and execute different blocks of code depending on the match. 


```

    Methods For Creating Conditions
                |
                |
      |---------------------|
      |                     |
      |                     |
      |                     |
If-Else Statements      Match Cases
                    
```

  
## Syntax Of Match Cases

```python
x = input("Enter the number : ")
# variable x with the input system

match x:
    # Condition 1
    case 'Value1':
        print("The value is 1")

    # Condition 2
    case 'Value2':
        print("The value is 2")

    # Condition 3
    case 'Value3':
        print("The value is 3")

    # Condition 4
    case 'Value4':
        print("The value is 4")

    # Else Condition
    case _:
        print("other value")
```
  

## Examples of Match Cases
**This a simple example of match cases.**

```python
x = input("Enter the number : ")
# variable x with the input system

match x:
    # Condition 1
    case '1':
        print("The value is 1")

    # Condition 2
    case '2':
        print("The value is 2")

    # Condition 3
    case '3':
        print("The value is 3")

    # Condition 4
    case '4':
        print("The value is 4")

    # Else Condition
    case _:
        print("other value")
```

## Recommended Content 
1. [If-Else statements - Python Tutorials For Beginners #6](https://giteshwagh.com/post/if-else-statements-in-python-tutorial-6/)  

2. [Variables And DataTypes - Python Tutorials For Beginners #3](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)     

3. [Installation and Setup of Python and VS Codium - Python Tutorials For Beginners #1](https://giteshwagh.com/post/setup-of-python-tutorial-1/)     



## Watch Video Tutorial On Youtube
{{< youtube A-WbED_fMtY >}}

