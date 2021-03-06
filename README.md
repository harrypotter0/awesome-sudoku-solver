# Sudoku Solver

This Python module can solve even 'hard' sudoku problems almost instantly. It takes
longer to input the board, then it does to solve the problem.  It would probably benefit
from either a problem generator, or a gui interface for input.

__How to use__

import solver
import boards

board = solver.solve(boards.board_hard)


To solve a different problem, pass in the board you want to solve to the constructor
of SudokuBoard.  The board should be a list of 9 strings of length 9. Each entry 
represents a square on the board. Use 0 for blanks. Whitespaces will be stripped, and 
can be added to the strings for readability.

See boards.py for example boards.
