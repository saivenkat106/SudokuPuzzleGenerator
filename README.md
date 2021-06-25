# SudokuPuzzleGenerator
Here we are using a backtracking approach to solve and validate
the Sudoku puzzle.Firstly user get a random puzzle with some
candidates in some random cells.Then starts with[1,1] position we
check the cell is complete or not.If not put a random integer which
satisfies the given conditions and calling the same function with
remaining empty cells.Like this all cells are filled with respective
candidates.For this we splits entire algorithm into small method.
