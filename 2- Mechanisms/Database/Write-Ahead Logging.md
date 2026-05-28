
### `Definition`

**Write-Ahead Logging (WAL)** is a durability mechanism that records changes to a log before applying them to the main data files. It ensures that committed transactions can be recovered even if a system failure occurs.

---
### `How It Works`

- **Log Before Data**  
    When a change is made, a record describing the modification is written to a log file before the corresponding data page is updated on disk.

- **Sequential Log Writes**  
    Log records are typically written sequentially, improving disk write efficiency.

- **Commit Recording**  
    A transaction is considered committed only after its log records are safely persisted.

- **Crash Recovery**  
    After a failure, the system replays or rolls back operations using the log to restore a consistent state.

- **Coordination with Checkpointing**  
    Periodic checkpoints reduce recovery time by marking stable states.

---
### `Why It Exists`

- To guarantee durability of committed transactions
- To enable reliable crash recovery
- To prevent data loss from incomplete writes
- To allow efficient disk write strategies

---
### `Connected Notes`

- [[Storage Subsystem]]