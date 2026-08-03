# Simple Calculator V1.0

## Description
A simple desktop calculator built with Python's Tkinter library. Supports basic arithmetic, parentheses, and exponents, evaluated live using Python's eval().

## Features
Digit buttons (0-9)
Basic operators: +, -, *, /
Parentheses support: ( )
Decimal point input
Exponent operator (^, mapped to Python's **)
Clear button (C)
Evaluate button (=)
Error handling for invalid expressions (displays "Error" and resets)

## Technologies Used
Python 3
Tkinter (standard library GUI toolkit)

## Installation
No external dependencies are required — Tkinter ships with most standard Python installations.

git clone https://github.com/1anP33in/<repo-name>.git
cd <repo-name>

# Commands to install dependencies
N/A

## How to Run
python main.py

## Usage
Launch the app with python main.py.
Click number and operator buttons to build an expression (e.g. 12+3*(4-1)).
Press = to evaluate the expression.
Press C to clear the current input.
If the expression is invalid, the display shows "Error" and resets automatically.

## Screenshots
![alt text](<Screenshot 2026-08-03 151141.png>)

## Future Improvements
Add keyboard input support
Add backspace/delete-last-character button
Improve visual styling (colors, spacing, button hover states)
Replace eval() with a safer expression parser
Add square root and percentage functions

## Known Issues
Uses Python's eval() to evaluate expressions, which is not safe for untrusted input
No backspace button — mistakes require clearing the entire expression

## License

MIT License

Copyright (a) 2026 1anP33in

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Author

1anP33in - [GitHub](https://github.com/1anP33in)
1anP33in - <- Discord Username