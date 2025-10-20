import math

class Calculator:
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

    def multiply(self, a, b):
        return a * b

    def divide(self, a, b):
        return a / b

    def square_root(self, x):
        return math.sqrt(x)

if __name__ == "__main__":
    calculator = Calculator()
    num1 = 16
    num2 = 4

    print(f"{num1} + {num2} = {calculator.add(num1, num2)}")
    print(f"{num1} - {num2} = {calculator.subtract(num1, num2)}")
    print(f"{num1} * {num2} = {calculator.multiply(num1, num2)}")
    print(f"{num1} / {num2} = {calculator.divide(num1, num2)}")

    num3 = 25
    print(f"The square root of {num3} = {calculator.square_root(num3)}")
    print ("testing")

# CalculatorPlus App

This is a simple calculator application with basic arithmetic operations.

## Assignment Steps

### Repository Setup
- Created a private GitHub repository named 'git_assignment_HeroVired'
- Created initial code structure

### Branch Management
- Created 'dev' branch with initial calculator code
- Created 'feature/sqrt' branch for square root implementation
- Fixed critical bug in divide function

### Releases
- Created version 1 release with basic calculator functionality
- Created version 2 release with square root feature and bug fixes

### Collaboration
- Added classmate as collaborator
- Requested code review from team member

## Features
- Addition
- Subtraction
- Multiplication
- Division (with zero division check)
- Square Root calculation

## How to Use
```python
calculator = Calculator()
result = calculator.add(5, 3)  # Returns 8
sqrt_result = calculator.square_root(16)  # Returns 4.0