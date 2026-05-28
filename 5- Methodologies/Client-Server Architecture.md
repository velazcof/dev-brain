
**Client-Server Architecture** is a design pattern where applications are divided into **clients**, which request resources or services, and **servers**, which provide them.  
Clients initiate communication; servers process requests and return results.

---
### `Key Ideas`

- **Clear Role Separation:**
    
    - **Client:** Initiates requests, handles UI or user commands.
        
    - **Server:** Provides data, computation, or services.  
        _Simple and intuitive communication model._
    
- **Centralized Resource Management:**  
    The server stores data and handles computation, while clients remain lightweight.  
    _Common in early web and desktop applications._
    
- **Scalable Server-Side:**  
    Multiple clients can connect to the same server.  
    _Server can be scaled vertically or horizontally._
    
- **Foundational Pattern:**  
    Almost all modern architectures (REST APIs, microservices, databases) build upon client-server concepts.
    
- **Used in Many Contexts:**  
    Web browsers → web servers  
    Mobile apps → backend APIs  
    Desktop apps → corporate servers

---
### `Challenges`

- Server becomes a bottleneck under heavy load.
    
- Single point of failure unless redundancy is added.
    
- Clients may depend heavily on server availability and performance.
    
- Distributed deployments require session, state, and load-balancing strategies.
    
- Centralization causes scalability limitations without proper architecture.

---
### `Connected Notes`

- [[Architectural Patterns]]
