# Solving-Sudoku-By-BackTracking

BackTracking: Back Tracking is finding solution to the computational problems mainly constraint satisfaction problems by incrementally building the 
candidates to solutions and abandoning each partial candidates in between that do not correspont to the correct final solution.

Like any other back tracking problems, sudoku can be solved.

Given a partially filled 9*9 grid, our goal is to completely fill the grid by assigning digits (1-9) in all the empty cells.
Each row and column and the subgrid should have exactly one instance of each digit in the range (1-9).

Before assigning numbers to the empty cell, the back tracking algo checks if it is safe to assign that number to that cell by checking whether the 
same number is present in same row/column/sub grid.

After assigning the number, recursively the grid is checked if the solution is correct, if not correct the assigned number is reset to 0 and tried with the next number.

