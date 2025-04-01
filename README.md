# Sudoku Solver

A simple C++ program that solves a 9x9 Sudoku puzzle using a backtracking algorithm.

## Features
- Solves a 9x9 Sudoku puzzle efficiently using recursion and backtracking.
- Prints the Sudoku board before and after solving.
- Validates number placement based on Sudoku rules.

## How It Works
1. The program reads a predefined 9x9 Sudoku board.
2. It tries placing numbers (1-9) in empty cells while following Sudoku rules.
3. If a placement is valid, it moves forward; if not, it backtracks.
4. Once the board is filled correctly, it prints the solution.

## Installation & Usage
### Prerequisites
- C++ compiler (e.g., g++ for GCC)

### Compile and Run
```sh
# Compile the program
 g++ sudoku_solver.cpp -o sudoku_solver

# Run the executable
 ./sudoku_solver
```

## Example
**Input (Unsolved Sudoku):**
```
0 0 0 | 0 3 7 | 0 9 2
6 3 0 | 0 0 0 | 0 0 0
0 9 0 | 0 0 2 | 3 0 5
---------------------
8 7 0 | 0 0 0 | 0 0 1
0 2 0 | 9 0 1 | 0 4 0
9 0 0 | 0 0 0 | 0 2 7
---------------------
1 0 9 | 5 0 0 | 0 7 0
0 0 0 | 0 0 0 | 0 8 6
3 6 0 | 4 1 0 | 0 0 0
```

**Output (Solved Sudoku):**
```
5 1 8 | 6 3 7 | 4 9 2
6 3 2 | 1 9 5 | 8 7 4
7 9 4 | 8 6 2 | 3 1 5
---------------------
8 7 5 | 2 4 3 | 9 6 1
3 2 6 | 9 7 1 | 5 4 8
9 4 1 | 3 5 8 | 6 2 7
---------------------
1 8 9 | 5 2 6 | 7 3 4
4 5 7 | 7 3 9 | 1 8 6
3 6 3 | 4 1 7 | 2 5 9
```

## Contributions
Feel free to contribute by forking the repository and submitting pull requests!
# Sudoku Solver

A simple C++ program that solves a 9x9 Sudoku puzzle using a backtracking algorithm.

## Features
- Solves a 9x9 Sudoku puzzle efficiently using recursion and backtracking.
- Prints the Sudoku board before and after solving.
- Validates number placement based on Sudoku rules.

## How It Works
1. The program reads a predefined 9x9 Sudoku board.
2. It tries placing numbers (1-9) in empty cells while following Sudoku rules.
3. If a placement is valid, it moves forward; if not, it backtracks.
4. Once the board is filled correctly, it prints the solution.

## Installation & Usage
### Prerequisites
- C++ compiler (e.g., g++ for GCC)

### Compile and Run
```sh
# Compile the program
 g++ sudoku_solver.cpp -o sudoku_solver

# Run the executable
 ./sudoku_solver
```

## Example
**Input (Unsolved Sudoku):**
```
0 0 0 | 0 3 7 | 0 9 2
6 3 0 | 0 0 0 | 0 0 0
0 9 0 | 0 0 2 | 3 0 5
---------------------
8 7 0 | 0 0 0 | 0 0 1
0 2 0 | 9 0 1 | 0 4 0
9 0 0 | 0 0 0 | 0 2 7
---------------------
1 0 9 | 5 0 0 | 0 7 0
0 0 0 | 0 0 0 | 0 8 6
3 6 0 | 4 1 0 | 0 0 0
```

**Output (Solved Sudoku):**
```
5 1 8 | 6 3 7 | 4 9 2
6 3 2 | 1 9 5 | 8 7 4
7 9 4 | 8 6 2 | 3 1 5
---------------------
8 7 5 | 2 4 3 | 9 6 1
3 2 6 | 9 7 1 | 5 4 8
9 4 1 | 3 5 8 | 6 2 7
---------------------
1 8 9 | 5 2 6 | 7 3 4
4 5 7 | 7 3 9 | 1 8 6
3 6 3 | 4 1 7 | 2 5 9
```





