# Extended_Sudoku

We have a hybrid solution, getting the advantages of using the backtracking and the constraint propagation methodologies together. In a contradiction situation, the backtracking algorithm intends to place subsequent valid digits in the cells as well as un-doing any previous actions. Application of Sudoku rules to eliminate unlikely numbers by means of constraint propagation technique serves to narrow down the problem area, whereas AI-based algorithms could theoretically outperform it (constraint propagation) by means of solutions provided with given clues. This combined effect also adds reliability and convenience when completing Sudoku puzzles.

## Diagonal Sudoku
Also we recommend adding a parameter to the solver class that users can set any one of them to get a solution to the Sudoku puzzle the conventional way or Diagonal Sudoku way. In a Diagonal Sudoku, only nine numbers from 1 to 9 are available, and the two diagonals, the main diagonal being read from left to right and the secondary one from right to left, are each made up of four. The implementation of this is done by creating the solver with an added constraint to it.
