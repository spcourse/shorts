# Fun Sum

Rewrite the program `sum.py` you wrote in the previous module and call in `fun_sum.py`. Just as before, it calculate the sum of all integers in a given range. The program should prompt the user to input two integers: the starting number (`a`) and the ending number (`b`). Then, it should compute the sum of all numbers from `a` to `b` (including both `a` and `b` themselves) and display the result.

But, this time the sum should be computed using a function named `sum(a, b)` which calculates the sum of all integers between two given numbers `a` and `b` (inclusive).

### Example Usage

    Enter first number: 1
    Enter second number: 5

### Expected Output

    The sum of all numbers from 1 to 5 is 15.

## Run

Run your program and verify that it indeed displays the expected text:

    python fun_sum.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy fun_sum
