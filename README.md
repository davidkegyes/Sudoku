# Sudoku
Precondition to compile is that the JDK 8 JAVA_HOME environment variable is set and added to Path.

To compile $ ./build.bat

````
Sudoku solver
Input parameters are required:
I. The input Sudoku in text file:
   a. On the first line should be one value which is the dimension of the table
   b. On the rest of the lines the values of the table separated with spaces
   c. Values from 1-DIM are the fixed values
   d. Put 0 where the values are missing and the program will fill the place with a proper one
!!! IMPORTANT the Sudoku should be a valid and solvable
II. The method key which will be used to solve the game
   1. Backtracking
   2. Backtracking + MVR + Forward checking
   3. Backtracking + MVR + AC3
Example: java -jar SudokuSolver.jar sudoku9.txt 1
