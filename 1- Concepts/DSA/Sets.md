
### `Definition`

Sets are **abstract data structures** that store **unique elements** without guaranteed ordering. They model membership rather than position, focusing on whether an element exists rather than where it is located.

---
### `Key Ideas`

- Each element appears **at most once**.
    
- Order is not semantically meaningful.
    
- Core operations revolve around **membership** and **uniqueness**.
    
- Common implementations include **hash-based sets** and **tree-based sets**.
    
- Frequently used to eliminate duplicates and perform membership checks.

---
### `Big-O Performance`

|Operation|Time Complexity|Notes|
|---|---|---|
|**Insert**|**O(1)** average / **O(log n)**|Hash set vs tree set|
|**Delete**|**O(1)** average / **O(log n)**|Depends on implementation|
|**Search / Contains**|**O(1)** average / **O(log n)**|Fast membership checks|
|**Traversal**|**O(n)**|Must visit all elements|
|**Union / Intersection**|**O(n + m)**|Depends on set sizes|
|**Space Complexity**|**O(n)**|Stores n unique elements|

---
### `Connected Notes`

- [[Data Structures]]