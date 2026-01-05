# Sorting Algorithms

This directory contains implementations of various sorting algorithms in Go.

## Algorithms to be Implemented

### Comparison-Based Sorting

1. **Bubble Sort** - `bubble_sort.go`
   - Time Complexity: O(n²)
   - Space Complexity: O(1)
   - Simple comparison-based sorting algorithm

2. **Selection Sort** - `selection_sort.go`
   - Time Complexity: O(n²)
   - Space Complexity: O(1)
   - Finds minimum element and places it at the beginning

3. **Insertion Sort** - `insertion_sort.go`
   - Time Complexity: O(n²)
   - Space Complexity: O(1)
   - Builds sorted array one item at a time

4. **Merge Sort** - `merge_sort.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Divide and conquer algorithm

5. **Quick Sort** - `quick_sort.go`
   - Time Complexity: O(n log n) average, O(n²) worst case
   - Space Complexity: O(log n)
   - Efficient divide and conquer algorithm

6. **Heap Sort** - `heap_sort.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(1)
   - Uses binary heap data structure

7. **Shell Sort** - `shell_sort.go`
   - Time Complexity: O(n log n) to O(n²) depending on gap sequence
   - Space Complexity: O(1)
   - Generalization of insertion sort

### Non-Comparison Sorting

8. **Counting Sort** - `counting_sort.go`
   - Time Complexity: O(n + k) where k is the range
   - Space Complexity: O(k)
   - Integer sorting algorithm

9. **Radix Sort** - `radix_sort.go`
   - Time Complexity: O(d × (n + k))
   - Space Complexity: O(n + k)
   - Sorts integers by processing digits

10. **Bucket Sort** - `bucket_sort.go`
    - Time Complexity: O(n + k) average case
    - Space Complexity: O(n + k)
    - Distributes elements into buckets

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
