
A **Dead-Letter Queue (DLQ)** is a holding queue where **messages that cannot be successfully processed** are sent after repeated failures, instead of being retried indefinitely or blocking normal message flow.

It isolates problematic messages so systems can continue operating reliably.

---
### `How It Works`

- A message is delivered to a consumer for processing.
- Processing fails (e.g. exception, timeout, validation error).
- The messaging system retries the message according to configured rules.

- After exceeding retry limits or meeting failure criteria:
    - The message is **redirected to a dead-letter queue**

- Operators or systems can later:
    - Inspect the message
    - Debug the failure
    - Replay, fix, or discard it

**DLQs typically preserve:**

- The original message
- Failure metadata (error reason, retry count, timestamps)

---
### `Why It Exists`

- To prevent **poison messages** from blocking the system
- To avoid infinite retry loops
- To improve **system resilience and stability**
- To enable debugging and root-cause analysis
- To separate operational failure handling from normal message processing

---
### `Connected Notes`

- [[Message Delivery Semantics]]