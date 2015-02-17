# cse20212-lab5
Lab 5 
A traditional Sudoku puzzle is either a 4x4, 9x9 or 16x16 grid. In the case of a 9x9
numeric puzzle, a solved puzzle has the following three properties:
Every column contains the symbols 1–9 exactly once
Every row contains the symbols 1–9 exactly once
Each of the 3x3 minigrids contains the symbols 1–9 exactly once.

Develop a templated Puzzle class such that you can
easily create a Puzzle<int> (traditional Sudoku) or a Puzzle<char>

Develop an interactive game that will read in a traditional (1-9; 0 = empty) Sudoku
puzzle and ask a user to enter in a specific cell to replace its value. Your simple game
must do the following:
Use your templated class from Part 2
Determine if a given entry is valid based on the current state of the board, i.e., that
number does not occur in the same row, column or mini grid
Determine if a puzzle is completed successfully
