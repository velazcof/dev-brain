
### `Definition`

Workload Management refers to the processes and mechanisms responsible for **deploying, running, scaling, and maintaining application workloads within a system**. In Kubernetes, it encompasses the components that control how containers and pods are created, replicated, updated, and executed across a cluster.

---
### `Key Ideas`

- **Application execution management**  
    Workload management handles the lifecycle of application workloads, including creation, scheduling, scaling, replacement, and termination.

- **Declarative workload control**  
    Kubernetes defines workloads through desired state declarations, allowing the system to automatically maintain and reconcile application state over time.

- **Abstraction over containers**  
    Instead of managing individual containers directly, Kubernetes uses higher-level workload objects such as pods and deployments to coordinate execution.

- **Reliability and scalability**  
    Workload management mechanisms help maintain availability, distribute workloads across nodes, and support scaling and rolling updates.

---
### `Table`

| Type        | Behaviour                    | Use case                      |
| ----------- | ---------------------------- | ----------------------------- |
| Pod         | Runs container               | Testing / base unit           |
| Deployment  | Keeps stateless apps running | APIs, web apps                |
| ReplicaSet  | Maintains replica count      | Internal (don’t use directly) |
| StatefulSet | Runs stateful apps           | DBs, Kafka                    |
| DaemonSet   | Runs everywhere              | Logging/monitoring            |
| Job         | Runs once                    | Scripts, batch tasks          |

---
### `Connected Notes`

- [[Kubernetes]]
- [[Kubernetes Pod]]
- [[Kubernetes Deployment]]
- [[Kubernetes ReplicaSet]]
- [[Kubernetes StatefulSet]]
- [[Kubernetes DaemonSet]]
- [[Kubernetes Job]]