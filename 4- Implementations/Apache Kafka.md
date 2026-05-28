
**Apache Kafka** is a **distributed event streaming platform** used to **publish, store, and process streams of events** at high throughput with strong durability and replay capabilities. It is designed around **append-only logs** rather than traditional message queues.

---
### `Key Capabilities`

- **Event Streaming (Log-Based)**  
    Messages (events) are appended to immutable logs (topics) and retained for a configurable period.
    
- **High Throughput & Low Latency**  
    Optimized for millions of events per second with horizontal scalability.
    
- **Durability & Replay**  
    Events are persisted to disk and can be replayed by consumers at any time.
    
- **Partitioning & Parallelism**  
    Topics are partitioned to enable parallel consumption and scale-out processing.
    
- **Consumer Groups**  
    Multiple consumers can coordinate to process partitions without duplicating work.
    
- **Ecosystem & Tooling**  
    Includes Kafka Streams, Kafka Connect, and integrations across data platforms.

---
### `Usage Basics`

- Producers publish events to **topics**.
    
- Topics are split into **partitions**.
    
- Consumers read events using **offsets** they manage.
    
- Retention is time- or size-based, not delete-on-consume.
    
- Ordering is guaranteed **within a partition**.

---
### `Challenges`

- **Operational Complexity**  
    Requires managing brokers, partitions, replication, and tuning (unless using a managed service).
    
- **Learning Curve**  
    Concepts like offsets, partitions, and rebalancing add complexity.
    
- **Not a Traditional Queue**  
    Lacks simple delete-on-consume semantics; unsuitable for some job-queue use cases.
    
- **Exactly-Once Semantics Are Advanced**  
    Available, but require careful configuration and understanding.

---
### `Connected Notes`

- [[Message Brokers]]