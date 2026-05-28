
A **load balancer** distributes incoming network requests across multiple servers to prevent any single server from becoming overloaded. It enables applications to handle traffic efficiently while maintaining availability and reliability.

---
### `How It Works`

Incoming requests are received at a single entry point and routed to backend servers based on predefined routing logic.  

The selection of a target server depends on factors such as current load, server health, or distribution strategy, ensuring traffic is spread across available resources.

This routing happens transparently as requests flow through the system.

---
### `Why It Exists`

- To prevent **overloading individual servers**
    
- To improve **availability and fault tolerance**
    
- To enable **horizontal scalability**
    
- To maintain consistent performance under varying traffic levels

---
### `Connected Notes`

- [[Production Deployment Components]]