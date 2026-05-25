
### `Definition`

**Delivery Guarantees** describe the promises a messaging system makes about how many times a message may be delivered and processed, especially in the presence of failures. They define the balance between **reliability, duplication, and complexity**.

---
### `Key Ideas`

- **At-Most-Once**  
    A message is delivered **zero or one time**.
    - No retries
    - Messages may be lost
    - Lowest latency, simplest handling

- **At-Least-Once**  
    A message is delivered **one or more times** until acknowledged.
    - Retries enabled
    - Duplicates possible
    - Most common guarantee in practice

- **Exactly-Once**  
    A message is processed **once and only once**.
    - No loss, no duplication
    - Requires coordination, idempotency, or transactions
    - Highest complexity and cost

- **Guarantees Are End-to-End**  
    True delivery guarantees depend on:
    - Acknowledgements
    - Retry behavior
    - Consumer logic (idempotency)
    - Broker or framework capabilities

- **Trade-offs Are Inevitable**  
    Stronger guarantees typically increase:
    - Latency
    - Operational complexity
    - System coupling
    - Resource usage

---
### `Why It Exists`

- To set clear expectations around message reliability
- To guide system design and consumer behavior
- To handle failures predictably
- To choose appropriate trade-offs for different workloads
- To avoid false assumptions about message processing

---
### `Connected Notes`

- [[Message Delivery Semantics]]