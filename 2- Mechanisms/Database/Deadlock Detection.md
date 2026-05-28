
**Deadlock Detection** is the mechanism that identifies situations where two or more transactions are waiting indefinitely for resources held by each other. It enables the system to resolve circular wait conditions and restore progress.

---
### `How It Works`

- **Wait Tracking**  
    The system monitors which transactions are waiting for locks held by others.

- **Cycle Detection**  
    It analyzes dependency relationships to detect cycles in the wait graph.

- **Victim Selection**  
    When a deadlock is detected, one transaction is chosen to be rolled back.

- **Rollback & Recovery**  
    The selected transaction is aborted to release its locks, allowing other transactions to proceed.

---
### `Why It Exists`

- To prevent indefinite blocking caused by circular resource dependencies
- To maintain system liveness under high concurrency
- To ensure that lock-based concurrency control does not halt progress

---
### `Connected Notes`

- [[Transaction Management]]