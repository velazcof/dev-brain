
**Request–Reply** is a messaging pattern where one component **sends a request message** and later receives a corresponding response message, without requiring a direct, synchronous connection. 

It enables **asynchronous interactions** that still preserve a question–answer flow.

---
### `How It Works`

- A requester sends a **request message** to a messaging system.
- The request includes a **correlation identifier**.
- A responder processes the request and sends a **reply message**.
- The reply references the original request via the correlation identifier.
- The requester matches the reply to the original request and continues processing.

**Communication typically occurs via:**

- Separate request and reply queues
- Topics with reply-to metadata

---
### `Why It Exists`

- To avoid blocking synchronous calls
- To enable long-running or delayed responses
- To improve reliability in distributed systems
- To decouple requesters from responders
- To support scalable, message-based workflows

---
### `Connected Notes`

- [[Messaging Patterns]]