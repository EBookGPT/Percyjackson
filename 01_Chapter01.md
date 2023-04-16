# Chapter 1: The Lightning Thief

Welcome aspiring demigods and devoted Percy Jackson fans! In this chapter, we delve into the exciting world of "The Lightning Thief". 

As many of you may know, "The Lightning Thief" is the first book in the "Percy Jackson and the Olympians" series by Rick Riordan. The book introduces us to Percy, a dyslexic 12-year-old boy who discovers that he's actually a demigod, the son of Poseidon. 

Percy's life is turned upside down when he's accused of stealing Zeus' lightning bolt, and he embarks on a journey to clear his name and prevent a war between the gods. Along the way, Percy encounters various mythological creatures and battles the forces of the Underworld.

In this chapter, we'll explore the exciting plot of "The Lightning Thief" and learn how to solve a coding problem using Percy's adventures as inspiration. So grab your sword and shield, and let's get started on this thrilling quest!
# Solving the Riddle of the Oracle

In "The Lightning Thief", Percy and his friends are faced with many challenges, but one of the most puzzling is the riddle of the Oracle. In order to find the location of the missing lightning bolt, they must solve the Oracle's riddle: "You shall sail the iron ship with warriors of bone, you shall find what you seek and make it your own, but despair for your life entombed within stone, a ten-year promise you shall atone."

This riddle may seem cryptic and difficult to unravel, but with a bit of coding knowledge, we can break it down and solve it too! Let's take a closer look at the different parts of the riddle and how we can represent them in code.

First, we have the line "You shall sail the iron ship with warriors of bone". We can interpret this as a clue to use a data structure called a list, where the ship is represented by the list and the warriors of bone are the elements within it. We can define our list in Python like this:

```python
ship = ["warrior1", "warrior2", "warrior3", ...]
```

Next, we have "you shall find what you seek and make it your own". This suggests that we need to search for something within the list and retrieve it. We can use the `index()` method to find the index of an item within the list. For example:

```python
index = ship.index("warrior2")
```

Now, let's move on to "but despair for your life entombed within stone". This line implies that we need to use a loop to iterate over the elements within the list and look for a specific condition. We can use a `for` loop to do this. For example:

```python
for warrior in ship:
  if warrior == "skeleton":
    print("Despair for your life!")
```

Finally, we have "a ten-year promise you shall atone". This may seem the most puzzling part of the riddle, but we can interpret it as an instruction to use a timer or delay of 10 seconds. We can use the `time` module in Python to create a delay. For example:

```python
import time

time.sleep(10)
```

By putting all these pieces of code together, we can solve the riddle of the Oracle and complete our quest in "The Lightning Thief"! Remember, just like Percy and his friends, don't give up when faced with a difficult challenge – keep investigating, experimenting, and learning from your mistakes.
Sure, I'd be happy to explain the code used to solve the riddle of the Oracle in "The Lightning Thief"!

## Using a List to Represent the Iron Ship

The first part of the riddle refers to "sailing the iron ship with warriors of bone". To represent this in code, we can use a Python list to represent the ship, with each warrior as an element of the list.

```python
ship = ["warrior1", "warrior2", "warrior3", ...]
```

In this example, we've defined a list called `ship` and populated it with some placeholders for the warriors. In reality, the warriors in the story are made of bone, but we can use any values we want for our list.

## Finding What You Seek and Making It Your Own

The second part of the riddle tells us to "find what you seek and make it your own". This implies that we need to search for something within the list and retrieve it. In Python, we can use the `index()` method to find the index of a particular value within a list.

```python
index = ship.index("warrior2")
```

In this example, we've used the `index()` method to find the index of "warrior2" within the `ship` list. This returns the value 1, since "warrior2" is the second element of the list (Python uses 0-based indexing).

## Despair for Your Life Entombed Within Stone

The third part of the riddle warns us to "despair for your life entombed within stone". This suggests that we need to use a loop to search through the entire list and look for a particular value.

```python
for warrior in ship:
    if warrior == "skeleton":
        print("Despair for your life!")
```

In this example, we've used a `for` loop to iterate over each value in the `ship` list. We've then used an `if` statement to check if the current value is equal to "skeleton". If it is, we print out the message "Despair for your life!".

## A Ten-Year Promise You Shall Atone

The final part of the riddle tells us that we must "atone" for a ten-year promise. This is a bit trickier to represent in code, but we could use the `time` module to create a 10-second delay in our program.

```python
import time

time.sleep(10)
```

In this example, we've imported the `time` module and called its `sleep()` function, which causes the program to pause for 10 seconds before continuing.

By combining these pieces of code into a single program, we can solve the riddle of the Oracle in "The Lightning Thief"!


[Next Chapter](02_Chapter02.md)