# Average and Variance as Functions

You have already written the algorithms for computing the average and the variance of a list. Now you will put both algorithms into functions.

Create a file called `average_variance_fn.py`. Start by copying the computing parts of your `average.py` and `variance.py` (not the `while` loops that collect input, just the `for` loops that do the maths).

Note that: for this assignment you're not going to ask the user for input. To test your functions you can just use some hard-coded test inputs.

## Part 1: average

Define a function `average(lst)` that takes a list of numbers and returns the mean.

### Example Usage

    print(average([1.0, 2.0, 3.0]))
    print(average([10.0, 20.0, 30.0, 40.0]))
    print(average([7.0]))

### Expected Output

    2.0
    25.0
    7.0

## Part 2: variance

Define a function `variance(lst)` that takes a list of numbers and returns the variance (using the `for` loop you copied from the previous variance assignment).

Call `average(lst)` inside `variance` to compute $$\mu$$. Do not repeat the averaging loop — that is exactly what the function is for.

### Example Usage

    print(variance([2.0, 4.0, 4.0, 6.0]))
    print(variance([1.0, 3.0]))
    print(variance([5.0, 5.0, 5.0]))

### Expected Output

    2.0
    1.0
    0.0

## Run

Run your program and verify that it indeed displays the expected text:

    python average_variance_fn.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy average_variance_fn
