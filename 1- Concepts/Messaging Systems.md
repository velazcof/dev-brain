
**Messaging Systems** are systems that enable **asynchronous communication** between independent components by exchanging **messages** instead of making direct calls. They decouple producers and consumers, allowing systems to communicate **reliably, flexibly, and at scale**.

---
### `Key Ideas`

- **Asynchronous Communication**  
    Components do not need to be online or available at the same time to communicate.
    
- **Loose Coupling**  
    Senders do not need to know who receives the message or how it is processed.
    
- **Message-Based Interaction**  
    Communication happens by sending structured messages rather than invoking functions or APIs directly.
    
- **Improved Reliability**  
    Messages can be stored, retried, or replayed if consumers fail.
    
- **Scalability**  
    Multiple consumers can process messages in parallel.
    
- **Foundational to Distributed Systems**  
    Messaging systems are a core building block for microservices, event-driven architectures, and cloud-native applications.

---
### `Connected Notes`

- [[Distributed System]]
- [[Messaging Patterns]]
- [[Messaging Frameworks]]
- [[Message Brokers]]
- [[Message Delivery Semantics]]
