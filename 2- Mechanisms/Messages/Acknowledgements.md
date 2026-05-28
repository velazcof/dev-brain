
**Acknowledgements** define how and when a consumer **confirms successful processing of a message** to the messaging system.

They determine whether a message is considered completed, retried, or redelivered.

---
### `How It Works`

- A message is delivered to a consumer.
- After processing:
    - The consumer sends an **acknowledgement** to the messaging system.

- If an acknowledgement is received:
    - The message is marked as successfully processed.

- If no acknowledgement is received (e.g. crash, timeout):
    - The message may be redelivered or retried.

**Acknowledgements can be:**
- Automatic (ack on receipt)
- Manual (ack after successful processing)
- Explicitly rejected (negative acknowledgement)

---
### `Why It Exists`

- To confirm message processing success
- To enable retries and redelivery on failure
- To prevent silent message loss
- To support delivery guarantees
- To coordinate reliable message handling in distributed systems

---
### `Connected Notes`

- [[Message Delivery Semantics]]