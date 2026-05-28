
**Function as a Service (FaaS)** is a **cloud service model** that allows developers to run **individual functions** in response to events, without managing servers, operating systems, or scaling infrastructure.

It forms the **core compute layer of serverless architectures**, executing small, stateless functions on demand.

---
### `Key Ideas`

- **Event-Driven:**  
    Functions trigger automatically on specific events — HTTP requests, queue messages, file uploads, database updates, or scheduled timers.
    
- **Fully Managed Compute:**  
    The provider handles provisioning, scaling, and availability. Developers only upload code and define triggers.
    
- **Stateless & Ephemeral:**  
    Each function runs in isolation and terminates after execution. Persistent state must live in external storage.
    
- **Granular Billing:**  
    You pay only for execution time and resources consumed per request (e.g., milliseconds and memory usage).
    
- **Scalability:**  
    Automatically scales horizontally to meet incoming request volume, then scales to zero when idle.
    
- **Examples:**
    
    - AWS Lambda
    - Azure Functions
    - Google Cloud Functions
    - Cloudflare Workers
    - Firebase Cloud Functions

---
### `Use Cases`

- Lightweight REST or GraphQL APIs.
    
- Event-driven workflows (e.g., image resizing, email sending).
    
- CRON or scheduled automation.
    
- Data pipelines or webhooks.
    
- Integration glue between cloud services (e.g., Firestore → Function → Storage).

---
### `Connected Notes`

- [[Serverless Computing]]
- [[Platform-as-a-Service (PaaS)]]
- [[AWS Lambda]]
- [[Google Cloud Functions]] 
- [[Azure Functions]]  
- [[Cloudflare Workers]]