# Python Calculator

## Overview
This project contains a simple calculator function in Python that performs basic arithmetic operations: addition, subtraction, multiplication, and division.

## Functionality
The `calculator` function takes in three parameters:
1. `a`: The first operand (a number).
2. `b`: The second operand (a number).
3. `operator`: A string that specifies the arithmetic operation to be performed. The possible operators are:
   - `+` for addition
   - `-` for subtraction
   - `*` for multiplication
   - `/` for division

### Example Usage:
```python
def calculator(a, b, operator):
    if operator == "+":
        print(a + b)
    elif operator == "-":
        print(a - b)
    elif operator == "*":
        print(a * b)
    else:
        print(a / b)

calculator(3, 7, "-")  # Output will be -4
