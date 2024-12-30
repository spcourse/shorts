# Vowel Words

Write a program called `vowel_words.py` that defines a function `vowel_words(text)` which extracts and returns all words from the input string `text` that start with a vowel (a, e, i, o, u).

### Example Usage

    # Define the function
    def vowel_words(text):
        new = ""
        for w in text.split():
            if w[0].lower() in "aeiou":
                new += w + " "
        return new

    # Example string
    alice = "Sometimes I have believed as many as six impossible things before breakfast."
    only_words_that_start_with_vowels = vowel_words(alice)
    print(only_words_that_start_with_vowels)

### Expected Output

    I as as impossible

## Run

Run your program and verify that it indeed displays the expected text:

    python vowel_words.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy vowel_words
