# Sudoku-Solver
This is a console-based Sudoku solver written in C++. It solves 9x9 Sudoku puzzles by implementing a backtracking algorithm.

# Usage
To run the program, first download the main.cpp file from this repository. Then, compile the source code using a C++ compiler:

Copy code:
---------

9 5 7 6 1 3 2 8 4

4 0 3 0 5 0 1 9 6

6 1 2 8 4 0 5 3 7

1 7 0 3 6 4 9 5 2

5 2 4 9 7 1 3 6 8

3 6 9 0 2 8 7 4 1

8 0 5 7 0 2 6 1 3

2 9 1 4 3 6 8 7 5

7 3 0 1 8 5 4 2 0

The program will then print the solved Sudoku puzzle to the console. Note that the input file should contain exactly 9 rows and 9 columns, with each cell separated by a space. If a cell is empty, replace it with a 0.

# Algorithm
The solver uses a backtracking algorithm to solve the puzzle. It tries each number in each empty cell, and then recursively solves the resulting sub-puzzle. If a solution is found, the program returns the solved puzzle. If no solution is found, it backtracks to the previous cell and tries the next number.

# Contributing
If you find a bug or would like to contribute to the project, feel free to create a pull request or submit an issue on GitHub.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
