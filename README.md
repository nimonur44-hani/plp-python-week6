
# PLP Python Week 6 Assignment: Safe Tools

## Files

- safe_tools.py: Contains three functions that handle errors safely using try and except.
- README.md: Contains the assignment description and explanation.

## Question: Why can the if check not catch abc on its own?

An if statement can check conditions, but it cannot automatically catch errors that happen during type conversion. When int() tries to convert "abc" into a whole number, Python raises a ValueError. We use try and except to handle this error without crashing the program.
