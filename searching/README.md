# Searching Algorithms

This directory contains implementations of various searching algorithms in Go.

## Algorithms to be Implemented

1. **Linear Search** - `linear_search.go`
   - Time Complexity: O(n)
   - Space Complexity: O(1)
   - Sequential search through array

2. **Binary Search** - `binary_search.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1) iterative, O(log n) recursive
   - Efficient search in sorted arrays

3. **Jump Search** - `jump_search.go`
   - Time Complexity: O(√n)
   - Space Complexity: O(1)
   - Works on sorted arrays by jumping blocks

4. **Interpolation Search** - `interpolation_search.go`
   - Time Complexity: O(log log n) for uniformly distributed data
   - Space Complexity: O(1)
   - Improved binary search for uniformly distributed values

5. **Exponential Search** - `exponential_search.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1)
   - Useful for unbounded/infinite arrays

6. **Ternary Search** - `ternary_search.go`
   - Time Complexity: O(log₃ n)
   - Space Complexity: O(1)
   - Divides array into three parts

7. **Fibonacci Search** - `fibonacci_search.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1)
   - Uses Fibonacci numbers to divide array

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
