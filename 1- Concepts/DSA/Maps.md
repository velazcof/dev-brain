
### `Definition`

Maps are **key–value data structures** that associate **unique keys** with corresponding values, enabling fast lookup, insertion, and deletion based on the key rather than position.

They model direct access by identity instead of sequence.

---
### `Key Ideas`

- Each **key is unique** and maps to exactly one value.
    
- Access is based on keys, not indexes.
    
- Order is not semantically important (unless using ordered variants).
    
- Common implementations include:
    
    - **Hash-based maps** (hash maps / hash tables)
    - **Tree-based maps** (ordered maps)
    
- Widely used for indexing, caching, configuration, and lookups.

---
### `Big-O Performance`

|Operation|Time Complexity|Notes|
|---|---|---|
|**Insert (by key)**|**O(1)** average / **O(log n)**|Hash map vs tree map|
|**Delete (by key)**|**O(1)** average / **O(log n)**|Depends on implementation|
|**Lookup (by key)**|**O(1)** average / **O(log n)**|Primary use case|
|**Update (by key)**|**O(1)** average / **O(log n)**|Same as lookup|
|**Traversal**|**O(n)**|Must visit all key–value pairs|
|**Space Complexity**|**O(n)**|Stores n key–value pairs|

---
### `Connected Notes`

- [[Data Structures]]