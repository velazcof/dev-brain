
A Kubernetes DaemonSet is a mechanism responsible for **ensuring a pod runs on specific nodes or across every node within a cluster**.

It is commonly used for workloads that provide cluster-wide functionality rather than application-specific services.

---
### `How It Works`

- **Node-wide pod deployment**  
    A DaemonSet automatically creates a pod on nodes that match defined criteria. As new nodes join the cluster, Kubernetes schedules the pod automatically.

- **Cluster coverage management**  
    Kubernetes continuously monitors nodes and ensures the required DaemonSet pods remain present across the intended infrastructure.

- **Infrastructure workload execution**  
    DaemonSets are typically used for system-level workloads that support cluster operations rather than serving application traffic directly.

- **Automatic lifecycle handling**  
    If nodes are removed or added, Kubernetes adjusts DaemonSet pods automatically to maintain desired coverage.

---
### `Why It Exists`

- **Cluster-wide services**  
    Some workloads need to operate on every machine rather than as shared application replicas.

- **Infrastructure observability and operations**  
    Logging agents, monitoring systems, networking components, and security tools often require execution across all cluster nodes.

- **Operational consistency**  
    DaemonSets ensure infrastructure-level services remain uniformly deployed throughout the cluster.

---
### `Connected Notes`

- [[Workload Management]]