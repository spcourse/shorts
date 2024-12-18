# Squares

Write a program called `squares.py` that prompts the user to input positive numbers, stores them in a list, and calculates the square of each number in the list.

## Requirements:

1. Prompt the user to enter positive numbers. Continue accepting inputs until the user enters a non-positive number (zero or negative).
2. Store all the entered positive numbers in a list.
3. Create a new list containing the squares of the numbers from the original list.
4. Print both lists.

### Example Usage 1:

    Enter a positive number: 2
    Enter a positive number: 3
    Enter a positive number: 4
    Enter a positive number: -1
    The squares of [2.0, 3.0, 4.0] are [4.0, 9.0, 16.0].

### Example Usage 2:


    Enter a positive number: 1.5
    Enter a positive number: 2.5
    Enter a positive number: 0
    The squares of [1.5, 2.5] are [2.25, 6.25].


## Run

Run your program and verify that it indeed displays the expected text:

    python squares.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy squares
