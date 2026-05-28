
**Database Durability** is the guarantee that once a transaction is committed, its changes will persist even in the event of crashes or system failures. It defines when a system considers data permanently stored and safe from loss.

---
### `Key Ideas`

- **Commit Safety Boundary**  
    Durability answers: _At what exact moment is a transaction considered irreversible?_  
    This boundary depends on how and when data is flushed to stable storage.
    
- **Persistence vs Acknowledgment**  
    A system may acknowledge a commit before data is physically written to disk, depending on configuration.
    
- **Failure Model Awareness**  
    Durability guarantees are defined relative to failure types (process crash, power loss, hardware failure, distributed node failure).
    
- **Performance Trade-Offs**  
    Stronger durability typically increases latency due to synchronous log flushing, disk writes, or replicated confirmations.
    
- **Configurable Guarantees**  
    Many systems allow durability levels to be tuned (e.g., synchronous vs asynchronous commit).
    
- **Interaction with Mechanisms**  
    Durability is enforced through mechanisms such as Write-Ahead Logging, Checkpointing, and replication strategies — but durability itself defines the guarantee, not the implementation.
    
- **Distributed System Implications**  
    In distributed databases, durability may depend on replication or consensus protocols before acknowledging a commit.
    
- **Part of ACID**  
    Durability is one dimension of the broader ACID Properties framework.

---
### `Connected Notes`

- [[Database Properties]]