
**Checkpointing** is a recovery mechanism that periodically writes a consistent snapshot of in-memory database state to persistent storage. It reduces the amount of log replay required during crash recovery.

---
### `How It Works`

- **Stable State Recording**  
    The system ensures that modified pages in memory are written to disk up to a known point.

- **Log Position Marking**  
    A checkpoint records a position in the write-ahead log indicating that prior changes are safely persisted.

- **Dirty Page Flushing**  
    Pages modified in memory are flushed to data files in a coordinated manner.

- **Recovery Optimization**  
    During restart, recovery begins from the last checkpoint instead of replaying the entire log history.

- **Coordination with Logging**  
    Works alongside write-ahead logging to maintain durability and consistency.

---
### `Why It Exists`

- To reduce recovery time after failures
- To limit excessive log growth
- To maintain efficient durability mechanisms
- To ensure consistent persistent state over time

---
### `Connected Notes`

- [[Storage Subsystem]]