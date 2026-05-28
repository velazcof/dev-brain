
**Fan-Out / Fan-In** is a messaging pattern where a single task or message is **split into multiple parallel units of work (fan-out)** and the results are later **collected and combined (fan-in)** into a final outcome.

It enables **parallel processing** while preserving a single logical workflow.

---
### `How It Works`

- A producer emits a **single initiating message**.
- The system **fans out** the work by:
    - Creating multiple messages
    - Dispatching them to parallel consumers or workers

- Each consumer processes its portion independently.
- Results are sent back to a coordination point.
- The system **fans in** by:
    - Aggregating results
    - Detecting completion
    - Producing a final response or event

**Coordination often relies on:**

- Correlation identifiers
- Completion counters
- Timeouts or partial aggregation rules

---
### `Why It Exists`

- To **speed up processing** through parallelism
- To break large tasks into **independent, scalable units**
- To improve fault isolation (one failure doesn’t stop all work)
- To support batch processing and distributed computation
- To enable elastic scaling of workloads

---
### `Connected Notes`

- [[Messaging Patterns]]