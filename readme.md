# **PACKAGES AND MODULES** <img align="center" width="120" height="75" src="![python-logo](https://user-images.githubusercontent.com/77577111/182298776-dbd4edeb-da5b-4d2c-a509-7bb05e0400bd.png)"> 
![python-logo](https://user-images.githubusercontent.com/77577111/182298776-dbd4edeb-da5b-4d2c-a509-7bb05e0400bd.png width='480') 

> I am curating a list of vastly used packages and modules along with its implementation in python.

## PACKAGES

* Packages are a way of structuring python module's namespace by using "dotted module names".

* Essentially, a Package is a directory having collection of various modules.This directory contains python modules having **\_init_.py** file by which interpreter interprets it as a Package. 

> Thus, a module named `A.B` designates a module named `B` in a package `A`.

* Some of the versatile packages are NumPy, Pandas, Matplotlib, Sklearn.

Importing a built-in package in python:

```
import matplotlib.pyplot as plt
```
Here, `pyplot` is a module in a package `matplotlib`.

## MODULES

* A module is simply a python file containing various functions , global variables and classes that are accessible by the coder as well as users.

* With the help of functions inside a module, the maintainability of the code becomes easier in a long run. 

* The functions in a module can be accessed just by importing that module name(without .py) with dot(.) in different python script.

Creating a module `factorial.py` containing a function that calculates factorial:

```
def fact(n):    
    if n==0 or n==1:
        return 1
    else:
        return (n*fact(n-1))
 ```

If we want to use this function in another python file, one simply needs to import the module factorial, like shown below:

```
import factorial
```
In order to calculate for a particular 'n', say n=5, you may write,

```
factorial.fact(5)
```
The above piece of code gives an output `120`.


# *List of libraries:*

# References
Geeksforgeeks (https://www.geeksforgeeks.org/python-modules/?ref=lbp)
Python.org documentation

