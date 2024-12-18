# Elmo

Write a program called `elmo.py` that repeatedly prompts the user to enter a name until they guess the correct name, "Elmo".

## Requirements:

1. Prompt the user to enter a name.
2. If the user does not enter "Elmo," prompt them to try again.
3. Continue prompting the user until they enter "Elmo."
4. Once the correct name is entered, display the message:  
   `Elmo is so happy to see you!`

### Example Usage:

If the user initially guesses incorrectly:

    Enter a name: Cookie
    Try again: Big Bird
    Try again: Elmo
    Elmo is so happy to see you!

## Run

Run your program and verify that it indeed displays the expected text:

    python elmo.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy elmo
