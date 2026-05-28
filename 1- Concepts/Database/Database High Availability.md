
**Database High Availability** refers to the architectural design and operational strategies used to ensure that a database system remains accessible with minimal downtime. It focuses on reducing service interruptions caused by hardware failures, software crashes, or network issues.

---
### `Key Ideas`

- **Redundancy**  
    Multiple database instances or nodes are deployed to prevent single points of failure.
    
- **Failover Mechanisms**  
    When a primary instance fails, another instance can automatically or manually take over.
    
- **Replication-Based Availability**  
    Replicated data enables continuity during node failures.
    
- **Load Distribution**  
    Traffic may be distributed across nodes to reduce overload and improve resilience.
    
- **Uptime Targets**  
    Availability is often measured using service-level objectives (e.g., 99.9% uptime).
    
- **Trade-Offs**  
    Higher availability may increase system complexity and operational overhead.
    
- **Distinct from Backup**  
    High availability minimizes downtime, while backup & recovery protects against data loss.

---
### `Connected Notes`

- [[Database Operations]]