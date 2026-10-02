# C++ Calculator — Version 2

A beginner-friendly command-line calculator written in C++.

This is the second version of my calculator project. It builds on my earlier calculator by adding more operations, a menu-based interface, repeated calculations using a `do-while` loop, and basic error handling.

## Features

* Addition
* Subtraction
* Multiplication
* Division
* Square root
* Power
* Repeat calculations without restarting the program
* Division-by-zero protection
* Protection against calculating the square root of a negative number
* Invalid operation handling
* Improved terminal interface

## Concepts Used

* Variables
* User input and output
* `if / else if / else`
* `do-while` loops
* `char` and `string` input
* Arithmetic operators
* Basic error handling
* `<cmath>` functions such as `sqrt()` and `pow()`

## Available Operations

| Input   | Operation      |
| ------- | -------------- |
| `+`     | Addition       |
| `-`     | Subtraction    |
| `*`     | Multiplication |
| `/`     | Division       |
| `sqrt`  | Square root    |
| `power` | Power          |

## How to Run

Compile the program using a C++ compiler:

```bash
g++ Calculator.cpp -o Calculator
```

Then run:

```bash
./Calculator
```

On Windows:

```bash
Calculator.exe
```

## Changes from V1

Compared with my first calculator, this version includes:

* A menu-based interface
* Square root operation
* Power operation
* Division-by-zero protection
* Negative-number square-root protection
* Invalid-operation handling
* Improved terminal interface
* String-based operation input for commands such as `sqrt` and `power`
* Continued use of a `do-while` loop for repeated calculations

## Limitations

This is a beginner console project, so it currently has some limitations:

* It only supports the operations listed above.
* Input validation for non-numeric input is limited.
* It does not have a graphical user interface.
* Results are displayed only in the terminal.
* It does not save calculation history.
* Operations must be entered in the expected format.

## Future Improvements

Possible improvements for a future version:

* Better input validation
* More mathematical operations
* Calculation history
* Cleaner and more reusable functions
* A graphical user interface

## What I Learned

This project helped me practice conditional statements and `do-while` loops while building something functional.

Compared with my first calculator, I learned how to expand an existing program with additional operations and basic error handling.

## Version

**Version 2 — Beginner C++ Project**
