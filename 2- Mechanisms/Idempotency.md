
**Idempotency** is the property where **performing the same operation multiple times produces the same result as performing it once**.

It allows systems to safely handle **duplicate messages or repeated requests** without causing unintended side effects.

---
### `Key Ideas`

- **Duplicate-Safe Operations**  
    An idempotent operation can be retried or repeated without changing the final system state.
    
- **Critical for Reliable Messaging**  
    In systems with **at-least-once delivery**, duplicate message processing is expected, not exceptional.
    
- **State-Based Correctness**  
    Idempotency is usually enforced by checking existing state before applying changes.
    
- **Common Strategies**
    
    - Unique request or message IDs
    - Deduplication tables or caches
    - Version checks or optimistic locking
    - Natural idempotent operations (e.g. setting a value vs incrementing)
    
- **Application-Level Responsibility**  
    Messaging systems can deliver duplicates, but **only application logic can ensure idempotent behavior**.
    
- **Often Misunderstood**  
    Exactly-once delivery at the broker level does **not remove the need for idempotent consumers**.

---
### `Why It Exists`

- To safely support retries and redelivery
    
- To prevent duplicate side effects (double charges, duplicate records)
    
- To enable fault-tolerant distributed systems
    
- To simplify error handling and recovery
    
- To make delivery guarantees practical in real systems

---
### `Connected Notes`

- [[Message Delivery Semantics]]