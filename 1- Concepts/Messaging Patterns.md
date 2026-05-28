
**Messaging Patterns** are **reusable communication models** that describe **how messages are exchanged, routed, and processed** between components in a distributed system.

They capture _common solutions_ to recurring messaging problems, independent of any specific technology or tool.

---
### `Key Ideas`

- **Describe “How”, Not “What”**  
    Messaging patterns explain _how communication behaves_ (one-to-one, one-to-many, ordered, replayable), not what system implements it.
    
- **Technology-Agnostic**  
    The same pattern can be implemented using different message brokers or frameworks.
    
- **Solve Recurring Distributed Problems**  
    Patterns address concerns such as:
    
    - Decoupling producers and consumers
    - Scalability and parallel processing
    - Reliability and fault tolerance
    - Event distribution and coordination
    
- **Different Patterns, Different Trade-offs**  
    Each pattern makes different guarantees around:
    
    - Delivery (once, at-least-once, exactly-once)
    - Ordering
    - Fan-out behavior
    - Persistence and replay
    
- **Foundation for Architecture Decisions**  
    Choosing a messaging pattern is an architectural decision that shapes system behavior more than the underlying tool.

---
### `Connected Notes`

- [[Messaging Systems]]
- [[Message Queues]]
- [[Publish–Subscribe]]
- [[Event Streaming]]
- [[Request–Reply Messaging]]
- [[Fan-Out Fan-In]]