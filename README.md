# Algorithms-Golang 🚀

[![Go Report Card](https://goreportcard.com/badge/github.com/ivikasavnish/algorithms-golang)](https://goreportcard.com/report/github.com/ivikasavnish/algorithms-golang)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![GoDoc](https://godoc.org/github.com/ivikasavnish/algorithms-golang?status.svg)](https://godoc.org/github.com/ivikasavnish/algorithms-golang)

A comprehensive collection of algorithms and data structures implemented in Go (Golang). This package aims to be the most complete and production-ready algorithms library, covering Data Structures & Algorithms (DSA), Machine Learning, and Database-related algorithms.

## 📋 Table of Contents

- [Features](#-features)
- [Installation](#-installation)
- [Data Structures](#-data-structures)
- [Sorting Algorithms](#-sorting-algorithms)
- [Searching Algorithms](#-searching-algorithms)
- [Graph Algorithms](#-graph-algorithms)
- [Tree Algorithms](#-tree-algorithms)
- [Dynamic Programming](#-dynamic-programming)
- [String Algorithms](#-string-algorithms)
- [Mathematical Algorithms](#-mathematical-algorithms)
- [Bit Manipulation](#-bit-manipulation)
- [Backtracking Algorithms](#-backtracking-algorithms)
- [Greedy Algorithms](#-greedy-algorithms)
- [Divide and Conquer](#-divide-and-conquer)
- [Machine Learning Algorithms](#-machine-learning-algorithms)
- [Database Algorithms](#-database-algorithms)
- [Usage Examples](#-usage-examples)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- **Production-Ready**: Well-tested, efficient implementations
- **Comprehensive Coverage**: DSA, ML, and Database algorithms
- **Clean Code**: Idiomatic Go with clear documentation
- **Performance Optimized**: Benchmarked and optimized implementations
- **Easy to Use**: Simple API with extensive examples
- **Type Safe**: Leverages Go generics where applicable
- **Well Documented**: Each algorithm includes complexity analysis and usage examples

## 📦 Installation

```bash
go get github.com/ivikasavnish/algorithms-golang
```

## 📊 Data Structures

### Linear Data Structures
- **Array**
  - Dynamic Array
  - Circular Array
- **Linked List**
  - Singly Linked List
  - Doubly Linked List
  - Circular Linked List
  - Skip List
- **Stack**
  - Array-based Stack
  - Linked List Stack
  - Min Stack
- **Queue**
  - Array-based Queue
  - Linked List Queue
  - Circular Queue
  - Priority Queue
  - Deque (Double-ended Queue)

### Non-Linear Data Structures
- **Tree**
  - Binary Tree
  - Binary Search Tree (BST)
  - AVL Tree
  - Red-Black Tree
  - B-Tree
  - B+ Tree
  - Segment Tree
  - Fenwick Tree (Binary Indexed Tree)
  - Trie (Prefix Tree)
  - Suffix Tree
  - Radix Tree
- **Heap**
  - Min Heap
  - Max Heap
  - Binomial Heap
  - Fibonacci Heap
- **Graph**
  - Adjacency Matrix
  - Adjacency List
  - Edge List
  - Directed Graph
  - Undirected Graph
  - Weighted Graph

### Hash-Based Structures
- **Hash Table**
  - Chaining
  - Open Addressing
  - Linear Probing
  - Quadratic Probing
  - Double Hashing
- **Hash Set**
- **Hash Map**
- **Bloom Filter**
- **Consistent Hashing**

### Advanced Structures
- **Disjoint Set (Union-Find)**
- **LRU Cache**
- **LFU Cache**
- **Suffix Array**
- **Sparse Table**

## 🔄 Sorting Algorithms

### Comparison-Based Sorts
- **Bubble Sort** - O(n²) time, O(1) space
- **Selection Sort** - O(n²) time, O(1) space
- **Insertion Sort** - O(n²) time, O(1) space
- **Merge Sort** - O(n log n) time, O(n) space
- **Quick Sort** - O(n log n) average time, O(log n) space
- **Heap Sort** - O(n log n) time, O(1) space
- **Shell Sort** - O(n log n) to O(n²) time, O(1) space
- **Tree Sort** - O(n log n) time, O(n) space
- **Cocktail Sort** - O(n²) time, O(1) space
- **Comb Sort** - O(n²/2^p) time, O(1) space
- **Gnome Sort** - O(n²) time, O(1) space
- **Tim Sort** - O(n log n) time, O(n) space

### Non-Comparison Sorts
- **Counting Sort** - O(n + k) time, O(k) space
- **Radix Sort** - O(d × (n + k)) time, O(n + k) space
- **Bucket Sort** - O(n + k) time, O(n + k) space

### Other Sorting
- **Topological Sort** - For DAGs
- **External Sorting** - For large datasets that don't fit in memory

## 🔍 Searching Algorithms

### Linear Search Variants
- **Linear Search** - O(n) time
- **Sentinel Linear Search** - O(n) time
- **Jump Search** - O(√n) time

### Binary Search Variants
- **Binary Search** - O(log n) time
- **Exponential Search** - O(log n) time
- **Interpolation Search** - O(log log n) average time
- **Fibonacci Search** - O(log n) time
- **Ternary Search** - O(log₃ n) time

### Advanced Searching
- **Depth-First Search (DFS)** - Graph traversal
- **Breadth-First Search (BFS)** - Graph traversal
- **Bidirectional Search** - Graph searching
- **A* Search Algorithm** - Pathfinding
- **Best-First Search** - Informed search

## 📈 Graph Algorithms

### Shortest Path
- **Dijkstra's Algorithm** - Single source shortest path
- **Bellman-Ford Algorithm** - With negative weights
- **Floyd-Warshall Algorithm** - All pairs shortest paths
- **Johnson's Algorithm** - All pairs with negative weights
- **A* Algorithm** - Heuristic pathfinding

### Minimum Spanning Tree
- **Kruskal's Algorithm** - Edge-based MST
- **Prim's Algorithm** - Vertex-based MST
- **Boruvka's Algorithm** - Parallel MST

### Graph Traversal
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**
- **Iterative Deepening DFS**

### Cycle Detection
- **Cycle Detection in Directed Graph**
- **Cycle Detection in Undirected Graph**
- **Detect Negative Cycle**

### Connectivity
- **Connected Components**
- **Strongly Connected Components (Kosaraju's, Tarjan's)**
- **Bridges and Articulation Points**
- **Biconnected Components**

### Network Flow
- **Ford-Fulkerson Algorithm**
- **Edmonds-Karp Algorithm**
- **Dinic's Algorithm**
- **Push-Relabel Algorithm**
- **Min-Cut Max-Flow Theorem**

### Matching
- **Bipartite Matching**
- **Hungarian Algorithm** - Assignment problem
- **Hopcroft-Karp Algorithm**

### Other Graph Algorithms
- **Topological Sort**
- **Eulerian Path and Circuit**
- **Hamiltonian Path and Cycle**
- **Graph Coloring**
- **Traveling Salesman Problem (TSP)**

## 🌳 Tree Algorithms

### Tree Traversal
- **In-order Traversal**
- **Pre-order Traversal**
- **Post-order Traversal**
- **Level-order Traversal (BFS)**
- **Morris Traversal**

### Binary Search Tree Operations
- **Search**
- **Insert**
- **Delete**
- **Find Min/Max**
- **Successor/Predecessor**

### Tree Properties
- **Height/Depth Calculation**
- **Diameter of Tree**
- **Lowest Common Ancestor (LCA)**
- **Check if Balanced**
- **Check if BST**

### Advanced Tree Algorithms
- **AVL Tree Rotations**
- **Red-Black Tree Operations**
- **B-Tree Operations**
- **Segment Tree (Range Queries)**
- **Fenwick Tree (Binary Indexed Tree)**
- **Trie Operations** - Insert, Search, Delete
- **Suffix Tree Construction**

## 💡 Dynamic Programming

### Classic DP Problems
- **Fibonacci Sequence**
- **Climbing Stairs**
- **Coin Change Problem**
- **Knapsack Problem (0/1, Unbounded, Fractional)**
- **Longest Common Subsequence (LCS)**
- **Longest Increasing Subsequence (LIS)**
- **Edit Distance (Levenshtein Distance)**
- **Matrix Chain Multiplication**
- **Rod Cutting Problem**
- **Egg Drop Problem**

### Advanced DP
- **Longest Common Substring**
- **Longest Palindromic Subsequence**
- **Palindrome Partitioning**
- **Word Break Problem**
- **Optimal Binary Search Tree**
- **Travelling Salesman Problem (DP)**
- **Subset Sum Problem**
- **Partition Problem**
- **Maximum Subarray Sum (Kadane's Algorithm)**
- **Buy and Sell Stock Problems**
- **House Robber Problems**
- **Unique Paths**
- **Minimum Path Sum**
- **Regular Expression Matching**
- **Wildcard Matching**

## 🔤 String Algorithms

### Pattern Matching
- **Naive Pattern Matching** - O(n×m)
- **KMP Algorithm** - O(n + m)
- **Boyer-Moore Algorithm** - O(n/m) to O(n×m)
- **Rabin-Karp Algorithm** - O(n + m) average
- **Z Algorithm** - O(n + m)
- **Aho-Corasick Algorithm** - Multiple pattern matching

### String Manipulation
- **String Reversal**
- **Palindrome Check**
- **Anagram Detection**
- **String Compression**
- **Run-Length Encoding**

### Advanced String Algorithms
- **Longest Common Prefix**
- **Longest Repeating Substring**
- **Suffix Array Construction**
- **Manacher's Algorithm** - Longest palindromic substring
- **String Hashing**
- **Trie-based Operations**

## 🔢 Mathematical Algorithms

### Number Theory
- **GCD (Euclidean Algorithm)**
- **LCM**
- **Prime Number Generation (Sieve of Eratosthenes)**
- **Segmented Sieve**
- **Prime Factorization**
- **Modular Arithmetic**
- **Modular Exponentiation**
- **Extended Euclidean Algorithm**
- **Chinese Remainder Theorem**

### Combinatorics
- **Permutations**
- **Combinations**
- **Catalan Numbers**
- **Pascal's Triangle**
- **Binomial Coefficient**

### Matrix Operations
- **Matrix Multiplication**
- **Matrix Transpose**
- **Matrix Determinant**
- **Matrix Inverse**
- **Strassen's Algorithm**

### Numerical Methods
- **Newton-Raphson Method**
- **Binary Exponentiation**
- **Fast Fourier Transform (FFT)**
- **Number Theoretic Transform (NTT)**

### Geometry
- **Convex Hull (Graham Scan, Jarvis March)**
- **Line Intersection**
- **Point in Polygon**
- **Closest Pair of Points**

## 🔧 Bit Manipulation

- **Set, Clear, Toggle Bit**
- **Check if Power of Two**
- **Count Set Bits (Brian Kernighan's Algorithm)**
- **Find Single Number**
- **Subset Generation using Bits**
- **Bit Masking**
- **XOR Properties**
- **Gray Code**

## ⚡ Backtracking Algorithms

- **N-Queens Problem**
- **Sudoku Solver**
- **Rat in a Maze**
- **Knight's Tour**
- **Subset Sum**
- **Permutations and Combinations**
- **Graph Coloring**
- **Hamiltonian Path**

## 💰 Greedy Algorithms

- **Activity Selection Problem**
- **Huffman Encoding**
- **Job Sequencing Problem**
- **Fractional Knapsack**
- **Minimum Coins**
- **Prim's MST**
- **Kruskal's MST**
- **Dijkstra's Algorithm**

## ➗ Divide and Conquer

- **Merge Sort**
- **Quick Sort**
- **Binary Search**
- **Closest Pair of Points**
- **Strassen's Matrix Multiplication**
- **Karatsuba Algorithm** - Fast multiplication

## 🤖 Machine Learning Algorithms

### Supervised Learning

#### Regression
- **Linear Regression**
  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Regression
  - Ridge Regression (L2 Regularization)
  - Lasso Regression (L1 Regularization)
  - Elastic Net Regression
- **Support Vector Regression (SVR)**
- **Decision Tree Regression**
- **Random Forest Regression**
- **Gradient Boosting Regression**

#### Classification
- **Logistic Regression**
  - Binary Classification
  - Multiclass Classification
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes Classifier**
  - Gaussian Naive Bayes
  - Multinomial Naive Bayes
  - Bernoulli Naive Bayes
- **Support Vector Machines (SVM)**
  - Linear SVM
  - Kernel SVM (RBF, Polynomial)
- **Decision Trees**
  - ID3 Algorithm
  - C4.5 Algorithm
  - CART (Classification and Regression Trees)
- **Random Forest**
- **Gradient Boosting**
  - XGBoost
  - AdaBoost
  - LightGBM
- **Neural Networks**
  - Perceptron
  - Multi-layer Perceptron (MLP)

### Unsupervised Learning

#### Clustering
- **K-Means Clustering**
- **K-Medoids (PAM)**
- **Hierarchical Clustering**
  - Agglomerative
  - Divisive
- **DBSCAN (Density-Based Clustering)**
- **Mean Shift Clustering**
- **Gaussian Mixture Models (GMM)**
- **Spectral Clustering**

#### Dimensionality Reduction
- **Principal Component Analysis (PCA)**
- **Linear Discriminant Analysis (LDA)**
- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**
- **Autoencoders**
- **Singular Value Decomposition (SVD)**

#### Association Rule Learning
- **Apriori Algorithm**
- **Eclat Algorithm**
- **FP-Growth Algorithm**

### Reinforcement Learning
- **Q-Learning**
- **SARSA**
- **Deep Q-Network (DQN)**
- **Policy Gradient Methods**

### Neural Networks & Deep Learning
- **Activation Functions**
  - Sigmoid, Tanh, ReLU, Leaky ReLU, Softmax
- **Backpropagation**
- **Gradient Descent Variants**
  - Batch Gradient Descent
  - Stochastic Gradient Descent (SGD)
  - Mini-batch Gradient Descent
  - Adam Optimizer
  - RMSprop
  - Adagrad
- **Convolutional Neural Networks (CNN)**
- **Recurrent Neural Networks (RNN)**
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**

### Optimization Algorithms
- **Gradient Descent**
- **Stochastic Gradient Descent**
- **Adam Optimization**
- **RMSprop**
- **Genetic Algorithms**
- **Particle Swarm Optimization**
- **Simulated Annealing**

### Ensemble Methods
- **Bagging**
- **Boosting**
- **Stacking**
- **Voting Classifier**

### Model Evaluation
- **Cross-Validation**
  - K-Fold Cross-Validation
  - Stratified K-Fold
  - Leave-One-Out
- **Performance Metrics**
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1-Score
  - ROC Curve and AUC
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score

## 🗄️ Database Algorithms

### Indexing Algorithms
- **B-Tree Index** - Balanced tree for range queries
- **B+ Tree Index** - Optimized for disk-based storage
- **Hash Index** - Fast equality lookups
- **Bitmap Index** - Efficient for low-cardinality columns
- **R-Tree Index** - Spatial data indexing
- **GiST (Generalized Search Tree)**
- **GIN (Generalized Inverted Index)**
- **Full-Text Search Index** - Inverted index for text search

### Query Optimization
- **Query Parser**
- **Query Planner**
- **Cost-Based Optimization**
- **Rule-Based Optimization**
- **Join Algorithms**
  - Nested Loop Join
  - Hash Join
  - Merge Join (Sort-Merge Join)
  - Index Nested Loop Join
- **Query Execution Plans**

### Storage and Retrieval
- **Buffer Pool Management**
  - LRU (Least Recently Used)
  - Clock Algorithm
  - 2Q Algorithm
- **Page Replacement Algorithms**
- **LSM Tree (Log-Structured Merge Tree)**
  - Write-optimized storage
  - Compaction strategies
- **WAL (Write-Ahead Logging)**
- **MVCC (Multi-Version Concurrency Control)**

### Transaction Management
- **ACID Properties Implementation**
- **Two-Phase Locking (2PL)**
  - Strict 2PL
  - Rigorous 2PL
- **Timestamp Ordering**
- **Optimistic Concurrency Control**
- **Deadlock Detection**
  - Wait-for Graph
  - Timeout-based
- **Deadlock Prevention**

### Recovery Algorithms
- **ARIES Algorithm** - Algorithm for Recovery and Isolation Exploiting Semantics
- **Checkpoint Mechanisms**
- **Redo/Undo Logging**
- **Shadow Paging**

### Distributed Database Algorithms
- **Consistent Hashing** - Data distribution
- **Sharding Strategies**
  - Range-based Sharding
  - Hash-based Sharding
  - Directory-based Sharding
- **Replication Algorithms**
  - Master-Slave Replication
  - Multi-Master Replication
  - Chain Replication
- **Consensus Algorithms**
  - Paxos
  - Raft
  - Two-Phase Commit (2PC)
  - Three-Phase Commit (3PC)
- **Vector Clocks** - Distributed versioning
- **Merkle Trees** - Data synchronization

### Caching Strategies
- **Cache Replacement Policies**
  - LRU (Least Recently Used)
  - LFU (Least Frequently Used)
  - FIFO (First In First Out)
  - ARC (Adaptive Replacement Cache)
- **Write Policies**
  - Write-Through
  - Write-Back
  - Write-Around

### Compression Algorithms
- **Dictionary Encoding**
- **Run-Length Encoding (RLE)**
- **Delta Encoding**
- **Bit-Packing**
- **Columnar Compression**

### Data Structures for Databases
- **Bloom Filters** - Probabilistic membership testing
- **Skip Lists** - Alternative to balanced trees
- **Count-Min Sketch** - Frequency estimation
- **HyperLogLog** - Cardinality estimation
- **Roaring Bitmaps** - Compressed bitmap index

### Query Processing
- **External Sorting**
  - Multi-way Merge Sort
  - Replacement Selection
- **External Hashing**
- **Bitmap Operations** - Fast set operations
- **Column-Oriented Storage**

## 📖 Usage Examples

### Example 1: Binary Search
```go
package main

import (
    "fmt"
    "github.com/ivikasavnish/algorithms-golang/searching"
)

func main() {
    arr := []int{1, 3, 5, 7, 9, 11, 13, 15}
    target := 7
    
    result := searching.BinarySearch(arr, target)
    if result != -1 {
        fmt.Printf("Element found at index: %d\n", result)
    } else {
        fmt.Println("Element not found")
    }
}
```

### Example 2: Quick Sort
```go
package main

import (
    "fmt"
    "github.com/ivikasavnish/algorithms-golang/sorting"
)

func main() {
    arr := []int{64, 34, 25, 12, 22, 11, 90}
    
    sorting.QuickSort(arr)
    fmt.Println("Sorted array:", arr)
}
```

### Example 3: Dijkstra's Algorithm
```go
package main

import (
    "fmt"
    "github.com/ivikasavnish/algorithms-golang/graph"
)

func main() {
    g := graph.NewGraph(5)
    g.AddEdge(0, 1, 4)
    g.AddEdge(0, 2, 1)
    g.AddEdge(2, 1, 2)
    g.AddEdge(1, 3, 1)
    g.AddEdge(2, 3, 5)
    g.AddEdge(3, 4, 3)
    
    distances := g.Dijkstra(0)
    fmt.Println("Shortest distances from source:", distances)
}
```

### Example 4: K-Means Clustering
```go
package main

import (
    "fmt"
    "github.com/ivikasavnish/algorithms-golang/ml"
)

func main() {
    data := [][]float64{
        {1.0, 2.0},
        {1.5, 1.8},
        {5.0, 8.0},
        {8.0, 8.0},
        {1.0, 0.6},
        {9.0, 11.0},
    }
    
    kmeans := ml.NewKMeans(2, 100)
    clusters := kmeans.Fit(data)
    fmt.Println("Cluster assignments:", clusters)
}
```

### Example 5: B+ Tree Index
```go
package main

import (
    "fmt"
    "github.com/ivikasavnish/algorithms-golang/database"
)

func main() {
    tree := database.NewBPlusTree(3)
    
    tree.Insert(10, "value1")
    tree.Insert(20, "value2")
    tree.Insert(30, "value3")
    
    value, found := tree.Search(20)
    if found {
        fmt.Println("Found:", value)
    }
}
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Write clean, idiomatic Go code
- Include unit tests for all new algorithms
- Add benchmarks for performance-critical code
- Update documentation and examples
- Follow Go best practices and conventions
- Include complexity analysis in comments

## 📝 Documentation

Each algorithm includes:
- Clear code comments
- Time and space complexity analysis
- Usage examples
- Edge case handling
- Performance benchmarks

## 🧪 Testing

Run all tests:
```bash
go test ./...
```

Run tests with coverage:
```bash
go test -cover ./...
```

Run benchmarks:
```bash
go test -bench=. ./...
```

## 📊 Performance

All algorithms are benchmarked and optimized for production use. Check the `/benchmarks` directory for detailed performance analysis.

## 🗺️ Roadmap

- [ ] Complete implementation of all listed algorithms
- [ ] Add comprehensive test coverage (target: 90%+)
- [ ] Add benchmarks for all algorithms
- [ ] Create interactive documentation website
- [ ] Add more machine learning algorithms
- [ ] Implement distributed algorithms
- [ ] Add visualization tools
- [ ] Create CLI tool for algorithm demos

## 📚 Resources

- [Go Documentation](https://golang.org/doc/)
- [Algorithm Design Manual](https://www.algorist.com/)
- [Introduction to Algorithms (CLRS)](https://mitpress.mit.edu/books/introduction-algorithms)
- [Machine Learning (Andrew Ng)](https://www.coursera.org/learn/machine-learning)

## 🙏 Acknowledgments

This project is inspired by various algorithm implementations and educational resources from the programming community.

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- GitHub: [@ivikasavnish](https://github.com/ivikasavnish)
- Project Link: [https://github.com/ivikasavnish/algorithms-golang](https://github.com/ivikasavnish/algorithms-golang)

---

**Made with ❤️ for the Go community**

⭐ Star this repository if you find it helpful!
