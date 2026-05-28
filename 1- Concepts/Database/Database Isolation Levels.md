
**Isolation Levels** define how concurrent transactions interact and what kinds of side effects they are allowed to observe. They specify the degree to which one transaction is isolated from the intermediate states of others.

---
### `Key Ideas`

- **Concurrency Visibility Control**  
    Isolation levels determine what a transaction can see when other transactions are reading or modifying data at the same time.
    
- **Anomaly Prevention Spectrum**  
    Different levels prevent different concurrency anomalies such as dirty reads, non-repeatable reads, or phantom reads.
    
- **Trade-Off with Performance**  
    Stronger isolation typically requires more coordination, increasing overhead and reducing concurrency.
    
- **Transaction Scope**  
    Isolation is defined at the transaction level, not at the database level as a whole.
    
- **Part of ACID**  
    Isolation is one of the four guarantees in ACID Properties, but it is configurable in most systems.
    
- **Defined by Behavior, Not Mechanism**  
    Isolation levels describe observable behavior, not how it is enforced (e.g., via Database Locking or MVCC).

---
### `Connected Notes`

- [[Database Properties]]