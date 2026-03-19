AI-assignment-3
A collection of AI search algorithms for optimal pathfinding, featuring Dijkstra’s algorithm and A*-based UGV navigation with obstacle handling.

1. Dijkstra / Uniform Cost Search
- Computes shortest paths from a source node to all other nodes
- Applied to a graph of Indian cities with road distances
- Uses a priority queue (min-heap) for efficiency

---

2. UGV Navigation (Static Obstacles)
- Implements **A\*** Search Algorithm
- Finds optimal path on a grid-based map (simulated battlefield)
- Handles obstacles with configurable density levels

---

 3️. UGV Navigation (Dynamic Obstacles)
- Simulates real-world environments with changing obstacles
- Uses **replanning strategy** (inspired by D* Lite)
- Recomputes path dynamically when obstacles appear

---

Measures of Effectiveness
- Path Length (Optimality)
- Computation Time
- Nodes Expanded (Efficiency)

---
Requirements:
Python 3.x, 
 No external libraries required

How to Run:
python filename.py
