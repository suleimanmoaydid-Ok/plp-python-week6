Week 6 Assignment: Safe Functions
Files
safe_tools.py — Contains three functions that handle division errors, invalid number input, and missing dictionary keys.
README.md — Describes the assignment files and explains why error handling is needed.
Why can't an if check catch "abc" on its own?
An if check can test conditions, but it does not automatically prevent int("abc") from raising a ValueError. Using try/except allows the program to handle the conversion error and continue running.
