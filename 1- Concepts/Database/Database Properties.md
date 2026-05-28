
**Database properties** are the fundamental guarantees and behavioral characteristics that define how a database maintains correctness, consistency, and reliability.

They describe what assurances a database provides, independent of how those guarantees are implemented internally.

---
### `Key Ideas`

- **Correctness Guarantees**  
    Databases define rules to ensure data remains valid and logically consistent.
    
- **Transaction Behavior**  
    Properties govern how operations behave under concurrent access and system failures.
    
- **Failure Handling**  
    Databases specify how data integrity is preserved during crashes or unexpected interruptions.
    
- **Consistency Expectations**  
    Different systems may offer different levels of consistency depending on their design goals.
    
- **Abstract Guarantees**  
    These properties define _what must hold true_, not _how it is enforced_ (which belongs to mechanisms).

---
### `Connected Notes`

- [[ACID Properties]]
- [[Database Consistency Models]]
- [[Database Isolation Levels]]
- [[Database Durability]]
- [[Databases]]