
**Message Queues** are a messaging mechanism where **messages are sent to a queue and processed by exactly one consumer**. They enable asynchronous, decoupled work distribution between producers and workers.

---
### `How It Works`

- A producer **sends a message** to a queue.
- The message is **stored** until a consumer is available.
- A consumer **retrieves and processes** the message.
- Once successfully processed, the message is **acknowledged and removed**.
- If processing fails, the message may be retried or moved to a dead-letter queue.

Messages are typically processed in **FIFO order**, though ordering guarantees vary by implementation.

---
### `Why It Exists`

- To **decouple producers from consumers**
- To smooth traffic spikes and **level load**
- To enable **background and asynchronous processing**
- To improve system **resilience and fault tolerance**
- To allow **horizontal scaling** by adding more consumers

---
### `Connected Notes`

- [[Messaging Patterns]]