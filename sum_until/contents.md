# Sum Until

Write a program called `sum_until.py` that calculates the sum from $$1 + 2 + ...$ until this sum surpasses a given `n` provided by the user.

## Requirements:

1. Prompt the user to enter a positive integer (`n`). If the input is less than 1, keep prompting the user to "Try again" until a valid positive number is entered.
2. Starting from 1, calculate the sum of consecutive integers (i.e., $$1 + 2 + ...$$) until the sum is greater than or equal to `n`.
3. Print results.

### Example Usage:

    Enter a positive number: 9
    The sum of all numbers from 1 to 4 is 10 (which is bigger or equal to 9).

## Run

Run your program and verify that it indeed displays the expected text:

    python sum_until.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy sum_until
