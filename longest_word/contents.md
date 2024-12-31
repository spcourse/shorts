# Longest Word

Write a program called `longest_word.py` that defines a function `longest_word(text)` which identifies and returns the longest word from a given string `text`. (If there are multiple words of the same maximum length, the function should return the first one encountered.) You don't have to worry about punctuation: periods, comma's, etc. are considered part of the word they're attached to.

### Example Usage

    # Example string
    alice = "Sometimes I have believed as many as six impossible things before breakfast."
    longest = longest_word(alice)
    print(longest)

### Expected Output

    impossible

## Run

Run your program and verify that it indeed displays the expected text:

    python longest_word.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy longest_word
