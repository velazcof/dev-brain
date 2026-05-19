
### `Definition`

Kubernetes Architecture describes the **structural organization of a Kubernetes system**, including how its components interact to manage containerized applications across a cluster.

It defines how Kubernetes coordinates nodes, schedules workloads, and maintains the desired state of applications in a distributed environment.

---
### `Key Ideas`

- Built around a **cluster of machines (nodes)** acting as a unified system
	
- Follows a **control plane + worker node architecture**:
    - **Control Plane** → responsible for cluster management, scheduling decisions, and maintaining system state
    - **Worker Nodes** → execute workloads by running pods
	
- Uses a **declarative desired state model**:
    - Users define the desired system state (e.g., number of replicas)
    - Kubernetes continuously reconciles actual state to match it
    
- Relies on a **scheduler** to assign pods to nodes based on:
    - Available resources (CPU, memory)
    - Constraints and policies
    
- Implements a **controller-based architecture**:
    - Controllers monitor system state
    - Automatically take actions to correct deviations
    
- Provides **self-healing capabilities**:
    - Restarts failed containers
    - Reschedules pods if nodes fail
    
- Supports **horizontal scaling**:
    - Adjusts the number of pod instances dynamically
    
- Separates **workload definition from execution**:
    - Workloads are defined declaratively
    - Execution details are handled by the system
    
- Uses a centralized **API-driven model**:
    - All interactions go through the Kubernetes API
    - Components communicate through this control layer

---
### `Connected Notes`

- [[Kubernetes]]