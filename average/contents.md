# Average

Write a program called `average.py` that calculates the average of a sequence of positive numbers entered by the user.

## Requirements:

1. Prompt the user to enter positive numbers one by one. Continue accepting inputs until the user enters a non-positive number (zero or negative).
2. Store all the entered positive numbers in a list.
3. Calculate the average of the numbers in the list.

### Example Usage 1:

    Enter a positive number: 5
    Enter a positive number: 10
    Enter a positive number: 15
    Enter a positive number: -1
    The average of [5.0, 10.0, 15.0] is 10.0.

### Example Usage 2:

    Enter a positive number: 1.2
    Enter a positive number: 2.5
    Enter a positive number: 3.8
    Enter a positive number: 0
    The average of [1.2, 2.5, 3.8] is 2.5.

## Run

Run your program and verify that it indeed displays the expected text:

    python average.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy average
