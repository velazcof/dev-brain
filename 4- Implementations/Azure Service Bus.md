
**Azure Service Bus** is a **fully managed enterprise messaging service** provided by Microsoft Azure that supports **message queues and publish–subscribe messaging** with advanced reliability, ordering, and transactional guarantees.

It is designed for **enterprise-grade asynchronous communication** between distributed applications.

---
### `Key Capabilities`

- **Queues & Topics (Pub/Sub)**  
    Supports:
    
    - **Queues** for point-to-point messaging
    - **Topics & Subscriptions** for publish–subscribe patterns
    
- **Enterprise Messaging Features**  
    Includes:
    
    - Guaranteed message ordering
    - Duplicate detection
    - Dead-letter queues
    - Scheduled and deferred messages
    
- **Transactions & Sessions**  
    Enables transactional message handling and **session-based ordering** for related messages.
    
- **Managed & Highly Available**  
    Fully managed by Azure with built-in replication and fault tolerance.
    
- **Security & Identity Integration**  
    Integrated with Azure Active Directory (Entra ID) and role-based access control.
    
- **Hybrid Integration Support**  
    Often used to connect on-prem systems with Azure-hosted services.

---
### `Usage Basics`

- Create a **namespace**.
    
- Define:
    
    - **Queues**, or
    - **Topics** with **subscriptions**
    
- Producers send messages via Azure SDKs.
    
- Consumers receive and acknowledge messages.
    
- Failed messages can be routed to **dead-letter queues**.

---
### `Challenges`

- **Azure Lock-In**  
    Tightly coupled to the Azure ecosystem.
    
- **Operational Limits**  
    Throughput and feature availability vary by pricing tier.
    
- **Not an Event Streaming Platform**  
    Not suitable for large-scale event replay or analytics workloads like Kafka.
    
- **Configuration Complexity**  
    Rich feature set can increase setup and operational complexity.

---
### `Connected Notes`

- [[Message Brokers]]