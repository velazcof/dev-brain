
**Apache Pulsar** is a **distributed messaging and event streaming platform** designed to support **both traditional messaging (queues, pub/sub)** and **event streaming** within a single system.

It separates **message storage from serving**, enabling high scalability, multi-tenancy, and flexible messaging patterns.

---
### `Key Capabilities`

- **Unified Messaging & Streaming**  
    Supports:
    
    - Message queues
    - Publish–subscribe
    - Event streaming  
        within the same platform.
    
- **Separation of Compute & Storage**  
    Brokers handle message delivery, while storage is managed independently (typically via Apache BookKeeper).
    
- **Multi-Tenancy by Design**  
    Built-in support for:
    
    - Tenants
    - Namespaces
    - Isolation and quotas
    
- **Scalability & Elasticity**  
    Scales horizontally with minimal rebalancing overhead.
    
- **Durability & Replay**  
    Messages are persisted and can be replayed by consumers.
    
- **Geo-Replication**  
    Native support for replicating topics across regions and data centers.
    
- **Protocol Support**  
    Supports Pulsar protocol and Kafka-compatible APIs.

---
### `Usage Basics`

- Producers publish messages to **topics**.
    
- Topics are organized into **namespaces** under **tenants**.
    
- Consumers subscribe using:
    
    - Exclusive
    - Shared
    - Failover
    - Key-shared subscriptions
    
- Messages are acknowledged after processing.
    
- Retention and persistence are configurable per topic.

---
### `Challenges`

- **Operational Complexity**  
    Requires managing brokers, BookKeeper clusters, and coordination services.
    
- **Smaller Ecosystem Than Kafka**  
    Fewer third-party tools and integrations compared to Kafka.
    
- **Conceptual Overhead**  
    Additional abstractions (tenants, namespaces) add learning curve.
    
- **Overkill for Simple Queues**  
    More complex than needed for basic job-queue scenarios.

---
### `Connected Notes`

- [[Message Brokers]]