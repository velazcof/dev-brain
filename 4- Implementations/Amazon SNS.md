
**Amazon Simple Notification Service (SNS)** is a **fully managed publish–subscribe messaging service** provided by AWS that enables applications to **broadcast messages to multiple subscribers**.

It is designed for **event notification and fan-out messaging**, not task processing.

---
### `Key Capabilities`

- **Publish–Subscribe Messaging**  
    Messages are published to **topics** and delivered to all subscribed endpoints.
    
- **Multiple Subscription Types**  
    Supports delivery to:
    
    - SQS queues
    - Lambda functions
    - HTTP/HTTPS endpoints
    - Email / SMS
    - Mobile push notifications
    
- **Managed & Serverless**  
    No infrastructure to provision, scale, or maintain.
    
- **High Availability & Durability**  
    Messages are replicated across multiple AWS availability zones.
    
- **Integration with AWS Ecosystem**  
    Commonly paired with:
    
    - SQS (fan-out pattern)
    - Lambda
    - EventBridge
    
- **Security & Access Control**  
    Integrated with AWS IAM for fine-grained permissions and encryption.

---
### `Usage Basics`

- Create a **topic**.
    
- Publishers send messages to the topic.
    
- Subscribers receive a copy of each message.
    
- Message delivery is push-based rather than polled.
    
- Optional message filtering controls which subscribers receive which messages.

---
### `Challenges`

- **No Message Replay**  
    Messages are delivered once and not retained for later consumption.
    
- **Limited Ordering Guarantees**  
    FIFO topics exist but with stricter limits.
    
- **Not a Queue**  
    Cannot be used for work distribution or job processing.
    
- **AWS Lock-In**  
    Tightly coupled to the AWS platform.

---
### `Connected Notes`

- [[Message Brokers]]