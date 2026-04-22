# Sum of a List

Write a program called `sum_list.py` that computes the sum of a sequence of positive numbers entered by the user.

## Requirements:

1. Use a `while` loop to prompt the user to enter positive numbers one by one. Continue accepting inputs until the user enters a non-positive number (zero or negative).
2. Store all the entered positive numbers in a list.
3. Compute the sum of the numbers in the list using a `for` loop. Do not use Python's built-in `sum()` function.
4. Print the list and its sum.

Why would you use a `while` loop in step 1 and a `for` loop in step 3?

### Example Usage 1:

    Enter a positive number: 4
    Enter a positive number: 7
    Enter a positive number: 2
    Enter a positive number: -1
    The sum of [4.0, 7.0, 2.0] is 13.0.

### Example Usage 2:

    Enter a positive number: 1.5
    Enter a positive number: 2.5
    Enter a positive number: 0
    The sum of [1.5, 2.5] is 4.0.

## Run

Run your program and verify that it indeed displays the expected text:

    python sum_list.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy sum_list
