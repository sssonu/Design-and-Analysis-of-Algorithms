#### Design-and-Analysis-of-Algorithms
Here is the time and space complexity analysis for the algorithms listed in the table:

---

### 1. **Linear Search and Binary Search**
- **Linear Search**:
  - **Time Complexity**: \(O(n)\)
  - **Space Complexity**: \(O(1)\)
- **Binary Search (Recursive)**:
  - **Time Complexity**: \(O(\log n)\)
  - **Space Complexity**: \(O(\log n)\) (due to recursion stack)

---

### 2. **Quick Sort**
- **Time Complexity**:
  - Best Case: \(O(n \log n)\)
  - Average Case: \(O(n \log n)\)
  - Worst Case: \(O(n^2)\) (when the pivot is poorly chosen)
- **Space Complexity**: 
  - In-place: \(O(\log n)\) (recursion stack)
  - Non-in-place: \(O(n)\) (if additional storage is used for sub-arrays)

---

### 3. **Merge Sort**
- **Time Complexity**:
  - Best, Average, and Worst Case: \(O(n \log n)\)
- **Space Complexity**:
  - \(O(n)\) (due to temporary arrays used during merging)

---

### 4. **Prim's and Kruskal's Algorithm**
- **Prim’s Algorithm**:
  - **Time Complexity**:
    - Using an adjacency matrix: \(O(V^2)\)
    - Using a priority queue with adjacency list: \(O(E \log V)\)
  - **Space Complexity**: \(O(V^2)\) or \(O(E + V)\) depending on the graph representation
- **Kruskal’s Algorithm**:
  - **Time Complexity**: \(O(E \log E)\) (sorting edges dominates)
  - **Space Complexity**: \(O(V + E)\) (for disjoint sets)

---

### 5. **Dijkstra’s Algorithm**
- **Time Complexity**:
  - Using an adjacency matrix: \(O(V^2)\)
  - Using a priority queue with adjacency list: \(O(E + V \log V)\)
- **Space Complexity**: \(O(V^2)\) or \(O(E + V)\) depending on the graph representation

---

### 6. **Knapsack Problem (Greedy Strategy)**
- **Time Complexity**: \(O(n \log n)\) (for sorting items by value/weight ratio)
- **Space Complexity**: \(O(1)\) (if sorting is done in-place)

---

### 7. **Knapsack Problem (Dynamic Programming)**
- **Time Complexity**: \(O(n \cdot W)\), where \(W\) is the capacity of the knapsack
- **Space Complexity**:
  - Standard DP table: \(O(n \cdot W)\)
  - Optimized for space: \(O(W)\) (using a single-dimensional DP array)

---

### 8. **Floyd’s Algorithm**
- **Time Complexity**: \(O(V^3)\) (triple nested loops for \(V\) vertices)
- **Space Complexity**: \(O(V^2)\) (distance matrix)

---

### 9. **Optimal Merge Pattern**
- **Time Complexity**: \(O(n \log n)\) (using a min-heap or sorting)
- **Space Complexity**: \(O(n)\) (for storing the heap)

---

### 10. **N-Queens Problem**
- **Time Complexity**:
  - \(O(n!)\) (for solving all configurations)
  - Optimized backtracking: \(O(n^n)\)
- **Space Complexity**: \(O(n)\) (recursion stack for backtracking)

- ![image](https://github.com/user-attachments/assets/dcd816a4-54d2-4900-9875-72cce5c05861)


