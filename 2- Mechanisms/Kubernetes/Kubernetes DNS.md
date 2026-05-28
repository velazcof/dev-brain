
Kubernetes DNS is a mechanism responsible for **providing service discovery and name resolution within a Kubernetes cluster**.

It allows workloads to communicate using stable service names rather than requiring direct knowledge of pod IP addresses or infrastructure details.

---
### `How It Works`

- **Automatic service naming**  
    Kubernetes assigns DNS names to services, allowing workloads to reference resources using predictable names instead of network addresses.

- **Name resolution**  
    When a workload requests a service name, the cluster DNS system resolves that name into the appropriate network endpoint.

- **Pod lifecycle abstraction**  
    Since pods are frequently created, replaced, or moved, DNS provides a stable communication layer independent of changing infrastructure.

- **Cluster-wide communication support**  
    Internal workloads use Kubernetes DNS to discover and communicate with services throughout the cluster.

---
### `Why It Exists`

- **Reliable service discovery**  
    Distributed systems require stable mechanisms for locating workloads without depending on constantly changing infrastructure details.

- **Reduced infrastructure coupling**  
    Applications communicate through logical names rather than hardcoded addresses.

- **Scalable cluster networking**  
    DNS enables Kubernetes workloads to remain portable and resilient as infrastructure evolves.

---
### `Connected Notes`

- [[Networking]]