
The **Circuit Breaker Pattern** is a **resilience design pattern** that **prevents repeated attempts to execute an operation that is likely to fail**, by temporarily blocking requests to a failing component.

It protects systems from **cascading failures** and allows time for recovery.

---
### `Key Ideas`

- **Failure Detection and State Management**  
    The circuit breaker monitors failures and transitions between states:
    
    - **Closed** → requests flow normally
    - **Open** → requests are immediately rejected
    - **Half-Open** → limited test requests are allowed
    
- **Fail Fast Behavior**  
    When open, the system avoids waiting on timeouts or retries, reducing latency and resource exhaustion.
    
- **Automatic Recovery**  
    After a cooldown period, the breaker allows trial requests to determine if the dependency has recovered.
    
- **Protects Both Caller and Dependency**  
    Prevents overwhelming a failing service and preserves resources in the calling system.
    
- **Complements Retry Pattern**  
    Retries handle transient errors; circuit breakers stop retries when failures become persistent.

---
### `Use Cases`

- Preventing overload of failing external services
    
- Protecting microservices from cascading failures
    
- Avoiding thread pool or connection pool exhaustion
    
- Improving system responsiveness during partial outages
    
- Stabilizing distributed systems under failure conditions

---
### `Connected Notes`

- [[Design for Failure]]