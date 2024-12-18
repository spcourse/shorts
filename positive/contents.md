# Positive

Write a program called `positive.py` that prompts the user to enter a positive integer and keeps asking until a valid positive number is provided.

## Requirements:

1. Prompt the user to enter a positive integer.
2. If the user enters a number less than 1, prompt them to "Try again" until they enter a valid positive number.

### Example Usage 1:

    Enter a positive number: -5
    Try again: -3
    Try again: -2
    Try again: 10
    Great, 10 is a positive number!

### Example Usage 2:

    Enter a positive number: 2
    Great, 2 is a positive number!


## Run

Run your program and verify that it indeed displays the expected text:

    python positive.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy positive
