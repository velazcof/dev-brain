
Cluster & Scheduling refers to the systems and mechanisms responsible for **organizing cluster resources and determining where workloads execute within a Kubernetes environment**. 

It governs how nodes are coordinated, how workloads are assigned to infrastructure, and how cluster-wide operations are managed.

---
### `Key Ideas`

- **Cluster organization**  
    Kubernetes operates as a cluster of nodes working together as a unified system for running distributed workloads.

- **Workload placement**  
    The scheduler determines which nodes should run workloads based on resource availability, constraints, and policies.

- **Resource coordination**  
    Cluster-level components manage communication, orchestration, and state management across the environment.

- **Execution abstraction**  
    Kubernetes abstracts the underlying infrastructure, allowing workloads to be scheduled and managed without directly interacting with individual machines.

---
### `Connected Notes`

- [[Kubernetes]]
- [[Kubernetes Node]]
- [[Kubernetes Scheduler]]
- [[Kubernetes Namespace]]
- [[Kubernetes Control Plane]]