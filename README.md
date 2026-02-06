# Full of exercise I made to solve in MaxFLow/MinCut

# Max Flow — Network Flow Algorithm

**Max Flow** is a graph algorithm used to find the **maximum amount of flow**
that can be sent from a **source node** to a **sink node** in a network,
without exceeding the capacities of the edges.

The graph is **directed**, and each edge has a **capacity**.

---

## Core Idea

- Flow starts at the **source**
- Flow ends at the **sink**
- Each edge has a maximum capacity
- The total flow must respect:
  - Capacity constraints
  - Flow conservation at intermediate nodes

---

## Common Algorithms

- **Ford–Fulkerson**
- **Edmonds–Karp** (BFS-based, guaranteed polynomial time)
- **Dinic’s Algorithm** (fast, commonly used in contests)

---

## Typical Applications

- **Minimum Cut** problems
- **Bipartite Matching**
- Network reliability
- Transportation and logistics
- Scheduling and assignment problems

---

## Key Properties

- All flows are non-negative
- Flow into a node = flow out (except source & sink)
- **Max Flow = Min Cut** (Max-Flow Min-Cut Theorem)

---

## Time Complexity (overview)

- Ford–Fulkerson: depends on implementation
- Edmonds–Karp: `O(V · E²)`
- Dinic: `O(E √V)` or better in practice
