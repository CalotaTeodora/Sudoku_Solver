# Sudoku Solver

This is a simple Sudoku solver written in C++ that uses a backtracking algorithm to find the solution to a given Sudoku puzzle.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/sudoku-solver.git
    ```

2. **Compile the code:**

    ```bash
    python sudoku_solver.py
    ```

3. **Run the program:**

    ```bash
    ./sudoku_solver
    ```

## Usage

The Sudoku puzzle is represented as a 9x9 grid where empty cells are denoted by 0. To solve a Sudoku puzzle, simply modify the `board` array in the `sudoku_solver.cpp` file with the puzzle you want to solve:

```cpp
int board[9][9] = {
    {7, 8, 0, 4, 0, 0, 1, 2, 0},
    {6, 0, 0, 0, 7, 5, 0, 0, 9},
    {0, 0, 0, 6, 0, 1, 0, 7, 8},
    {0, 0, 7, 0, 4, 0, 2, 6, 0},
    {0, 0, 1, 0, 5, 0, 9, 3, 0},
    {9, 0, 4, 0, 6, 0, 0, 0, 5},
    {0, 7, 0, 3, 0, 0, 0, 1, 2},
    {1, 2, 0, 0, 0, 7, 4, 0, 0},
    {0, 4, 9, 2, 0, 6, 0, 0, 7}
};
```

Run the program again, and it will display the solved Sudoku puzzle.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

Happy Sudoku solving! 🧩
