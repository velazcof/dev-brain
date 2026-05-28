
A Kubernetes Pod is a mechanism for **grouping and running one or more containers as a single execution unit within a cluster**. It acts as the smallest deployable unit in Kubernetes.

---
### `How It Works`

- **Container grouping**  
    A pod encapsulates one or more containers that are always scheduled and executed together on the same node.

- **Shared resources**  
    Containers within a pod share networking and storage resources, including the same IP address, port space, and attached volumes.

- **Cluster execution model**  
    Pods are created and managed by higher-level Kubernetes resources such as deployments, while the scheduler determines which node should run them.

- **Ephemeral lifecycle**  
    Pods are designed to be temporary and replaceable, allowing Kubernetes to recreate or reschedule them dynamically when failures occur.

---
### `Why It Exists`

- **Unified execution unit**  
    Pods allow tightly coupled containers to operate as a single logical application unit with shared lifecycle and resources.

- **Simplified orchestration**  
    By abstracting containers into pods, Kubernetes can manage scheduling, scaling, networking, and recovery more consistently across the cluster.

- **Distributed application support**  
    Pods provide the foundational execution model used by Kubernetes to run scalable and distributed workloads.

---
### `Connected Notes`

- [[Workload Management]]