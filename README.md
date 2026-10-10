# PLP Python Week 6

- safe_tools.py: contains the three safe helper functions for division, integer conversion, and dictionary lookup with error handling.
- README.md: explains the assignment and answers the question about why a simple if check cannot catch invalid input like abc on its own.

An if check alone cannot catch abc because the problem happens when calling int("abc"), which raises a ValueError instead of returning a normal result. The program needs a try/except block to handle that exception cleanly rather than relying on a condition that does not cover every invalid input scenario.
