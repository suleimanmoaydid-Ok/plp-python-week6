Week 6 Assignment: Safe Functions
Files
safe_tools.py — Contains three functions that handle division by zero, invalid integer conversion, and missing dictionary keys.
safe_tools_output.png — Screenshot showing the program's execution and output.
README.md — Documents the assignment and explains why exception handling is necessary.

Why can't an if check catch "abc" on its own?

An if statement can check conditions, but it cannot automatically prevent int("abc") from raising a ValueError. Using try/except allows Python to handle the conversion error gracefully and lets the program continue running.
