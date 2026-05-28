
**Design for Failure** is a **resilience principle** in system architecture that assumes every component will eventually fail — networks will drop, servers will crash, dependencies will become unavailable — and systems should be **designed to recover gracefully**, not merely avoid failure.

---
### `Key Ideas`

- **Failure is inevitable** → The goal is resilience, not perfection.
    
- **Graceful degradation** → Systems continue operating in a reduced state instead of crashing entirely.
    
- **Isolation and recovery** → Architect services to contain faults and recover automatically when dependencies fail.
    
- **Resilience patterns** → Techniques like **Retry**, **Circuit Breaker**, **Bulkhead**, and **Chaos Engineering** model, test, and handle failure predictably.
    
- **Operational readiness** → Emphasizes monitoring, alerting, and automation to detect and mitigate failures quickly.

---
### `Connected Notes`

- [[Retry Pattern]]
- [[Circuit Breaker Pattern]]
- [[Bulkhead Pattern]]
- [[Chaos Engineering]]
- [[Software Architecture]]