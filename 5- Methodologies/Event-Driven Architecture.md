
**Event-Driven Architecture (EDA)** is a software design pattern where system components communicate by **producing and consuming events**.  

Instead of direct synchronous calls, components react to events that represent state changes or actions in the system.

---
### `Key Ideas`

- **Asynchronous Communication:**  
    Components don’t wait for each other — they react to events when they occur.  
    _Ideal for high-throughput or loosely coupled systems._
    
- **Producers and Consumers:**  
    Services publish events (e.g., _OrderPlaced_, _PaymentCompleted_) that other services subscribe to.  
    _Supports scalable, decoupled workflows._
    
- **Event Brokers as Glue:**  
    Systems use tools like Kafka, RabbitMQ, SNS/SQS, or EventBridge.  
    _Reliable message delivery and buffering._
    
- **Loose Coupling:**  
    Services don’t need to know about each other — only the event format.  
    _Greatly improves agility and system flexibility._
    
- **Reactive Systems:**  
    Real-time updates, streaming, IoT, and analytics pipelines rely on event-driven flows.

---
### `Challenges`

- Harder debugging due to asynchronous flows.
    
- Event duplication or ordering issues require careful design.
    
- Complex traceability — requires distributed tracing.
    
- Event storms or high throughput need robust infrastructure.
    
- Designing events and versioning them is non-trivial.

---
### `Connected Notes`

- [[Architectural Patterns]]