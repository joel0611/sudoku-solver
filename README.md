# Sudoku Solver using Backtracking

This Python project is designed to solve a Sudoku puzzle using a backtracking algorithm. Sudoku is a classic number puzzle game that requires filling a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 sub-grids contain all of the digits from 1 to 9.

## How it Works
The project consists of a Python script that implements a backtracking algorithm to solve Sudoku puzzles. Here's how it works:
1. Print Grid Function: The print_grid function is used to display the Sudoku grid on the console.
2. Find Empty Location Function: The find_empty_location function scans the grid to find an empty cell (represented by a 0) and returns its coordinates in the l list. If no empty cells are found, it returns False.
3. Used in Row/Column/Box Functions: These functions check if a given number is already used in a specific row, column, or 3x3 sub-grid.
4. Check Location is Safe Function: The check_location_is_safe function checks if it's safe to place a number in a specific cell by verifying that the number is not already used in the same row, column, or 3x3 sub-grid.
5. Solve Sudoku Function: The solve_sudoku function is the heart of the algorithm. It recursively attempts to solve the Sudoku puzzle by trying numbers from 1 to 9 in empty cells, backtracking when necessary. If a solution is found, it returns True. If no solution exists, it returns False.
6. Grid Initialization: A sample Sudoku grid is provided in the script as a 9x9 list, where 0 represents empty cells and other numbers represent initial values.
7. Solving the Sudoku: The script calls the solve_sudoku function on the provided grid and, if a solution exists, it prints the solved Sudoku puzzle. If no solution exists, it indicates that.

## Usage
To use this Sudoku solver, follow these steps:
1. Modify the grid variable to represent the Sudoku puzzle you want to solve. Use 0 for empty cells and fill in the initial values.
2. Run the script in a Python environment.
3. The script will attempt to solve the Sudoku puzzle and print the solution if one exists.
