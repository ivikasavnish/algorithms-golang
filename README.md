# Algorithms in Golang

A comprehensive collection of algorithms and data structures implemented in Go, organized by subject area.

## 📚 Repository Structure

This repository contains implementations of various algorithms and data structures, grouped into the following categories:

### 🔢 [Sorting Algorithms](./sorting)
Implementations of various sorting techniques:
- **Comparison-based**: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Shell Sort
- **Non-comparison**: Counting Sort, Radix Sort, Bucket Sort

### 🔍 [Searching Algorithms](./searching)
Efficient searching techniques:
- Linear Search, Binary Search, Jump Search, Interpolation Search
- Exponential Search, Ternary Search, Fibonacci Search

### 🌐 [Graph Algorithms](./graph)
Graph traversal and analysis algorithms:
- **Traversal**: BFS, DFS
- **Shortest Path**: Dijkstra, Bellman-Ford, Floyd-Warshall, A*
- **MST**: Kruskal, Prim
- **Cycle Detection**, **Topological Sort**, **SCC** (Kosaraju, Tarjan)
- **Network Flow**: Ford-Fulkerson

### 💡 [Dynamic Programming](./dynamic-programming)
Classic DP problems and optimizations:
- Fibonacci, LCS, LIS, Edit Distance
- Knapsack problems (0/1, Unbounded, Fractional)
- Coin Change, Matrix Chain Multiplication
- Subset Sum, Rod Cutting, Maximum Subarray (Kadane's)

### 📝 [String Algorithms](./string-algorithms)
String manipulation and pattern matching:
- **Pattern Matching**: KMP, Rabin-Karp, Boyer-Moore, Z-Algorithm, Aho-Corasick
- **Suffix Structures**: Suffix Array, Suffix Tree, LCP Array
- Manacher's Algorithm, String Compression, Regular Expression Matching

### 🗂️ [Data Structures](./data-structures)
Fundamental and advanced data structures:
- **Linear**: Linked Lists, Stacks, Queues, Deques
- **Trees**: BST, AVL Tree, Red-Black Tree, B-Tree, Trie, Segment Tree
- **Heaps**: Min Heap, Max Heap, Fibonacci Heap
- **Hash-based**: Hash Table, Hash Set
- **Advanced**: Union-Find, Bloom Filter, Skip List, Interval Tree

### ➕ [Mathematical Algorithms](./math)
Number theory and mathematical computations:
- **Number Theory**: GCD, LCM, Modular Arithmetic, Prime Numbers (Sieve of Eratosthenes)
- **Combinatorics**: Factorial, Binomial Coefficients, Pascal's Triangle
- **Sequences**: Fibonacci, Catalan Numbers
- **Matrix Operations**: Multiplication, Determinant, Transpose

### 🔄 [Backtracking Algorithms](./backtracking)
Exhaustive search with pruning:
- **Puzzles**: N-Queens, Sudoku Solver, Knight's Tour, Rat in Maze
- **Combinatorics**: Permutations, Combinations, Subset Sum
- **Graph**: Hamiltonian Path/Cycle, Graph Coloring
- Word Search, Palindrome Partitioning

### 💰 [Greedy Algorithms](./greedy)
Locally optimal choices leading to global solutions:
- Activity Selection, Job Sequencing, Huffman Coding
- Fractional Knapsack, Interval Scheduling
- Dijkstra's Algorithm, MST (Kruskal, Prim)
- Gas Station, Jump Game

### ⚡ [Divide and Conquer](./divide-and-conquer)
Breaking problems into smaller subproblems:
- Merge Sort, Quick Sort, Quick Select
- Binary Search, Ternary Search
- Strassen's Matrix Multiplication, Maximum Subarray
- Closest Pair of Points, Karatsuba Multiplication, FFT

## 🎯 Goal

The goal of this repository is to provide:
- **Well-documented** algorithm implementations
- **Efficient** and **idiomatic** Go code
- **Comprehensive test coverage** for each algorithm
- **Educational resources** for learning algorithms

## 📖 Usage

Each directory contains:
- `README.md` - Detailed index of algorithms with complexity analysis
- Implementation files (`.go`) - Clean, commented code
- Test files (`_test.go`) - Comprehensive test cases
- Example usage in tests

## 🚀 Getting Started

### Prerequisites
- Go 1.16 or higher

### Installation
```bash
git clone https://github.com/ivikasavnish/algorithms-golang.git
cd algorithms-golang
```

### Running Tests
```bash
# Run all tests
go test ./...

# Run tests for a specific package
go test ./sorting/...

# Run tests with verbose output
go test -v ./...
```

## 📊 Algorithm Complexity Reference

Each algorithm includes time and space complexity information in the following format:
- **Time Complexity**: Best, Average, and Worst case scenarios
- **Space Complexity**: Auxiliary space required

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingAlgorithm`)
3. Commit your changes (`git commit -m 'Add some AmazingAlgorithm'`)
4. Push to the branch (`git push origin feature/AmazingAlgorithm`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources

- [Introduction to Algorithms (CLRS)](https://mitpress.mit.edu/books/introduction-algorithms-third-edition)
- [The Algorithm Design Manual](https://www.algorist.com/)
- [Competitive Programming Handbook](https://cses.fi/book/book.pdf)

## 📈 Progress

This repository is actively being developed. Check individual category README files for implementation status of specific algorithms.
