# Arange

Write a program called `arange.py` that defines a function `arange(a, b, step_size)` which generates a list of numbers starting from `a`, incrementing by `step_size`, and stopping before reaching `b`.

### Example Usage

    # Test case 1
    l1 = arange(0, 10, 1)
    print(l1)

    # Test case 2
    start = -1
    stop = 1
    step = 0.25
    l2 = arange(start, stop, step)
    print(l2)

### Expected Output

    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    [-1, -0.75, -0.5, -0.25, 0.0, 0.25, 0.5, 0.75]

## Run

Run your program and verify that it indeed displays the expected text:

    python arange.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy arange
