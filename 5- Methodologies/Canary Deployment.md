
A Canary Deployment is a deployment strategy where the **new application version is gradually exposed to a small subset of users before wider rollout occurs**.

Traffic is incrementally shifted to the new version while monitoring system behavior and stability.

---
### `Key Ideas`

- **Gradual traffic exposure**  
    A small percentage of users or requests are routed to the new application version initially.

- **Progressive rollout process**  
    If the new version performs reliably, traffic allocation gradually increases until the rollout completes.

- **Risk reduction through observation**  
    Canary deployments allow teams to detect issues in production environments before affecting the entire user base.

- **Version coexistence**  
    Old and new application versions run simultaneously during deployment while traffic distribution is controlled dynamically.

---
### `Pros & Cons`

- **Advantages**  
    Reduces deployment risk, enables real-world validation under production traffic, and limits the impact of potential failures.

- **Disadvantages**  
    Requires more advanced traffic routing, monitoring, and operational coordination compared to simpler deployment strategies.

- **Trade-offs**  
    Improves deployment safety and observability at the cost of increased infrastructure and operational complexity.

---
### `Connected Notes`

- [[Deployment Strategies]]