
**ACID Properties** are the four foundational guarantees that define reliable transaction behavior in a database system. They describe the conditions that must hold true for data operations to be considered correct and safe.

---
### `Key Ideas`

- **Atomicity**  
    A transaction either completes entirely or has no effect at all.
    
- **Consistency**  
    A transaction moves the database from one valid state to another, preserving defined rules and constraints.
    
- **Isolation**  
    Concurrent transactions behave as if they were executed independently, according to a defined isolation level.
    
- **Durability**  
    Once a transaction is committed, its changes persist even in the event of system failure.
    
- **Guarantee-Level Concept**  
    ACID defines _what must be guaranteed_, not how those guarantees are implemented.

---
### `Connected Notes`

- [[Database Properties]]