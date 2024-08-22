+++
authors= "Gitesh Wagh"
title = "For Loops In Python- Python Tutorials For Beginners #9"
date = "2023-10-02"
categories = "Python"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
thumbnail = "/images/PythonTutorial9.png"
feautureimage="/images/PythonTutorial9.png"
toc=true
featureImageAlt = "For Loops In Python- Python Tutorials For Beginners #9"
+++

## Understanding For Loops In Python

A for loop is a powerful construct that allows you to repeat a block of code for each element in a sequence **(like a list, tuple, or string)**. Here’s the basic structure:

````python
for element in sequence:
    # Code to execute for each element
````
  
    
## How To Create For Loops
* Step 1: For loops are always starts with **for** keyword.
* Step 2: Create a variable as per your need.
* Step 3: Iterate element as per you want.

Now, let’s break it down step by step:

### 1. Iterating Over a List  
    
Suppose we have a list of programming languages: **languages = ['Swift', 'Python', 'Go']**. We can use a **for loop** to access each language one by one:
  
````python
for language in languages:
    print(language)

````  
  
**Output:**  
```
Swift
Python
Go
```
  
### 2. Iterating Over a String:   
  
You can also loop through each character in a string: 
````python
language = 'Python'
for char in language:
    print(char)
````

**Output:**  
```
P
y
t
h
o
n
```

### 3. Using range() With For Loop:  
  
The **range()** function generates a sequence of numbers. You can iterate over it using a for loop.This code is used to print the numbers as per given limit. Here, The **limit** is 0 to 4. **Note that, The output will start from  0 and ends on 4.** Here, the variable **i** contains numbers **0, 1, 2, and 3.**
  
````python
# Iterate from 0 to 3
for i in range(4):
    print(i)

````
  
**Output:**    
  
```
0
1
2
3

```

### 4. Else Clause With For Loop:     
  
You can add an optional else block that executes after the loop completes:
  
````python
digits = [0, 1, 5]
for digit in digits:
    print(digit)
else:
    print("No items left.")
````
  
### 5. For Loops Along Conditions  
  
In this example, I used **For Loops** along with the **If-Else statement**. Here, **i** is **List** and **k** is a **variable** containing elements of list. **k** is used to access elements in the List. I assign conditions also with elements of the List.


````python
i = ['fish','cat','dog']

for k in i:
    print(k)
    if (k=="dog"):
        print("dogs are so loyal animals")

    elif (k == 'cat'):
        print("cats are so cute.")

    elif (k=='fish'):
        print("fish is live in the water")
    else:
        print(k,"is are nice animal")

        for i in k:
            print(i)
````
```Output
# Output:

fish
fish is live in the water
cat
cats are so cute.
dog
dogs are so loyal animals

```
  
### 6. For Loop Along Pass Keyword  
  
In this given example **pass** keyword works as a placeholder. Pass keyword use when we add code in **Loops, Functions, etc...** later, But we do not want errors now. 

````python
for x in "ABCD":
    pass
````
  
### 7. For Loops With Break Statement  
  
In Python, the break statement is used to exit a loop prematurely. When encountered, it terminates the loop immediately. Here’s how it works:  
  
````python
for i in range(5):
    if i == 3:
        break
    print(i)
````  

**Output:**  

```
0
1
2
```

<img title="For Loops With Break Statement" alt="For Loops With Break Statement" src="/images/ForLoopsInPython.png">


### 8. Iterating Over a Tuple  
````python
Colours=("Red","Green","Blue")
for i in Colours:
    print(i)

````
**Output:**
```
Red
Green
Blue
```
  
### 9. Iterating Over a List
````python
Colours=["Red","Green","Blue"]
for i in Colours:
    print(i)
  
````
**Output:**
```
Red
Green
Blue
```
  
### 10. Iterating Over a Dictionary  
````python
Colours={ 
    "1":"Red"
        "2":"Green"
        "3":"Blue" 
}

for i in Colours:
    print(i)

````
  
**Output:**
  
```
Red
Green
Blue
```


## Watch Video Tutorial 
{{< youtube nuOv1dM6URI >}}

## Recommended Content
  
1. [Variables And DataTypes - Python Tutorials For Beginners #3](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)
2. [Operators In Python - Python Tutorials For Beginners #5](https://giteshwagh.com/post/operators-in-python-tutorial-5/)
3. [Type Casting In Python- Python Tutorials For Beginners #10](https://giteshwagh.com/post/type-casting-in-python-tutorial-10/)
  
  
