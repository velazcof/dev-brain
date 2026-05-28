
Container orchestrators are **software systems used to automate the deployment, scheduling, scaling, networking, and lifecycle management of containers across multiple machines**.

They coordinate containerized workloads in distributed environments, making it possible to run applications reliably across clusters rather than managing individual containers manually.

---
### `Key Ideas`

- Operate at the **multi-host or cluster level**, unlike container platforms that primarily manage containers on a single host
- Automate **container scheduling** onto available machines
- Manage **scaling, failover, and self-healing** of containerized workloads
- Provide abstractions for **service discovery, networking, and load balancing**
- Commonly use **declarative configuration** to define desired application state
- Depend on **container runtimes** underneath to actually execute containers
- Are foundational to **cloud-native and large-scale distributed application deployment**

---
### `Use Cases`

- Running **containerized applications across clusters**
- Managing **high-availability production deployments**
- Automatically scaling services based on demand
- Performing **rolling updates and rollbacks**
- Coordinating **microservices architectures**
- Simplifying distributed container management in **cloud and enterprise environments**

---
### `Connected Notes`

- [[Containers]]
- [[Kubernetes]]
- [[Docker Swarm]]
- [[Nomad]]