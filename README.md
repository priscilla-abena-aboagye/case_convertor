# Case Convertor

This project converts PascalCase or camelCase text to snake_case text.

## Features

- **Purpose** : Converts a PascalCase string to a snake_case string

- **Methods**:
   - **main.py**: Uses a **for loop** to iterates through each character and apply the conversion logic.
   - **duplicate.py**: Uses **list comprehension** to achieve the same results in a more compact and readable form

## Overview

### Main.py
- **Description**:
   This file converts a PascalCase or camelCase string to snake_case by iterating through each character in the string.

   - **How it works**:
    - The loop checks if a character is uppercase. If so :
      - It adds an underscore ('_') before converting the character to lowercase
    - If the character is already lowercase, it remains unchanged.

### Duplicate.py
- **Decsription**
    - This file uses list comprehension to perform the same conversion. It's more compact and often preferred for simple transformations like this. The list comprehension goes through each character in the string, checks if it's uppercase, and applies the conversion logic.
