# Case Convertor
This project was done to convert pascal cased text or camel cased text to snake cased text

## Features - PascalCase to SnakeCase Conversion

- **Purpose** : Converts a PascalCase string to a snake_case string

- **Methods**:
   - **main.py**: Uses **for loop** ti iterates through each character and apply the conversion logic.

   - **duplicate.py**: Uses **list comprehension** to achieve the same results in a more compact and readable form

## Overview

- Main.py
    - This file converts a PascalCase string to snake_case by iterating through each letter in the string. The loop checks if a letter is uppercase and, if so, adds an underscore **(_)** before converting it to lowercase. If the letter is already lowercase, it remains unchanged.

- Duplicate.py
    - This file uses list comprehension to perform the same conversion. It's more compact and often preferred for simple transformations like this. The list comprehension goes through each character in the string, checks if it's uppercase, and applies the conversion logic.
