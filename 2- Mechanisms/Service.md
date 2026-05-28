
A **service** provides a **discrete unit of functionality** that can be accessed through a well-defined interface, typically over a network. It represents a boundary around a specific capability that other components can invoke.

---
### `How It Works`

A service runs independently and listens for requests through its exposed interface.  

Clients or other services send requests using agreed-upon protocols, and the service processes those requests and returns responses.

Interaction is based on contracts that define inputs, outputs, and behavior, allowing services to operate without sharing internal implementation details.

---
### `Why It Exists`

- To encapsulate **distinct capabilities** behind clear boundaries
    
- To enable **independent deployment and scaling**
    
- To support **loose coupling** between system components
    
- To allow reuse of functionality across multiple systems
    
- To form the basis of **distributed system architectures**

---
### `Connected Notes`

- [[Service-Oriented Architecture (SOA)]]