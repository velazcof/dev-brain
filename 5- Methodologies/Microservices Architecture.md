
**Microservices Architecture** is an architectural pattern where a system is composed of **small, independently deployable services**, each responsible for a single business capability.  

Microservices communicate over lightweight protocols (often HTTP or messaging) and can be developed, deployed, and scaled independently.

---
### `Key Ideas`

- **Single Responsibility Services:**  
    Each microservice focuses on one business function (e.g., orders, payments, inventory).  
    _Supports clear ownership and modular development._
    
- **Independent Deployment:**  
    Teams can release updates without affecting other services.  
    _Ideal for fast-moving organizations practicing CI/CD._
    
- **Polyglot Freedom:**  
    Different services can use different languages, frameworks, or databases.  
    _Allows teams to choose the best tool for their domain._
    
- **Decentralized Data:**  
    Each service owns its own database or storage model.  
    _Prevents tight coupling through shared schemas._
    
- **Scales by Capability:**  
    You scale only the services that need it (e.g., checkout during a sale).  
    _Highly cost-efficient compared to monolithic scaling._
    
- **Resilience Through Isolation:**  
    If one service fails, others can continue running.  
    _Supports modern distributed, cloud-native systems._

---
### `Challenges`

- Increased operational overhead (monitoring, logging, tracing).
    
- Distributed systems introduce latency and network complexity.
    
- Requires careful data consistency strategies (eventual consistency, sagas).
    
- Harder debugging due to multiple processes.
    
- Risk of creating a “distributed monolith” if boundaries aren’t clear.

---
### `Connected Notes`

- [[Architectural Patterns]]