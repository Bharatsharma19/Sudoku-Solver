# Sudoku-Solver

Suppose we have a Sudoku grid and we have to solve this famous number maze problem, Sudoku. We know that Sudoku is a 9 x 9 number grid, and the whole grid are also divided into 3 x 3 boxes There are some rules to solve the Sudoku.

We have to use digits 1 to 9 for solving this problem.

One digit cannot be repeated in one row, one column or in one 3 x 3 box.

Using backtracking algorithm, we will try to solve Sudoku problem. When some cell is filled with a digit, it checks whether it is valid or not. When it is not valid, it checks for other numbers. If all numbers are checked from 1-9, and no valid digit found to place, it backtracks to previous option.

Backtracking - Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time (by time, here, is referred to the time elapsed till reaching any level of the search tree).

Sudoku = {

        {'5', '3', '.', '.', '7', '.', '.', '.', '.'},
        
        {'6', '.', '.', '1', '9', '5', '.', '.', '.'},
        
        {'.', '9', '8', '.', '.', '.', '.', '6', '.'},
        
        {'8', '.', '.', '.', '6', '.', '.', '.', '3'},
        
        {'4', '.', '.', '8', '.', '3', '.', '.', '1'},
        
        {'7', '.', '.', '.', '2', '.', '.', '.', '6'},
        
        {'.', '6', '.', '.', '.', '.', '2', '8', '.'},
        
        {'.', '.', '.', '4', '1', '9', '.', '.', '5'},
        
        {'.', '.', '.', '.', '8', '.', '.', '7', '9'}
        
        };
        
        Here, ( . ) represents blank number in Sudoku.
              ( Number ), Pre-filled in Sudoku.
        
