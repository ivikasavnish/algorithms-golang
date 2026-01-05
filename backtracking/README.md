# Backtracking Algorithms

This directory contains implementations of various backtracking algorithms in Go.

## Algorithms to be Implemented

### Puzzle Solving

1. **N-Queens Problem** - `n_queens.go`
   - Time Complexity: O(n!)
   - Space Complexity: O(n²)
   - Place n queens on n×n chessboard

2. **Sudoku Solver** - `sudoku_solver.go`
   - Time Complexity: O(9^m) where m is empty cells
   - Space Complexity: O(1)
   - Solve 9×9 Sudoku puzzle

3. **Knight's Tour** - `knights_tour.go`
   - Time Complexity: O(8^(n²))
   - Space Complexity: O(n²)
   - Visit all squares on chessboard

4. **Rat in a Maze** - `rat_in_maze.go`
   - Time Complexity: O(2^(n²))
   - Space Complexity: O(n²)
   - Find path from start to end

### Combinatorial Problems

5. **All Permutations** - `permutations.go`
   - Time Complexity: O(n!)
   - Space Complexity: O(n)
   - Generate all permutations of array

6. **All Combinations** - `combinations.go`
   - Time Complexity: O(2^n)
   - Space Complexity: O(n)
   - Generate all combinations

7. **Combination Sum** - `combination_sum.go`
   - Time Complexity: O(2^n)
   - Space Complexity: O(n)
   - Find combinations that sum to target

8. **Subset Sum** - `subset_sum.go`
   - Time Complexity: O(2^n)
   - Space Complexity: O(n)
   - Find subsets with given sum

9. **Generate Parentheses** - `generate_parentheses.go`
   - Time Complexity: O(4^n / √n)
   - Space Complexity: O(n)
   - Generate all valid parentheses combinations

### Partitioning Problems

10. **Palindrome Partitioning** - `palindrome_partitioning.go`
    - Time Complexity: O(n × 2^n)
    - Space Complexity: O(n)
    - Partition string into palindromes

11. **String Partitioning** - `string_partitioning.go`
    - Time Complexity: O(2^n)
    - Space Complexity: O(n)
    - All ways to partition string

### Graph-Based Backtracking

12. **Hamiltonian Path** - `hamiltonian_path.go`
    - Time Complexity: O(n!)
    - Space Complexity: O(n)
    - Path visiting each vertex once

13. **Hamiltonian Cycle** - `hamiltonian_cycle.go`
    - Time Complexity: O(n!)
    - Space Complexity: O(n)
    - Cycle visiting each vertex once

14. **Graph Coloring** - `graph_coloring.go`
    - Time Complexity: O(m^n)
    - Space Complexity: O(n)
    - Color graph with m colors

15. **M-Coloring Problem** - `m_coloring.go`
    - Time Complexity: O(m^n)
    - Space Complexity: O(n)
    - Check if graph can be colored with m colors

### String Pattern Problems

16. **Word Search in Grid** - `word_search.go`
    - Time Complexity: O(n × m × 4^L)
    - Space Complexity: O(L)
    - Find word in 2D grid

17. **Regular Expression Matching (Backtracking)** - `regex_backtracking.go`
    - Time Complexity: O(2^n)
    - Space Complexity: O(n)
    - Match pattern with wildcards

18. **Wildcard Matching (Backtracking)** - `wildcard_backtracking.go`
    - Time Complexity: O(2^n)
    - Space Complexity: O(n)
    - Match with * and ? wildcards

### Constraint Satisfaction

19. **Crossword Puzzle Solver** - `crossword_solver.go`
    - Time Complexity: Exponential
    - Space Complexity: O(n × m)
    - Fill crossword with words

20. **Cryptarithmetic Solver** - `cryptarithmetic.go`
    - Time Complexity: O(10!)
    - Space Complexity: O(1)
    - Solve arithmetic puzzles with letters

21. **Magic Square** - `magic_square.go`
    - Time Complexity: O(n!)
    - Space Complexity: O(n²)
    - Generate magic squares

### Miscellaneous

22. **Letter Combinations of Phone Number** - `phone_number_combinations.go`
    - Time Complexity: O(4^n)
    - Space Complexity: O(n)
    - Generate letter combinations

23. **Restore IP Addresses** - `restore_ip_addresses.go`
    - Time Complexity: O(1) constant combinations
    - Space Complexity: O(1)
    - Generate valid IP addresses

24. **Partition to K Equal Sum Subsets** - `k_equal_sum_subsets.go`
    - Time Complexity: O(k × 2^n)
    - Space Complexity: O(n)
    - Partition array into k subsets

25. **Tug of War** - `tug_of_war.go`
    - Time Complexity: O(2^n)
    - Space Complexity: O(n)
    - Divide into two equal sum teams

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
