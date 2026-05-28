
**Message Delivery Semantics** describe the **behavioral guarantees and failure-handling rules** that govern how messages are delivered, retried, acknowledged, and handled when processing fails in a messaging system.

They define **what happens under success, delay, duplication, or failure**—independent of the messaging pattern used.

---
### `Key Ideas`

- **Orthogonal to Messaging Patterns**  
    Delivery semantics apply equally to queues, pub/sub, streaming, and request–reply.  
    They do not change message flow shape—only behavior under failure.

- **Delivery Guarantees**  
    Common guarantees include:
    - **At-most-once**: messages may be lost, never duplicated
    - **At-least-once**: messages are retried, duplicates possible
    - **Exactly-once**: messages processed once (hard and costly)

- **Acknowledgements & Visibility**  
    Consumers explicitly acknowledge successful processing; unacknowledged messages may be redelivered.

- **Retries & Backoff**  
    Failed messages can be retried automatically, often with delays or exponential backoff.

- **Dead-Letter Handling**  
    Messages that repeatedly fail can be isolated for inspection instead of blocking the system.

- **Trade-offs Are Inevitable**  
    Stronger guarantees often increase:
    - Latency
    - Complexity
    - Cost
    - Operational burden
    
    Messaging systems choose trade-offs deliberately.

---
### `Connected Notes`

- [[Messaging Systems]]
- [[Dead-Letter Queues]]
- [[Retries]]
- [[Acknowledgements]]
- [[Delivery Guarantees]]
- [[Idempotency]]