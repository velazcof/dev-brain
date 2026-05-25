
### `Definition`

**Retries** describe the behavior where a message that fails processing is **delivered again for reprocessing** instead of being immediately discarded or marked as failed. They allow transient errors to be resolved without manual intervention.

---
### `How It Works`

- A message is delivered to a consumer.
- Processing fails due to:
    - Temporary service unavailability
    - Network issues
    - Timeouts

- The messaging system:
    - Schedules the message for redelivery
    - Applies retry rules (count, delay, backoff)

- Retries continue until:
    - The message is successfully processed, or
    - Retry limits are exceeded and the message is sent to a dead-letter queue

**Retries may be:**

- Immediate or delayed
- Fixed or exponential backoff
- Broker-managed or consumer-managed

---
### `Why It Exists`

- To handle **transient failures** automatically
- To improve reliability without human intervention
- To avoid losing messages due to temporary issues
- To smooth over short-lived system outages
- To reduce operational burden

---
### `Connected Notes`

- [[Message Delivery Semantics]]