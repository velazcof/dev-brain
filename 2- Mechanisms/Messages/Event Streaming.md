
### `Definition`

**Event Streaming** is a messaging pattern where events are **continuously published to an append-only log** and **consumed sequentially by subscribers**, who track their own position in the stream.

Events are **retained** and can be **replayed**, enabling systems to process data in real time or retrospectively.

---
### `How It Works`

- Producers **append events** to a named stream (topic).
- Events are stored **in order** and retained for a configured duration.
- Consumers:
    - Read events sequentially
    - Maintain their own **offset or cursor**
    - Can pause, resume, or replay events

- Multiple consumers can read the same stream independently without interfering with each other.
- Ordering is guaranteed **within a partition or shard**.

---
### `Why It Exists`

- To enable **real-time data processing**
- To support **event replay and auditing**
- To decouple producers from consumers over time
- To build **event-driven and data-driven architectures**
- To scale event consumption across multiple independent systems

---
### `Connected Notes`

- [[Messaging Patterns]]