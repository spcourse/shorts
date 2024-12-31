# Longest Word in File

Write a program called `longest_word_in_file.py` that (just like the `longest_word` assignment before) defines a function `longest_word(text)` which identifies and returns the longest word from a given string `text`. In this case however, the input text should be read from a text file called `alice.txt` ([download](alice.txt)).

### Notes

- Contrary to earlier to the assignment you do need to strip all punctuation (`,;:!?()-`) and whitespacing (`\t\n `) from the words.
- Ensure the file `alice.txt` exists in the same directory as your program.
- You might want to use the `file.read()` method to read the whole file as a single string.

### Example Usage

    # define longest_word function.
    # your code here...

    # Open and read file store contents in txt variable
    # your code here...

    # Find and print the longest word
    longest_word = longest_word(txt)
    print(longest_word)

### Expected Output

    waistcoat-pocket

## Run

Run your program and verify that it indeed displays the expected text:

    python longest_word.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy longest_word
