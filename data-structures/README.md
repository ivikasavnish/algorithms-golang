# Data Structures

This directory contains implementations of various data structures in Go.

## Data Structures to be Implemented

### Linear Data Structures

1. **Singly Linked List** - `singly_linked_list.go`
   - Operations: Insert, Delete, Search, Traverse
   - Time Complexity: O(1) for insertion at head, O(n) for search

2. **Doubly Linked List** - `doubly_linked_list.go`
   - Operations: Insert, Delete, Search, Traverse (forward/backward)
   - Time Complexity: O(1) for insertion/deletion with pointer, O(n) for search

3. **Circular Linked List** - `circular_linked_list.go`
   - Operations: Insert, Delete, Search, Traverse
   - Last node points to first node

4. **Stack** - `stack.go`
   - Operations: Push, Pop, Peek, IsEmpty
   - Time Complexity: O(1) for all operations
   - LIFO (Last In First Out)

5. **Queue** - `queue.go`
   - Operations: Enqueue, Dequeue, Front, IsEmpty
   - Time Complexity: O(1) for all operations
   - FIFO (First In First Out)

6. **Deque (Double-Ended Queue)** - `deque.go`
   - Operations: InsertFront, InsertRear, DeleteFront, DeleteRear
   - Time Complexity: O(1) for all operations

7. **Priority Queue** - `priority_queue.go`
   - Operations: Insert, ExtractMax/Min, GetMax/Min
   - Time Complexity: O(log n) for insert and extract
   - Usually implemented with heap

### Tree Data Structures

8. **Binary Tree** - `binary_tree.go`
   - Basic binary tree structure
   - Traversals: Inorder, Preorder, Postorder, Level-order

9. **Binary Search Tree (BST)** - `binary_search_tree.go`
   - Operations: Insert, Delete, Search, Min, Max
   - Time Complexity: O(h) where h is height
   - Average case: O(log n), Worst case: O(n)

10. **AVL Tree** - `avl_tree.go`
    - Self-balancing BST
    - Time Complexity: O(log n) for all operations
    - Balance factor maintained

11. **Red-Black Tree** - `red_black_tree.go`
    - Self-balancing BST
    - Time Complexity: O(log n) for all operations
    - Less strict balancing than AVL

12. **B-Tree** - `b_tree.go`
    - Self-balancing search tree for disk storage
    - Time Complexity: O(log n)
    - Multiple keys per node

13. **Trie (Prefix Tree)** - `trie.go`
    - Operations: Insert, Search, StartsWith, Delete
    - Time Complexity: O(m) where m is key length
    - Used for string operations

14. **Segment Tree** - `segment_tree.go`
    - Range query and update operations
    - Time Complexity: O(log n) for query and update
    - Used for range sum, min, max queries

15. **Fenwick Tree (Binary Indexed Tree)** - `fenwick_tree.go`
    - Efficient prefix sum queries and updates
    - Time Complexity: O(log n)
    - Space efficient

### Heap Data Structures

16. **Min Heap** - `min_heap.go`
    - Operations: Insert, ExtractMin, GetMin, Heapify
    - Time Complexity: O(log n) for insert and extract
    - Parent is smaller than children

17. **Max Heap** - `max_heap.go`
    - Operations: Insert, ExtractMax, GetMax, Heapify
    - Time Complexity: O(log n) for insert and extract
    - Parent is larger than children

18. **Fibonacci Heap** - `fibonacci_heap.go`
    - Advanced heap structure
    - Time Complexity: O(1) amortized for insert, O(log n) for extract
    - Used in Dijkstra's algorithm

### Hash-Based Data Structures

19. **Hash Table** - `hash_table.go`
    - Operations: Insert, Delete, Search
    - Time Complexity: O(1) average case
    - Collision handling: Chaining or Open Addressing

20. **Hash Set** - `hash_set.go`
    - Operations: Add, Remove, Contains
    - Time Complexity: O(1) average case
    - Stores unique elements

### Graph Data Structures

21. **Graph (Adjacency List)** - `graph_adjacency_list.go`
    - Space Complexity: O(V + E)
    - Efficient for sparse graphs

22. **Graph (Adjacency Matrix)** - `graph_adjacency_matrix.go`
    - Space Complexity: O(V²)
    - Efficient for dense graphs

### Advanced Data Structures

23. **Union-Find (Disjoint Set)** - `union_find.go`
    - Operations: Union, Find
    - Time Complexity: O(α(n)) with path compression
    - Used in Kruskal's algorithm

24. **Bloom Filter** - `bloom_filter.go`
    - Probabilistic data structure
    - Space-efficient set membership testing
    - May have false positives

25. **Skip List** - `skip_list.go`
    - Probabilistic alternative to balanced trees
    - Time Complexity: O(log n) average case
    - Multiple levels of linked lists

26. **Suffix Trie** - `suffix_trie.go`
    - Trie of all suffixes
    - Used for pattern matching

27. **Interval Tree** - `interval_tree.go`
    - Store and query intervals
    - Time Complexity: O(log n) for query
    - Used for scheduling problems

28. **K-D Tree** - `kd_tree.go`
    - Space partitioning for k-dimensional points
    - Time Complexity: O(log n) average for nearest neighbor
    - Used in computer graphics

## Usage

Each data structure will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
