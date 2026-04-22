# Variance

Write a program called `variance.py` that calculates the variance of a sequence of positive numbers entered by the user.

The variance measures how spread out the numbers in a list are. It is defined as the average of the squared differences from the mean. For a list $$a$$ of $$n$$ numbers with mean $$\mu$$:

$$
\textrm{variance} = \frac{1}{n} \Sigma_{i=0}^{n-1} (a_i - \mu)^2
$$

where $$\mu$$ is the mean of the list:

$$
\mu = \frac{1}{n} \Sigma_{i=0}^{n-1} a_i
$$

Notice that computing the variance requires **two passes** over the list: first compute the mean, then use it to compute the sum of squared differences.

## Requirements:

1. Prompt the user to enter positive numbers one by one. Continue accepting inputs until the user enters a non-positive number (zero or negative).
2. Store all the entered positive numbers in a list.
3. Compute the mean using a `for` loop.
4. Compute the variance using a second `for` loop. Do not use Python's built-in `sum()` function.
5. Print the list and its variance.

### Example Usage 1:

    Enter a positive number: 2
    Enter a positive number: 4
    Enter a positive number: 4
    Enter a positive number: 6
    Enter a positive number: -1
    The variance of [2.0, 4.0, 4.0, 6.0] is 2.0.

### Example Usage 2:

    Enter a positive number: 1
    Enter a positive number: 3
    Enter a positive number: 0
    The variance of [1.0, 3.0] is 1.0.

## Run

Run your program and verify that it indeed displays the expected text:

    python variance.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy variance