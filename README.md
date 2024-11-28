# Sudoku Solver

A Python-based Sudoku solver that uses a **graphical user interface (GUI)** built with **Tkinter**. This application allows users to input a Sudoku puzzle, solve it using a backtracking algorithm, and display the solution interactively.

## Features
- **Interactive Grid**: Enter Sudoku puzzles directly into a 9x9 grid.
- **Solve Button**: Automatically solves the puzzle using backtracking.
- **Clear Button**: Resets the board for a new puzzle.
- **Error Handling**: Alerts the user if no solution exists.

## How It Works
1. Input the Sudoku puzzle directly into the grid (use `0` for empty cells).
2. Click the **"Solve"** button to solve the puzzle.
3. Click the **"Clear"** button to reset the board.

The program validates inputs, solves the puzzle using a backtracking algorithm, and displays the solution in the GUI.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   cd sudoku-solver-gui
   ```

2. Install Python (if not already installed). [Download Python](https://www.python.org/downloads/).

3. Run the script:
   ```bash
   python sudoku_solver.py
   ```

## Requirements
This project requires Python 3.x. No additional libraries are needed beyond the standard library.

## File Structure
```
sudoku-solver-gui/
│
├── sudoku_solver.py   # Main Python script for the application
├── README.md              # Project documentation

```

## How to Use
1. Launch the application by running the script:
   ```bash
   python sudoku_solver.py
   ```
2. Enter the Sudoku puzzle into the grid.
3. Click **"Solve"** to display the solution.
4. Use **"Clear"** to reset the grid.

## Algorithm Overview
The solver uses the **backtracking algorithm** to find the solution:
- Iterates through the grid to locate empty cells.
- Tests numbers from 1 to 9 in each cell.
- Validates the placement using Sudoku rules (row, column, and subgrid constraints).
- Recursively solves the board until all cells are filled or determines that no solution exists.
