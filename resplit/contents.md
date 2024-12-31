# Resplit

Write a program called `resplit.py` that defines a function `resplit(text)` which splits the input `text` on both periods (`.`) and commas (`,`). The output should be a list containing all split parts. All parts need to be stripped of whitespacing and empty strings should not be included in the output.

> Note that that the `.split()` method can only split on a single delimiter. So You will need to either need to use split multiple times (in a loop?) or write your own split-like function.

> Getting the details right in this assignment might be trickier than it seems. It is the explicit intention that you get help from others (students and teaching staff) for this assignment.

### Example Usage

    alice = "If I had a world of my own, everything would be nonsense. Nothing " +\
        "would be what it is because everything would be what it isn’t. And " +\
        "contrariwise, what it is, it wouldn’t be, and what it wouldn’t be, it would."

    parts = resplit(alice)

    print(parts)

### Expected Output

    ['If I had a world of my own',
     'everything would be nonsense',
     'Nothing would be what it is because everything would be what it isn’t',
     'And contrariwise',
     'what it is',
     'it wouldn’t be',
     'and what it wouldn’t be',
     'it would']

## Run

Run your program and verify that it indeed displays the expected text:

    python resplit.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy resplit
