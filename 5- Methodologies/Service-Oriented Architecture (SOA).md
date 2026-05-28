
**Service-Oriented Architecture (SOA)** is an architectural pattern where applications are built from **independently deployed, network-accessible services**, each responsible for a specific business capability. 

Services communicate through standardized protocols (often HTTP or messaging).

---
### `Key Ideas`

- **Independently Deployable Services:**  
    Each service runs on its own and can be updated without affecting the whole system.  
    _Useful for large enterprises with teams owning distinct business domains._
    
- **Business-Centric Boundaries:**  
    Services represent real business capabilities (e.g., credit check, payments).  
    _Aligns architecture with organizational structure._
    
- **Standardized Communication:**  
    Services communicate through APIs, messaging, or service buses.  
    _Promotes interoperability across tech stacks._
    
- **Loose Coupling Across the Network:**  
    Services depend on contracts, not internal implementations.  
    _Enables teams to work independently._
    
- **Reusability Across Multiple Applications:**  
    A service can support multiple products or channels.  
    _Example: authentication or payment services reused across applications._
    
- **Foundation for Distributed Systems:**  
    SOA enables systems composed of multiple services running on different machines.  
    _Often used before microservices became mainstream._

---
### `Challenges`

- Network latency and reliability issues need mitigation.
    
- Service orchestration and coordination can become complex.
    
- Requires strong governance, versioning, and contract management.
    
- Risk of creating a “distributed monolith” if services are too interdependent.
    
- Testing end-to-end flows becomes harder in distributed environments.

---
### `Connected Notes`

- [[Architectural Patterns]]
- [[Service]]