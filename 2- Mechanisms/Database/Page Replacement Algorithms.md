
**Page Replacement Algorithms** are mechanisms that determine which database pages should be evicted from the buffer pool when memory space is needed. They help manage limited memory efficiently while minimizing performance degradation.

---
### `How It Works`

- **Eviction Decision Logic**  
    When the buffer pool is full, the algorithm selects a page to remove.

- **Access Pattern Tracking**  
    Tracks usage patterns such as recency or frequency of page access.

- **Policy Application**  
    Applies strategies (e.g., least recently used, clock-based approaches) to approximate optimal retention.

- **Dirty Page Coordination**  
    Ensures modified pages are written to disk before eviction if necessary.

- **Performance Trade-offs**  
    Balances memory utilization, I/O cost, and system throughput.

---
### `Why It Exists`

- To prevent uncontrolled memory growth
- To retain frequently accessed pages in memory
- To reduce disk I/O overhead
- To maintain stable system performance under load

---
### `Connected Notes`

- [[Buffer Management]]