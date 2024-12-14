### Buzz

Write a program called `buzz.py` that prints a range of integers but prints `"buzz"` for any number in the range that is a multiple of 5. For all other numbers, the program should simply print the number itself.

The program should prompt the user to input two integers: the starting number (`a`) and the ending number (`b`). It should then iterate through all numbers from `a` to `b` (including `a` but _excluding_ `b`), performing the described check for each number.

### Example Usage

If the user inputs `10` as the first number and `16` as the second number, the program should check each number in the range from 10 to 15 and determine if it is a multiple of 5.

    Enter first number: 10
    Enter second number: 17

### Expected Output

    buzz
    11
    12
    13
    14
    buzz
    16

## Run

Run your program and verify that it indeed displays the expected text:

    python buzz.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy buzz
