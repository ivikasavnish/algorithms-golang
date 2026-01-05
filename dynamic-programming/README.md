# Dynamic Programming Algorithms

This directory contains implementations of various dynamic programming algorithms in Go.

## Algorithms to be Implemented

### Classic DP Problems

1. **Fibonacci Numbers** - `fibonacci.go`
   - Time Complexity: O(n)
   - Space Complexity: O(n) or O(1) optimized
   - Classic introduction to DP

2. **Longest Common Subsequence (LCS)** - `longest_common_subsequence.go`
   - Time Complexity: O(m × n)
   - Space Complexity: O(m × n)
   - Find longest subsequence in two sequences

3. **Longest Increasing Subsequence (LIS)** - `longest_increasing_subsequence.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Find longest increasing subsequence

4. **Edit Distance (Levenshtein)** - `edit_distance.go`
   - Time Complexity: O(m × n)
   - Space Complexity: O(m × n)
   - Minimum edits to transform one string to another

### Knapsack Problems

5. **0/1 Knapsack** - `knapsack_01.go`
   - Time Complexity: O(n × W)
   - Space Complexity: O(n × W)
   - Items can be taken once

6. **Unbounded Knapsack** - `knapsack_unbounded.go`
   - Time Complexity: O(n × W)
   - Space Complexity: O(W)
   - Items can be taken multiple times

7. **Fractional Knapsack** - `knapsack_fractional.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(1)
   - Items can be broken into fractions

### Coin Change Problems

8. **Coin Change (Minimum Coins)** - `coin_change_min.go`
   - Time Complexity: O(n × amount)
   - Space Complexity: O(amount)
   - Minimum coins to make amount

9. **Coin Change (Number of Ways)** - `coin_change_ways.go`
   - Time Complexity: O(n × amount)
   - Space Complexity: O(amount)
   - Count ways to make amount

### Matrix Chain Multiplication

10. **Matrix Chain Multiplication** - `matrix_chain_multiplication.go`
    - Time Complexity: O(n³)
    - Space Complexity: O(n²)
    - Optimal parenthesization

### Subsequence Problems

11. **Longest Palindromic Subsequence** - `longest_palindromic_subsequence.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(n²)
    - Find longest palindromic subsequence

12. **Longest Palindromic Substring** - `longest_palindromic_substring.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(n²)
    - Find longest contiguous palindrome

### Path Problems

13. **Unique Paths in Grid** - `unique_paths.go`
    - Time Complexity: O(m × n)
    - Space Complexity: O(m × n)
    - Count paths from top-left to bottom-right

14. **Minimum Path Sum** - `minimum_path_sum.go`
    - Time Complexity: O(m × n)
    - Space Complexity: O(m × n)
    - Find minimum sum path in grid

15. **Maximum Subarray (Kadane's)** - `maximum_subarray.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Find contiguous subarray with maximum sum

### Partition Problems

16. **Subset Sum** - `subset_sum.go`
    - Time Complexity: O(n × sum)
    - Space Complexity: O(n × sum)
    - Check if subset with given sum exists

17. **Partition Equal Subset Sum** - `partition_equal_subset.go`
    - Time Complexity: O(n × sum)
    - Space Complexity: O(sum)
    - Partition array into two equal sum subsets

### Other DP Problems

18. **Rod Cutting** - `rod_cutting.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(n)
    - Maximize profit by cutting rod

19. **Egg Dropping Problem** - `egg_dropping.go`
    - Time Complexity: O(n × k²)
    - Space Complexity: O(n × k)
    - Minimum trials to find critical floor

20. **Word Break** - `word_break.go`
    - Time Complexity: O(n² × m)
    - Space Complexity: O(n)
    - Check if string can be segmented into dictionary words

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
