
**RabbitMQ** is an open-source **message broker** that implements **message queuing and publish–subscribe messaging** using the AMQP protocol. It is used to enable **asynchronous, reliable communication** between distributed applications.

---
### `Key Capabilities`

- **Message Queues & Pub/Sub**  
    Supports point-to-point queues and fan-out messaging via exchanges and bindings.
    
- **Protocol Support**  
    Native support for **AMQP**, with plugins for MQTT, STOMP, and HTTP.
    
- **Reliable Message Delivery**  
    Provides acknowledgements, persistence, retries, and dead-letter queues.
    
- **Flexible Routing**  
    Uses exchanges (direct, topic, fanout, headers) to control how messages are routed.
    
- **Horizontal Scalability**  
    Supports clustering and high availability configurations.
    
- **Broad Language Support**  
    Client libraries exist for most major programming languages.
    
- **Extensible via Plugins**  
    Management UI, federation, shovels, and authentication plugins.

---
### `Usage Basics`

- Runs as a standalone server or containerized service.
    
- Applications:
    
    - Publish messages to **exchanges**
    - Consume messages from **queues**
    
- Typical workflow:
    
    - Producer → Exchange → Queue → Consumer
    
- Includes a web-based **management UI** for monitoring and configuration.

---
### `Challenges`

- **Operational Complexity**  
    Requires careful configuration for clustering, durability, and performance.
    
- **Throughput Limits vs Streaming Systems**  
    Not optimized for very high-throughput event streaming compared to Kafka.
    
- **Message Ordering Guarantees**  
    Ordering is per-queue and can be affected by parallel consumers.
    
- **Requires Broker Management**  
    Unlike managed services (e.g. SQS), RabbitMQ must be operated and maintained.

---
### `Connected Notes`

- [[Message Brokers]]