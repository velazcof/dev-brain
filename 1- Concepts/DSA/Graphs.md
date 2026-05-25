
### `Definition`

Graphs are **non-linear data structures** composed of **nodes (vertices)** connected by **edges**, used to represent relationships between entities. They can model complex networks where elements are interconnected in arbitrary ways.

---
### `Key Ideas`

- Consist of **vertices** and **edges**.
    
- Edges may be **directed** or **undirected**.
    
- Can be **weighted** or **unweighted**.
    
- May contain **cycles** or be **acyclic**.
    
- Common representations:
    
    - **Adjacency List**
    - **Adjacency Matrix**
    
- Traversal typically uses **BFS** or **DFS**.

---
### `Big-O Performance`

| Operation                 | Time Complexity          | Notes                         |
| ------------------------- | ------------------------ | ----------------------------- |
| **Add Vertex**            | **O(1)**                 | Depends on representation     |
| **Add Edge**              | **O(1)**                 | Constant for adjacency list   |
| **Remove Vertex**         | **O(V + E)**             | Must remove connected edges   |
| **Remove Edge**           | **O(E)** / **O(1)**      | O(1) with adjacency matrix    |
| **Check Adjacency**       | **O(1)** / **O(V)**      | O(1) matrix, O(V) list        |
| **Traversal (BFS / DFS)** | **O(V + E)**             | Visits all vertices and edges |
| **Search**                | **O(V + E)**             | No guaranteed ordering        |
| **Space Complexity**      | **O(V + E)** / **O(V²)** | List vs matrix                |

---
### `Connected Notes`

- [[Data Structures]]