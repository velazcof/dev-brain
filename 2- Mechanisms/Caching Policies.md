
### `Definition`

**Caching Policies** are mechanisms that define how pages are retained, prioritized, and evicted within the buffer pool. They determine how memory is allocated to balance performance and resource usage.

---
### `How It Works`

- **Retention Strategy**  
    Establishes rules for how long pages should remain in memory based on access patterns.

- **Access Tracking**  
    Monitors page usage metrics such as recency or frequency.

- **Eviction Criteria**  
    Works with page replacement algorithms to select candidates for removal.

- **Priority Handling**  
    May prioritize certain types of pages (e.g., index pages or frequently accessed data).

- **Integration with Write Policies**  
    Coordinates when modified pages should be flushed to disk.

---
### `Why It Exists`

- To optimize memory utilization
- To improve overall query performance
- To reduce unnecessary disk I/O
- To adapt buffer behavior to workload characteristics

---
### `Connected Notes`

- [[Buffer Management]]