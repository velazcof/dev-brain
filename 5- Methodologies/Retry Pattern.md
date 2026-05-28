
The **Retry Pattern** is a **design pattern** used in software systems where an operation that fails is **automatically re-attempted**, based on defined rules, in order to handle **transient or temporary failures**.

---
### `Key Ideas`

- **Designed for Transient Failures**  
    Retries are effective only when failures are likely to be **temporary**, such as network glitches, timeouts, or momentary service unavailability.
    
- **Controlled Re-Attempts**  
    Retries must be bounded using:
    
    - Maximum retry count
    - Time delays between attempts  
        Uncontrolled retries can overload systems.
    
- **Backoff Strategies**  
    Common approaches include:
    
    - Fixed delay
    - Exponential backoff
    - Exponential backoff with jitter  
        These reduce contention and cascading failures.
    
- **Not All Errors Should Be Retried**  
    Permanent failures (e.g. invalid input, authentication errors) should **fail fast** rather than retry.
    
- **Often Combined with Other Patterns**  
    Commonly paired with:
    
    - Timeouts
    - Circuit Breaker
    - Bulkhead  
        to improve overall system resilience.

---
### `Use Cases`

- Retrying failed HTTP requests to external APIs
    
- Handling temporary database connection drops
    
- Recovering from brief service outages in distributed systems
    
- Improving reliability of message processing and event handling
    
- Cloud and microservice architectures where network failures are expected

---
### `Connected Notes`

- [[Design for Failure]]