
**Amazon Simple Queue Service (SQS)** is a **fully managed message queue service** provided by AWS that enables **asynchronous, decoupled communication** between distributed application components without managing messaging infrastructure.

---
### `Key Capabilities`

- **Managed Message Queues**  
    AWS operates and scales the service—no servers or brokers to manage.
    
- **Queue Types**
    
    - **Standard Queues**: high throughput, at-least-once delivery, best-effort ordering
    - **FIFO Queues**: exactly-once processing, strict message ordering
    
- **Reliability & Durability**  
    Messages are redundantly stored across multiple availability zones.
    
- **Scalability**  
    Automatically scales to handle virtually unlimited throughput.
    
- **Security Integration**  
    Tight integration with AWS IAM for access control and encryption.
    
- **Dead-Letter Queues (DLQ)**  
    Failed messages can be isolated for inspection and retries.
    
- **Event-Driven Integration**  
    Works seamlessly with Lambda, SNS, EventBridge, and other AWS services.

---
### `Usage Basics`

- Create a queue (Standard or FIFO).
    
- Producers send messages to the queue via AWS SDK or API.
    
- Consumers poll the queue and process messages.
    
- Messages are deleted after successful processing.
    
- Visibility timeout prevents duplicate processing during handling.

---
### `Challenges`

- **Polling-Based Consumption**  
    Consumers must poll queues, which can add latency.
    
- **Limited Routing Capabilities**  
    No native topic-style routing like traditional brokers.
    
- **Vendor Lock-In**  
    Tied tightly to the AWS ecosystem.
    
- **Not a Streaming System**  
    Unsuitable for high-throughput event replay or analytics use cases.

---
### `Connected Notes`

- [[Message Brokers]]