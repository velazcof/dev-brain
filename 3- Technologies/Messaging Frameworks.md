
**Messaging Frameworks** are **software frameworks** that sit on top of message brokers to **simplify building message-based applications**. They abstract low-level messaging concerns and provide higher-level constructs for **reliability, workflows, and developer productivity**.

Messaging frameworks **do not replace message brokers** — they **use them**.

---
### `Key Ideas`

- **Built on Top of Message Brokers**  
    Messaging frameworks rely on brokers (RabbitMQ, SQS, Kafka, etc.) for transport and delivery.
    
- **Higher-Level Abstractions**  
    They provide concepts such as:
    
    - Message handlers
    - Retries and error handling
    - Serialization and versioning
    - Correlation and tracing
    - Idempotency
    
- **Workflow & Coordination Support**  
    Many frameworks support:
    
    - Long-running workflows (sagas)
    - Message orchestration
    - State management across messages
    
- **Consistency & Safety**  
    Reduce common messaging pitfalls like:
    
    - Duplicate processing
    - Poison messages
    - Missing acknowledgements
    - Manual retry logic
    
- **Developer-Focused**  
    Emphasize:
    
    - Declarative configuration
    - Convention over configuration
    - Integration with application frameworks
    
- **Opinionated by Design**  
    Frameworks encode best practices, which:
    
    - Speeds up development
    - Reduces flexibility compared to raw brokers

---
### `Use Cases`

- Complex message-driven systems
    
- Enterprise integration scenarios
    
- Long-running business workflows
    
- Event-driven microservices
    
- Teams that want messaging best practices enforced by default

---
### `Connected Notes`

- [[Messaging Systems]]
- [[NServiceBus]]
- [[MassTransit]]
- [[Spring Cloud Stream]]
- [[Apache Camel]]
- [[Azure Service Bus SDKs]]
