# String Algorithms

This directory contains implementations of various string algorithms in Go.

## Algorithms to be Implemented

### Pattern Matching Algorithms

1. **Naive Pattern Matching** - `naive_pattern_matching.go`
   - Time Complexity: O(m × n)
   - Space Complexity: O(1)
   - Simple brute force approach

2. **Knuth-Morris-Pratt (KMP) Algorithm** - `kmp.go`
   - Time Complexity: O(m + n)
   - Space Complexity: O(m)
   - Efficient pattern matching using prefix function

3. **Rabin-Karp Algorithm** - `rabin_karp.go`
   - Time Complexity: O(m + n) average
   - Space Complexity: O(1)
   - Uses rolling hash for pattern matching

4. **Boyer-Moore Algorithm** - `boyer_moore.go`
   - Time Complexity: O(m + n)
   - Space Complexity: O(m)
   - Bad character and good suffix heuristics

5. **Z-Algorithm** - `z_algorithm.go`
   - Time Complexity: O(n)
   - Space Complexity: O(n)
   - Linear time pattern matching

6. **Aho-Corasick Algorithm** - `aho_corasick.go`
   - Time Complexity: O(m + n + z)
   - Space Complexity: O(m × k)
   - Multiple pattern matching

### String Manipulation

7. **String Reversal** - `string_reversal.go`
   - Time Complexity: O(n)
   - Space Complexity: O(1)
   - Reverse a string in place

8. **Palindrome Check** - `palindrome_check.go`
   - Time Complexity: O(n)
   - Space Complexity: O(1)
   - Check if string is palindrome

9. **Anagram Check** - `anagram_check.go`
   - Time Complexity: O(n)
   - Space Complexity: O(1)
   - Check if two strings are anagrams

10. **String Permutations** - `string_permutations.go`
    - Time Complexity: O(n!)
    - Space Complexity: O(n)
    - Generate all permutations

### Suffix-Based Algorithms

11. **Suffix Array** - `suffix_array.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Array of sorted suffixes

12. **Suffix Tree** - `suffix_tree.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Compressed trie of all suffixes

13. **Longest Common Prefix (LCP) Array** - `lcp_array.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Used with suffix arrays

### Other String Algorithms

14. **Longest Common Substring** - `longest_common_substring.go`
    - Time Complexity: O(m × n)
    - Space Complexity: O(m × n)
    - Find longest common substring

15. **Longest Repeated Substring** - `longest_repeated_substring.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Find longest repeated substring

16. **Manacher's Algorithm** - `manacher.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Find longest palindromic substring in linear time

17. **String Compression** - `string_compression.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Compress consecutive characters

18. **Regular Expression Matching** - `regex_matching.go`
    - Time Complexity: O(m × n)
    - Space Complexity: O(m × n)
    - Dynamic programming approach

19. **Wildcard Pattern Matching** - `wildcard_matching.go`
    - Time Complexity: O(m × n)
    - Space Complexity: O(m × n)
    - Match with * and ? wildcards

20. **Run-Length Encoding** - `run_length_encoding.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Encode consecutive characters

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
