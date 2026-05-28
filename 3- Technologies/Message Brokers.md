
A **Message Broker** is a **software system** that receives, stores, routes, and delivers messages between producers and consumers according to defined messaging patterns. It acts as the **central intermediary** that enables asynchronous, decoupled communication in messaging systems.

---
### `Key Ideas`

- **Intermediary Role**  
    Producers send messages to the broker, and consumers receive messages from it—without direct awareness of each other.
    
- **Implements Messaging Patterns**  
    Message brokers support patterns such as:
    
    - Message queues
    - Publish–subscribe
    - Event streaming
    - Request–reply
    
- **Message Routing & Delivery**  
    Brokers determine:
    
    - Where messages go
    - Which consumers receive them
    - When messages are delivered
    
- **Reliability Features**  
    Common capabilities include:
    
    - Message persistence
    - Retries and acknowledgements
    - Dead-letter queues
    - Ordering guarantees
    
- **Scalability & Concurrency**  
    Brokers enable multiple consumers to process messages in parallel, improving throughput.
    
- **Decoupling at Scale**  
    Producers and consumers can evolve, scale, and fail independently.

---
### `Use Cases`

- Background job processing
    
- Event-driven architectures
    
- Inter-service communication in distributed systems
    
- Load leveling and traffic smoothing
    
- Asynchronous workflows and integrations

---
### `Connected Notes`

- [[Messaging Systems]]
- [[RabbitMQ]]
- [[Apache Kafka]]
- [[Amazon SQS]]
- [[Amazon SNS]]
- [[Azure Service Bus]]
- [[Google Pub-Sub]]
- [[Apache Pulsar]]