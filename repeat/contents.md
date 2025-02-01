# Repeat

Write a program called `repeat.py` that asks the user for a string and a number, n. It should than display the string n times on a single line without spaces in between.

You are supposed to use a for-loop and are not allowed to use string multiplication (e.g., `"hello" * 5`) (This hasn’t been discussed yet, but if you happen to know it, don’t use it.)

You might want to go back to the [basics theory section](/python/en/basics) and check how you can print multiple times on a single line.

Your code should print a new line _after_ displaying the repeated string.

### Example Usage 1

    Text to repeat: hello
    How many times: 5
    hellohellohellohellohello

### Example Usage 2

    Text to repeat: _.-^-._
    How many times: 8
    _.-^-.__.-^-.__.-^-.__.-^-.__.-^-.__.-^-.__.-^-.__.-^-._

## Run

Run your program and verify that it indeed displays the expected text:

    python repeat.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy repeat
