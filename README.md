# Sudoku-project
End semester project-Sudoku in C language
Objective

The objective of this project is to develop a beginner-friendly C program that solves a 9×9 Sudoku puzzle entered by the user.
This project demonstrates key programming concepts such as:

2D arrays

Backtracking algorithm

User input handling

Modular programming

Recursion

Logical checking functions (row, column, box validation)



---

Project Description

This C program allows the user to:

✔ Enter a 9×9 Sudoku puzzle manually (81 numbers).
✔ Use 0 to represent empty cells.
✔ View the puzzle formatted in a grid.
✔ Let the program solve the puzzle automatically using backtracking.
✔ Display the solved puzzle OR show a message if no solution exists.

What the program does internally:

Prints the Sudoku board in a clean layout

Searches for the next empty position

Checks if placing a number is safe (row/column/3×3 box check)

Uses a recursive backtracking algorithm to fill the puzzle

Returns a fully solved Sudoku grid


The program does not use any predefined puzzles or libraries.
The user must enter all values manually.


---

Technologies Used

C Programming Language

GCC Compiler (or any standard C compiler)

VS Code / Terminal / Command Prompt



---

How to Compile

Use the following command:

gcc sudoku.c -o sudoku

This creates an executable file named sudoku (or sudoku.exe on Windows).


---

How to Run

On Windows:

sudoku.exe

On Linux / macOS:

./sudoku


---

Sample Input

to see user input view screenshots


---

Sample Output

to see user output view screenshots
If the puzzle has no valid solution:

No valid solution exists for this puzzle.


---
Screenshots

(Attach your screenshots of input and output here)

Examples:

Output for sudoku1.jpg — User Input

Output for sudoku2.jpg — Solved Sudoku Output

Assumptions

User enters only integers (0–9)

0 represents an empty cell

Puzzle must be 9×9

Backtracking is used (depth-first search approach)

No graphical UI—text-based only


Features

Clean and formatted Sudoku board printing

Modular code with separate functions

Row/column/box safety checks

Efficient backtracking algorithm

Handles invalid numbers automatically

Beginner-friendly and fully commented code

Learning Outcomes

From this project, students learn how to:

Use 2D arrays effectively

Implement recursive backtracking

Write clean, structured, modular C code

Perform input validation

Print formatted output

Document and organize a project for GitHub

Files Included

sudoku.c — Full C source code

README.md — Documentation.

Screenshots - user input,output





