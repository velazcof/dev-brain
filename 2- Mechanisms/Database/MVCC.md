
### `Definition`

**Multi-Version Concurrency Control (MVCC)** is a concurrency control mechanism that allows multiple transactions to access the same data by maintaining multiple versions of records. It enables readers and writers to operate concurrently without blocking each other under certain isolation levels.

---
### `How It Works`

- **Version Creation**  
    When a transaction modifies a record, a new version is created instead of overwriting the existing one.

- **Snapshot Visibility**  
    Each transaction reads data according to a consistent snapshot determined at its start time or statement time.

- **Version Metadata**  
    Records are tagged with transaction-related metadata to determine which version is visible to which transaction.

- **Garbage Collection**  
    Older versions that are no longer needed are eventually cleaned up.

- **Reduced Lock Contention**  
    Read operations often avoid acquiring blocking locks on modified data.

---
### `Why It Exists`

- To improve concurrency by reducing blocking between readers and writers
- To maintain isolation while supporting high throughput
- To provide predictable snapshot-based reads in concurrent environments

---
### `Connected Notes`

- [[Transaction Management]]