# Graph Algorithms

This directory contains implementations of various graph algorithms in Go.

## Algorithms to be Implemented

### Graph Traversal

1. **Breadth-First Search (BFS)** - `bfs.go`
   - Time Complexity: O(V + E)
   - Space Complexity: O(V)
   - Level-order traversal

2. **Depth-First Search (DFS)** - `dfs.go`
   - Time Complexity: O(V + E)
   - Space Complexity: O(V)
   - Explores as far as possible before backtracking

### Shortest Path Algorithms

3. **Dijkstra's Algorithm** - `dijkstra.go`
   - Time Complexity: O((V + E) log V)
   - Space Complexity: O(V)
   - Single-source shortest path for non-negative weights

4. **Bellman-Ford Algorithm** - `bellman_ford.go`
   - Time Complexity: O(VE)
   - Space Complexity: O(V)
   - Handles negative edge weights

5. **Floyd-Warshall Algorithm** - `floyd_warshall.go`
   - Time Complexity: O(V³)
   - Space Complexity: O(V²)
   - All-pairs shortest path

6. **A* Search Algorithm** - `a_star.go`
   - Time Complexity: O(E)
   - Space Complexity: O(V)
   - Heuristic-based pathfinding

### Minimum Spanning Tree

7. **Kruskal's Algorithm** - `kruskal.go`
   - Time Complexity: O(E log E)
   - Space Complexity: O(V)
   - Uses edge sorting and union-find

8. **Prim's Algorithm** - `prim.go`
   - Time Complexity: O(E log V)
   - Space Complexity: O(V)
   - Grows MST from starting vertex

### Cycle Detection

9. **Cycle Detection (Directed)** - `cycle_detection_directed.go`
   - Time Complexity: O(V + E)
   - Space Complexity: O(V)
   - Uses DFS with colors

10. **Cycle Detection (Undirected)** - `cycle_detection_undirected.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - Uses DFS or union-find

### Topological Sorting

11. **Topological Sort (DFS)** - `topological_sort.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - For directed acyclic graphs

12. **Kahn's Algorithm** - `kahns_algorithm.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - BFS-based topological sort

### Other Graph Algorithms

13. **Strongly Connected Components (Kosaraju)** - `kosaraju_scc.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - Finds SCCs in directed graph

14. **Tarjan's SCC Algorithm** - `tarjan_scc.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - Single-pass SCC detection

15. **Articulation Points and Bridges** - `articulation_points.go`
    - Time Complexity: O(V + E)
    - Space Complexity: O(V)
    - Find cut vertices and edges

16. **Max Flow (Ford-Fulkerson)** - `ford_fulkerson.go`
    - Time Complexity: O(E × max_flow)
    - Space Complexity: O(V²)
    - Maximum flow in flow network

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
