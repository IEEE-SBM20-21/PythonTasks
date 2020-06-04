# Week 3 | OOP Concepts

## Introduction

This task introduces Object Oriented Programming methodology with implementation in python. For those who are new to OOP concepts, this is an important task. 

**Object-Oriented Programming (OOP)** is the term used to describe a programming approach based on **objects** and **classes**. The object-oriented paradigm allows us to organise software as a collection of objects that consist of both data and behaviour. This is in contrast to conventional functional programming practice that only loosely connects data and behaviour.

## Resources

- To get an overview: [link](https://python.swaroopch.com/oop.html)
- In detail with theory content: [link](https://realpython.com/python3-object-oriented-programming/)
- For an easier read: [link](https://www.programiz.com/python-programming/object-oriented-programming)
  - Please go through the entire Python Object and Class Section

## Tasks

- Create a class Rectangle with length and breadth as two instance attributes. Initialize their values in the __init__ method. Also, create two instance methods: area() and perimeter() which calculate and return the two respective values. Make another method which checks whether the rectangle is a square or not (by returning a boolean value)
- Create a parent class College and two child classes Engineering and Medical. 
  - College has one instance attr location (String). Initialize it using __init__ method. 
  - Create one instance method ‘getLocation()’ which stored it.
  - The two children inherit from College. First, add a call to the super’s __init__ first in the __init__ of the two children.
  - The children have one additional attribute ‘isPrivate’ (boolean) which is also initialized using its __init__ method.
  - They also have an instance method ‘getType()’ which returns a string ‘Private’ or ‘Public’. (Use ternary operator to check and return all in one line)
  - Engineering subclass should have a class variable (stream = ‘Engineering’) and Medical should have a class variable (stream=’Medical’)

Note: Every function should have a suitable docstring defining it. 