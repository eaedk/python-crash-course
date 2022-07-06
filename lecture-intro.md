# Programming using Python 3

# Introduction
## Description of Python 3
Python 3 is a, high-level, dynamically typed, interpreted, object-oriented, general-purpose, programming language.

Python is a very high-level programming language because its syntax so closely resembles the English language. Higher-level means it's more readable to humans,so that, it's an easy language to learn.

Python is a dynamically typed language. This means that the Python interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.
Python is also a general-purpose language because it can be used for almost all the purposes, like web development, artificial intelligence, physics, mathematics, cyber security, etc.

Python is an interpreted language, which means the source code of a Python program is converted into bytecode that is then executed by the Python virtual machine. Python is different from major compiled languages, such as C and C++, as Python code is not required to be built and linked like code for these languages.

Python's object-oriented programming system supports all four features: encapsulation, abstraction, inheritance and polymorphism.

We will explore the language deeply a bit later. 

## What is programming ?
Programming means using code, written in a programming language, based on an algorithm, to make a computer perform desired actions or to solve some problems.

## What is an algorithm ?
In mathematics and computer science, an algorithm is a finite sequence of rigorous instructions, typically used to solve a class of specific problems or to perform a computation.

An algorithm has some main components that are implemented differently with each programming language.
![](https://slideplayer.com/slide/13700544/85/images/4/Components+of+an+Algorithm.jpg)

# Purpose 

This Python crash course aims to introduce learners in programming and help them to develop softwares that perform actions, calculations, processings to solve problems.

# Python code overall structure & I/O
There are many ways to write Python 3 code. Let's have a look to the Script method. 

```python
import os # We import the package named os

# def cal_add():
#     """This is a simple function that asks the user to type two numbers to add them up """
#     pass


def main():
    """The main function that will run instructions when the script file will be executed"""

    print("Hello world!")
    print("The working directory is", os.getcwd())
    message = input("Type a message for the world\n>>>")
    print("This is your message:", message)


if __name__ == "__main__":
    main()  # call of the main function

```

In the main function we write our instructions and at the bottom we check wheather the system want to execute the file, if so the main function is started and the instructions are execute from the top to the bottom.