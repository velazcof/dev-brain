
### `Definition`

Linked Lists are **linked data structures** made of nodes where each node stores a value and a reference to the next (and sometimes previous) node. They allow efficient insertions and deletions but have slower indexing compared to arrays or vectors.

---
### `Key Ideas`

- Not stored in contiguous memory — built from linked nodes.
    
- No random access; must traverse from the head to reach an index.
    
- Insertions and deletions are fast when nodes are known.
    
- Ideal for workloads with frequent mid-structure modifications.

---
### `Big-O Performance`

| Operation                     | Time Complexity                                   | Notes                                 |
| ----------------------------- | ------------------------------------------------- | ------------------------------------- |
| **Access (at index)**         | **O(n)**                                          | Must traverse from the head           |
| **Update (at index)**         | **O(n)**                                          | Same as access                        |
| **Append**                    | **O(1)** _if tail reference_ / **O(n)** otherwise | O(1) when list tracks the last node   |
| **Insert (at random index)**  | **O(n)**                                          | Need to traverse to that index first  |
| **Insert (after known node)** | **O(1)**                                          | Direct pointer reassignment           |
| **Delete (at random index)**  | **O(n)**                                          | Must find the node before it          |
| **Delete (known node)**       | **O(1)**                                          | Pointer reassignment                  |
| **Search (unsorted)**         | **O(n)**                                          | Must check nodes sequentially         |
| **Search (sorted)**           | **O(n)**                                          | No indexing; binary search impossible |
| **Space Complexity**          | **O(n)**                                          | Extra memory needed for node pointers |

---
### `Connected Notes`

- [[Data Structures]]