# Weighted Average

A weighted average is like a regular average, except that some values count more than others. Each value $a_i$ is multiplied by a corresponding weight $w_i$ before summing. The result is then divided by the total weight:

$$
\textrm{weighted\_average} = \frac{\Sigma_{i=0}^{n-1} w_i \cdot a_i}{\Sigma_{i=0}^{n-1} w_i}
$$

When all weights are equal, this is the same as the regular average.

## Assignment

Create a file called `weighted_average.py` and define a function `weighted_average(values, weights)` that takes two lists of equal length and returns the weighted average.

> Tip: since the formula uses both lists at the same index $i$, you cannot use the standard python loop `for a in values`. You will need to explicitely loop using the indices:
>
>        for range(len(values)):
>            a = values[i]
>            w = weights[i]
>            ...

### Example Usage

    print(weighted_average([1.0, 2.0, 3.0], [1.0, 1.0, 1.0]))
    print(weighted_average([4.0, 8.0], [1.0, 3.0]))
    print(weighted_average([0.0, 10.0], [3.0, 1.0]))

### Expected Output

    2.0
    7.0
    2.5

Note that the first test case uses equal weights (verify for yourself that the result is the same as a regular `average`).

## Run

Run your program and verify that it indeed displays the expected text:

    python weighted_average.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy weighted_average
