
### `Definition`

Trees are **hierarchical, non-linear data structures** composed of nodes connected by edges, where each node has a single parent (except the root) and zero or more children. They are used to represent structured relationships and ordered hierarchies.

---
### `Key Ideas`

- Organized around a **root node**.
    
- Each node can have multiple **child nodes**.
    
- No cycles; exactly one path exists between the root and any node.
    
- Can be **balanced** or **unbalanced**, affecting performance.
    
- Common variants include:
    
    - Binary trees
    - Binary search trees (BST)
    - Heaps
    - Tries
    
- Traversal methods include **preorder**, **inorder**, and **postorder**.

---
### `Big-O Performance`

|Operation|Time Complexity|Notes|
|---|---|---|
|**Search**|**O(log n)** average / **O(n)**|Balanced vs unbalanced|
|**Insert**|**O(log n)** average / **O(n)**|Depends on tree height|
|**Delete**|**O(log n)** average / **O(n)**|Rebalancing may be required|
|**Traversal**|**O(n)**|Visits all nodes|
|**Access (by index)**|**O(n)**|No random access|
|**Space Complexity**|**O(n)**|Stores n nodes|

---
### `Connected Notes`

- [[Data Structures]]