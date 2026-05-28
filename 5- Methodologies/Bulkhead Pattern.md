
The **Bulkhead Pattern** is a **resilience design pattern** that **isolates components or resources** within a system so that a failure in one part **does not cascade** and bring down the entire system.

It is inspired by ship bulkheads, where compartments prevent flooding from spreading.

---
### `Key Ideas`

- **Isolation Over Sharing**  
    Resources (threads, connections, memory, queues) are **partitioned** so failures are contained within a single compartment.
    
- **Failure Containment**  
    If one component becomes overloaded or fails, only its allocated resources are affected, while the rest of the system continues to operate.
    
- **Resource-Level Separation**  
    Bulkheads can be applied to:
    
    - Thread pools
    - Connection pools
    - Queues
    - Services or subsystems
    
- **Improves System Stability**  
    Prevents total system collapse caused by localized failures or traffic spikes.
    
- **Often Used with Other Resilience Patterns**  
    Commonly combined with:
    
    - Circuit Breaker
    - Retry
    - Timeout  
        to build robust fault-tolerant systems.

---
### `Use Cases`

- Isolating critical services from non-critical ones
    
- Preventing one slow dependency from exhausting shared thread pools
    
- Separating workloads in microservices architectures
    
- Protecting high-priority operations during partial outages
    
- Improving reliability in distributed and cloud-based systems

---
### `Connected Notes`

- [[Design for Failure]]