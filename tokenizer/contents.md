# Tokenizer

Before a computer can do anything with a text, it first has to cut it into pieces:
words, punctuation marks, or even parts of words. These pieces are called **tokens**,
and cutting a text into tokens is called **tokenizing**. A language model like
ChatGPT also starts here: it reads and predicts text one token at a time.

The simplest tokenizer there is just splits the text on spaces. That is all you need
to do in this assignment: **splitting on spaces is a (trivial) tokenizer**.

Write a program called `tokenizer.py` that defines a function `tokenize(text)` which
splits `text` on spaces and returns the tokens as a list.

### Example Usage

    sentence = "The cat sat on the mat."
    tokens = tokenize(sentence)
    print(tokens)

### Expected Output

    ['The', 'cat', 'sat', 'on', 'the', 'mat.']

Look at the last token: `'mat.'`. The full stop is stuck to the word, because there
is no space between them. Real tokenizers are smarter: they split off punctuation, and
they often cut long or rare words into smaller parts. But the idea is the same.

## Run

Run your program and verify that it indeed displays the expected text:

    python tokenizer.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy tokenizer
