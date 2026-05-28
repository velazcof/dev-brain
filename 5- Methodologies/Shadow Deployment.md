
### `Definition`

A Shadow Deployment is a deployment strategy where **production traffic is mirrored to a new application version without exposing its responses to end users**.

The new version processes real traffic in parallel with the live system, allowing behavior and performance to be evaluated safely.

---
### `Key Ideas`

- **Traffic mirroring**  
    Real production requests are duplicated and sent to the new application version while the original version continues serving users.

- **Invisible validation**  
    The shadow version operates in production conditions without affecting user-facing responses or application behavior.

- **Production environment testing**  
    Shadow deployments allow teams to observe how a new version behaves under realistic traffic patterns and workloads.

- **Parallel system execution**  
    Both application versions run simultaneously, enabling comparison of performance, stability, and operational characteristics.

---
### `Pros & Cons`

- **Advantages**  
    Enables realistic production testing with minimal user impact and helps identify scaling or performance issues before rollout.

- **Disadvantages**  
    Requires additional infrastructure resources and more advanced traffic duplication and observability systems.

- **Trade-offs**  
    Provides safer production validation at the cost of increased operational complexity and infrastructure overhead.

---
### `Connected Notes`

- [[Deployment Strategies]]