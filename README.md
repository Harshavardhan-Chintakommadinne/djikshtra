# Dijkstra’s Algorithm in C++

##  Overview
This project implements **Dijkstra’s Algorithm** in C++ to find the shortest path between two nodes in a weighted graph.  
The program asks the user for a **starting node** and an **ending node** and outputs:
- The cost of the shortest path  
-  The path itself  

The graph is **hardcoded** for simplicity, but the algorithm works for any graph with **positive edge weights**.

---

##  Features
- Graph represented using an **adjacency list**  
- Efficient **priority queue (min-heap)** for performance  
- User input for **start** and **end** nodes  
- Path reconstruction using a parent map  

---

##  Example Graph
1 --(4)-- 2 --(10)-- 4 --(11)-- 6
| |
(2) (5)
| |
3 --(3)-- 5 --(4)--


---

## ▶ Example Run


Enter starting node: 1
Enter ending node: 6

Shortest path cost from 1 to 6: 20
Path: 1 -> 3 -> 5 -> 4 -> 6


---

##  How to Compile and Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/dijkstra-cpp.git
cd dijkstra-cpp

2. Compile the program
g++ dijkstra.cpp -o dijkstra

3. Run the executable
./dijkstra

