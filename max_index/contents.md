# Max Index

Write a program called `max_index.py` that defines a function `max_index(lst)` which takes a list of numbers as input and returns the **index of** the maximum value in the list. If the list is empty, the function should return `None`.

### Example Usage

    # Example lists
    l = [1, 6, 19, 2, -8]
    m = max_index(l)
    print(f"The index of the maximum value of {l} is {m}.")

### Expected Output

    The index of the maximum value of [1, 6, 19, 2, -8] is 2.

## Run

Run your program and verify that it indeed displays the expected text:

    python max_index.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy max_index
