
### `Definition`

**Publish–Subscribe (Pub/Sub)** is a messaging pattern where **producers publish messages to a topic**, and **multiple independent consumers receive a copy** of each message by subscribing to that topic.

Publishers and subscribers are **fully decoupled** and unaware of each other.

---
### `How It Works`

- A producer **publishes a message** to a named topic.
- The messaging system:
    - Tracks all active **subscriptions** to that topic
    - Delivers a copy of the message to each subscriber
- Subscribers process messages **independently**.
- Delivery can be:
    - Push-based (messages sent to consumers)
    - Pull-based (consumers fetch messages)
- Subscribers can join or leave without affecting publishers.

---
### `Why It Exists`

- To **broadcast events** to multiple consumers
- To allow **multiple reactions** to the same event
- To support **event-driven architectures**
- To decouple producers from downstream systems
- To make systems extensible without changing publishers

---
### `Connected Notes`

- [[Messaging Patterns]]