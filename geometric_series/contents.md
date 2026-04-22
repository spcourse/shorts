# Geometric Series

Write a program called `geometric_series.py` that computes the following sum:

$$
\textrm{total} = \Sigma_{i=0}^n \frac{1}{2^i}
$$

The program should prompt the user for a non-negative integer `n` and print the result.

### Example Usage

    Enter n: 0

    The sum is 1.0

---

    Enter n: 4

    The sum is 1.9375

---

    Enter n: 10

    The sum is 1.9990234375

Notice that as `n` grows, the sum gets closer and closer to 2.

## Run

Run your program and verify that it indeed works as expected:

    python geometric_series.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy geometric_series
