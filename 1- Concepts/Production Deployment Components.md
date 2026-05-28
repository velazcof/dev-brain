
**Production deployment components** are the core infrastructure elements required to run an application reliably in a live environment. They handle traffic routing, security, execution of application logic, data storage, and system availability for real users.

---

### `Key Ideas`

- **Infrastructure for Live Systems:**  
    These components exist specifically to support applications in the **production environment**, where stability, performance, and security are critical.
    
- **Traffic Management:**  
    Incoming user requests are distributed and routed efficiently using load balancers and proxy mechanisms to prevent overload.
    
- **Security Boundaries:**  
    Firewalls and related controls protect internal systems from unauthorized access and malicious traffic.
    
- **Tiered Responsibility:**  
    Production systems often follow an n-tier structure:
    
    - Presentation (clients)
    - Web tier
    - Application tier
    - Data tier
    
- **Execution of Business Logic:**  
    Application servers run the core logic that processes requests and interacts with data stores.
    
- **Data Persistence:**  
    Database servers manage storage, retrieval, and consistency of application data through DBMS software.
    
- **Reliability & Availability:**  
    Components are often duplicated or replicated to avoid single points of failure.
    
- **Not All Systems Need All Components:**  
    Simpler deployments may collapse roles (e.g., web + app server combined).

---

### `Connected Notes`

- [[Firewall]]
- [[Load Balancer]]
- [[Web Server]]
- [[Application Server]]
- [[Database Server]]
- [[Proxy Server]]
- [[Deployment Diagram]]