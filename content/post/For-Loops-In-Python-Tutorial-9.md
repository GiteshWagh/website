+++
authors= "Gitesh Wagh"
title = " For Loops In Python- Python Tutorials For Beginners #9"
date = "2023-10-02"
categories = "Python"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial"
]
thumbnail = "/images/PythonTutorial9.png"
+++
------------------
# Loops In Python
**Loops are used to execute a specific code many times instead of writing code again and again.**

### Types of Loops:  

**1. For Loops**  
**2. While Loops**

--------------------

# For loop
**For Loop** is more used than **While Loops.** For Loops are used for **different purposes** in **different ways.**  

----------------------

In this example, I used **For Loops** along with the **if-else statement**. Here, **i** is **List** and **k** is a **variable** containing elements of list. **k** is used to access elements in the List. I assign conditions also with elements of the List.


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
********************************

# range()

This code is used to print the numbers as per given limit. Here, I gave a **limit** of 0 to 20 with the help of range function. **Note that, The output will start from 1 and ends on 19.** Here, the variable **i** contains numbers **1 to 19.**

````python
for i in range(0,20):
    print(i)
````
```
# Output:

0
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19

```
***********************

In this example, the variable **x** contains **letters** of the string **"Apple"**.

````python
for x in "Apple":
    print(x)
````
```
# Output:

A
p
p
l
e

```
*******************
# pass
Pass the keyword used to **hold a place** for future code. Pass keyword use when we add code in **Loops, Functions, etc...** later, But we do not want errors. 

````python
for x in "ABCD":
    pass
````
***************************

# Watch Video Tutorial On Youtube:
{{< youtube nuOv1dM6URI >}}

*******************************