# DSA Patterns (Java)

A structured repository of Data Structures and Algorithms patterns implemented in Java. Designed as both a comprehensive reference guide for interview preparation and a hands-on practice ground.

---

## 🎯 Purpose

- **Pattern-Oriented Learning**: Focus on reusable algorithmic paradigms and core templates rather than isolated problem solutions.
- **Clean Java Implementations**: Idiomatic Java 21+ code with thorough explanations, complexity analysis, and edge cases.
- **Reference & Practice Ground**: Quick review cheatsheets alongside ready-to-test code.

---

## 📂 Repository Structure

```text
dsa-patterns/
├── pom.xml
├── README.md
├── src/
│   ├── main/java/com/joseph/dsa/
│   │   └── graphs/
│   │       ├── representations/
│   │       │   ├── AdjacencyList.java       # Directed/undirected, weighted/unweighted representations
│   │       │   └── AdjacencyMatrix.java     # V x V matrix representation for dense graphs
│   │       ├── traversals/
│   │       │   ├── BfsLevelOrder.java       # Shortest path in unweighted graphs, level-by-level
│   │       │   ├── DfsRecursive.java        # Connectivity, paths, cycle detection
│   │       │   └── DfsIterative.java        # Explicit stack implementation
│   │       ├── topologicalsort/
│   │       │   ├── KahnsBfs.java            # In-degree queue + cycle detection
│   │       │   └── DfsPostOrder.java        # Tri-color / recursion stack approach
│   │       ├── cycle_detection/             # (Planned) Directed tri-color, undirected DSU
│   │       ├── shortest_paths/              # (Planned) Dijkstra, Bellman-Ford, Floyd-Warshall
│   │       ├── disjoint_set/                # (Planned) Union-Find with rank & path compression
│   │       └── advanced/                    # (Planned) Tarjan's SCC, Kosaraju's SCC, Bipartite coloring
│   └── test/java/com/joseph/dsa/
│       └── graphs/                          # Unit tests verifying implementations
```

---

## 🗺️ Roadmap & Patterns

### 1. Graphs
- [x] **Representations**: Adjacency List, Adjacency Matrix
- [x] **Traversals**: BFS (Level Order), DFS (Recursive & Iterative)
- [x] **Topological Sort**: Kahn's BFS Algorithm, DFS Post-Order
- [ ] **Cycle Detection**: Directed graph (3-color DFS), Undirected graph (Union-Find / BFS / DFS)
- [ ] **Shortest Paths**: Dijkstra (Min-Heap), Bellman-Ford, Floyd-Warshall
- [ ] **Disjoint Set Union (DSU)**: Path compression & Union by Rank/Size
- [ ] **Advanced Patterns**: Strongly Connected Components (Tarjan & Kosaraju), Bipartite graph 2-coloring

*(Additional pattern categories like Dynamic Programming, Trees, Heaps, and Two Pointers will be introduced as the repository evolves.)*

---

## 🛠️ Tech Stack & Requirements

- **Language**: Java 21+
- **Build Tool**: Maven (`pom.xml`)
- **Testing**: JUnit 5 (to be configured)
