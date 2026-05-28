
**Google Cloud Pub/Sub** is a **fully managed, global publish–subscribe messaging service** that enables applications to **publish events and deliver them asynchronously** to multiple subscribers at scale.

It is designed for **event-driven systems**, streaming ingestion, and loosely coupled services.

---
### `Key Capabilities`

- **Managed Publish–Subscribe**  
    Producers publish messages to **topics**, and subscribers receive copies independently.
    
- **Global, Serverless Service**  
    No infrastructure to manage; scales automatically across regions.
    
- **Push & Pull Delivery Models**  
    Subscribers can:
    
    - Pull messages at their own pace
    - Receive pushed messages via HTTP endpoints
    
- **At-Least-Once Delivery**  
    Messages are delivered reliably, with acknowledgment-based processing.
    
- **Message Retention & Replay**  
    Messages can be retained and replayed within a configurable retention window.
    
- **Ordering Support**  
    Supports ordered delivery using ordering keys (with constraints).
    
- **Security & IAM Integration**  
    Fine-grained access control using Google Cloud IAM.

---
### `Usage Basics`

- Create a **topic**.
    
- Publishers send messages to the topic.
    
- Create **subscriptions** (push or pull).
    
- Subscribers acknowledge messages after processing.
    
- Unacknowledged messages are redelivered.

---
### `Challenges`

- **Limited Exactly-Once Semantics**  
    Exactly-once delivery is supported but with constraints and cost considerations.
    
- **Less Flexible Routing**  
    Compared to traditional brokers, routing logic is limited.
    
- **Vendor Lock-In**  
    Tightly coupled to Google Cloud.
    
- **Not a Traditional Queue System**  
    Better suited for event distribution than work queues.

---
### `Connected Notes`

- [[Message Brokers]]