# Greedy Algorithms

This directory contains implementations of various greedy algorithms in Go.

## Algorithms to be Implemented

### Activity Selection Problems

1. **Activity Selection Problem** - `activity_selection.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(1)
   - Select maximum non-overlapping activities

2. **Job Sequencing Problem** - `job_sequencing.go`
   - Time Complexity: O(n² log n)
   - Space Complexity: O(n)
   - Schedule jobs to maximize profit with deadlines

3. **Job Scheduling with Minimum Loss** - `job_scheduling_min_loss.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Minimize loss in job scheduling

### Huffman Coding

4. **Huffman Encoding** - `huffman_encoding.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(n)
   - Optimal prefix-free encoding

5. **Huffman Decoding** - `huffman_decoding.go`
   - Time Complexity: O(n)
   - Space Complexity: O(n)
   - Decode Huffman encoded data

### Minimum Spanning Tree

6. **Kruskal's Algorithm (Greedy MST)** - `kruskal_greedy.go`
   - Time Complexity: O(E log E)
   - Space Complexity: O(V)
   - Greedy approach to MST

7. **Prim's Algorithm (Greedy MST)** - `prim_greedy.go`
   - Time Complexity: O(E log V)
   - Space Complexity: O(V)
   - Greedy approach to MST

### Shortest Path

8. **Dijkstra's Algorithm (Greedy)** - `dijkstra_greedy.go`
   - Time Complexity: O((V + E) log V)
   - Space Complexity: O(V)
   - Greedy shortest path for non-negative weights

### Fractional Knapsack

9. **Fractional Knapsack** - `fractional_knapsack.go`
   - Time Complexity: O(n log n)
   - Space Complexity: O(1)
   - Maximize value with fractional items

### Coin Change

10. **Coin Change (Greedy)** - `coin_change_greedy.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Works for canonical coin systems

### Interval Scheduling

11. **Interval Scheduling Maximization** - `interval_scheduling.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Select maximum non-overlapping intervals

12. **Minimum Platforms Required** - `minimum_platforms.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Find minimum platforms for trains

13. **Meeting Rooms** - `meeting_rooms.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Check if person can attend all meetings

### Minimize/Maximize Problems

14. **Minimize Cash Flow** - `minimize_cash_flow.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(n)
    - Minimize number of transactions

15. **Minimize Maximum Distance** - `minimize_max_distance.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Place gas stations optimally

16. **Maximize Sum of Array** - `maximize_array_sum.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Rearrange arrays for maximum sum

### Load Balancing

17. **Load Balancing** - `load_balancing.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(k)
    - Distribute tasks among servers

18. **Task Scheduling** - `task_scheduling.go`
    - Time Complexity: O(n)
    - Space Complexity: O(26)
    - Schedule tasks with cooling period

### Partition Problems

19. **Partition Array into Two Arrays** - `partition_array.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Minimize difference between partitions

### Water Collection

20. **Water Connection Problem** - `water_connection.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Connect houses with water pipes

### Stock Problems

21. **Buy and Sell Stock (Multiple Transactions)** - `stock_multiple_transactions.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Maximize profit with unlimited transactions

### Miscellaneous Greedy Problems

22. **Egyptian Fraction** - `egyptian_fraction.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(log n)
    - Represent fraction as sum of unit fractions

23. **Minimize Product Sum** - `minimize_product_sum.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Pair elements to minimize product sum

24. **Minimum Sum of Product** - `min_sum_of_product.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Minimize sum of products

25. **Policemen Catch Thieves** - `policemen_catch_thieves.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Maximum thieves caught within distance k

26. **Assign Mice to Holes** - `assign_mice_to_holes.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Minimize maximum time

27. **Paper Cut into Squares** - `paper_cut_squares.go`
    - Time Complexity: O(log min(m, n))
    - Space Complexity: O(1)
    - Minimum cuts to get squares

28. **Minimum Cost to Connect Ropes** - `connect_ropes.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(n)
    - Minimize cost using heap

29. **Gas Station** - `gas_station.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Find starting point for circular tour

30. **Jump Game** - `jump_game.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Check if can reach end with jumps

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
