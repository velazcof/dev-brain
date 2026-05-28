
**Chaos Engineering** is a **methodology** for improving system resilience by **intentionally introducing controlled failures** into a system to observe how it behaves under stress.

The goal is to **build confidence** that the system can withstand real-world failures.

---
### `Key Ideas`

- **Failure Is Inevitable**  
    Modern distributed systems will fail in unpredictable ways; chaos engineering treats failure as a **normal operating condition**, not an exception.
    
- **Hypothesis-Driven Experiments**  
    Experiments start with a hypothesis about steady-state behavior (e.g. latency, error rate) and test whether it holds during failure.
    
- **Controlled Blast Radius**  
    Failures are introduced gradually and safely to avoid large-scale outages.
    
- **Production-Focused**  
    Experiments are often run in **production or production-like environments**, where real behavior emerges.
    
- **Validates Resilience Patterns**  
    Confirms whether patterns like:
    
    - Retry
    - Circuit Breaker
    - Bulkhead  
        actually work as intended under stress.

---
### `Use Cases`

- Testing system behavior during service outages
    
- Validating fault tolerance in microservices and cloud systems
    
- Discovering hidden dependencies and single points of failure
    
- Improving incident response and operational confidence
    
- Hardening systems against unpredictable real-world failures

---
### `Connected Notes`

- [[Design for Failure]]