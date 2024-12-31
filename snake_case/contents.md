# Snake_case

In programming, variable naming conventions are essential for writing readable and maintainable code. Two common styles are **camelCase** and **snake_case**:

- **camelCase**: Words are joined together with the first word lowercase and subsequent words starting with uppercase letters (e.g., `myVariableName`).
- **snake_case**: Words are separated by underscores, and all letters are lowercase (e.g., `my_variable_name`).

CamelCase is popular in some programming languages like Java and JavaScript. Snake_case is the standard naming style in Python (arguably because it's more readable).

For this assignment, you'll create a program called `snake_case.py` to help convert variable names from camelCase to snake_case. Define a function `snake_case(text)` which converts a string in camelCase format to snake_case format. You may assume that the input is in camelCase format and doesn't contain any spaces or underscores.

### Example Usage

    java_variable_name = "textProcessingVariable"
    python_variable_name = snake_case(java_variable_name)
    print(python_variable_name)

### Expected Output

    text_processing_variable

## Run

Run your program and verify that it indeed displays the expected text:

    python snake_case.py

## Checkpy

You can use checkpy to verify that it meets our requirements:

    checkpy snake_case
