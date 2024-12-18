# Odd

Write a program called `odd.py` that prompts the user to input positive integers, collects them in a list, and then filters out all the odd numbers from the list.

## Requirements:

1. Prompt the user to enter positive integers. Continue accepting inputs until the user enters a non-positive number (zero or negative).
2. Store all the entered positive integers in a list.
3. Create a new list containing only the odd numbers from the original list.
4. Display both the original list and the list of odd numbers.

### Example Usage:

    Enter a positive number: 8
    Enter a positive number: 15
    Enter a positive number: 23
    Enter a positive number: 42
    Enter a positive number: -1
    The list [8, 15, 23, 42] contains these odd numbers [15, 23].


## Run

Run your program and verify that it indeed displays the expected text:

    python odd.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy odd
