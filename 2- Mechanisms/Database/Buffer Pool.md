
**Buffer Pool** is the in-memory area managed by the database system where database pages are cached for active use. It serves as the primary working memory for data access and modification.

---
### `How It Works`

- **Page Caching**  
    When data is requested, the corresponding page is loaded from disk into the buffer pool.

- **In-Memory Access**  
    Queries operate on pages in memory rather than directly on disk.

- **Dirty Page Handling**  
    Pages modified in memory are marked as dirty and later written back to disk.

- **Eviction Control**  
    When memory is full, pages are evicted according to configured replacement strategies.

- **Shared Resource**  
    Multiple concurrent queries and transactions access the buffer pool simultaneously.

---
### `Why It Exists`

- To minimize direct disk access
- To improve query and transaction performance
- To provide a controlled memory layer between execution and storage
- To enable efficient coordination of read and write operations

---
### `Connected Notes`

- [[Buffer Management]]