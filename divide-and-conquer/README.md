# Divide and Conquer Algorithms

This directory contains implementations of various divide and conquer algorithms in Go.

## Algorithms to be Implemented

### Sorting Algorithms

1. **Merge Sort** - `merge_sort.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Classic divide and conquer sorting

2. **Quick Sort** - `quick_sort.go`
   - Time Complexity: O(n log n) average, O(n²) worst
   - Space Complexity: O(log n)
   - In-place sorting with partitioning

3. **Quick Select** - `quick_select.go`
   - Time Complexity: O(n) average
   - Space Complexity: O(1)
   - Find kth smallest element

### Searching Algorithms

4. **Binary Search** - `binary_search.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1) iterative, O(log n) recursive
   - Search in sorted array

5. **Ternary Search** - `ternary_search.go`
   - Time Complexity: O(log₃ n)
   - Space Complexity: O(1)
   - Search by dividing into three parts

### Matrix Operations

6. **Strassen's Matrix Multiplication** - `strassen_matrix_multiplication.go`
   - Time Complexity: O(n^2.807)
   - Space Complexity: O(n²)
   - Faster than standard O(n³) multiplication

7. **Maximum Subarray (Divide and Conquer)** - `maximum_subarray.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(log n)
   - Find maximum sum subarray

### Geometric Algorithms

8. **Closest Pair of Points** - `closest_pair_of_points.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Find two closest points in plane

9. **Convex Hull (Quick Hull)** - `convex_hull_quick_hull.go`
   - Time Complexity: O(n log n) average
   - Space Complexity: O(n)
   - Find convex hull of points

10. **Skyline Problem** - `skyline_problem.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Merge building silhouettes

### Tree Problems

11. **Binary Tree Maximum Path Sum** - `binary_tree_max_path_sum.go`
    - Time Complexity: O(n)
    - Space Complexity: O(h)
    - Find maximum path sum in tree

12. **Binary Tree Diameter** - `binary_tree_diameter.go`
    - Time Complexity: O(n)
    - Space Complexity: O(h)
    - Find longest path between nodes

13. **Lowest Common Ancestor** - `lowest_common_ancestor.go`
    - Time Complexity: O(n)
    - Space Complexity: O(h)
    - Find LCA in binary tree

### Array Problems

14. **Count Inversions** - `count_inversions.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Count pairs where arr[i] > arr[j] and i < j

15. **Find Peak Element** - `find_peak_element.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Find local maximum

16. **Median of Two Sorted Arrays** - `median_two_sorted_arrays.go`
    - Time Complexity: O(log(min(m, n)))
    - Space Complexity: O(1)
    - Find median efficiently

### Computational Geometry

17. **Line Segment Intersection** - `line_segment_intersection.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Find all intersections

### Number Theory

18. **Karatsuba Multiplication** - `karatsuba_multiplication.go`
    - Time Complexity: O(n^1.585)
    - Space Complexity: O(n)
    - Fast large number multiplication

19. **Fast Fourier Transform (FFT)** - `fft.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Polynomial multiplication

20. **Integer Multiplication (Large Numbers)** - `large_integer_multiplication.go`
    - Time Complexity: O(n^1.585)
    - Space Complexity: O(n)
    - Multiply large integers

### Other Problems

21. **Tower of Hanoi** - `tower_of_hanoi.go`
    - Time Complexity: O(2^n)
    - Space Complexity: O(n)
    - Classic recursive problem

22. **Calculate Power** - `calculate_power.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(log n) recursive
    - Compute x^n efficiently

23. **Majority Element** - `majority_element.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(log n)
    - Find element appearing more than n/2 times

24. **Count of Smaller Numbers After Self** - `count_smaller_after_self.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Count smaller elements to the right

25. **Reverse Pairs** - `reverse_pairs.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Count pairs where arr[i] > 2 × arr[j] and i < j

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
