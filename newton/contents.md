# Newton's Method

Write a program called `newton.py` that calculates the square root of a given number using Newton's Method. The program should prompt the user to input a positive floating-point number (`n`). It should then use an iterative algorithm to approximate the square root of the number.

Newton's Method works as follows:

1. Start with an initial guess for the square root (in this case, the number itself): $$current\_guess = n$$
2. Iteratively update the guess using the formula:
   $$
   \text{new\_guess} = 0.5 \times (\text{current\_guess} + \frac{n}{\text{current\_guess}})
   $$
3. Repeat the update for a fixed number of iterations (in our case we will do 50 iterations).

### Constraints

- You're not allowed to use any other way to compute the square root (e.g., not `n ** 0.5` nor `math.sqrt(n)`).

### Example Usage

    Enter a number: 25
    The square root of 25.0 is 5.0

## Run

Run your program and verify that it indeed displays the expected text:

    python newton.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy newton
