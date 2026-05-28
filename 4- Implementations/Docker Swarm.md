
Docker Swarm is a **container orchestration platform built into Docker** that allows multiple Docker hosts to be managed as a single cluster. It enables the deployment, scaling, and management of containerized applications across multiple machines while maintaining the simplicity of the Docker ecosystem.

---
### `Key Capabilities`

- Orchestrates containers across **multiple Docker nodes**
- Provides **built-in clustering and scheduling**
- Supports **service scaling and replication**
- Enables **service discovery and internal load balancing**
- Maintains **high availability** by redistributing containers if nodes fail
- Uses **declarative service definitions**
- Integrates directly with the **Docker CLI and ecosystem**

---
### `Usage Basics`

**Basic workflow:**

1. Initialize a swarm cluster
    
2. Add worker nodes to the cluster
    
3. Deploy services to the swarm
    
4. Docker manages container placement and scaling

**Initialize a swarm:**

```bash
docker swarm init
```

**Deploy a service:**

```bash
docker service create --name web -p 80:80 nginx
```

**Scale the service:**

```bash
docker service scale web=3
```

---
### `Challenges`

- Smaller ecosystem compared to Kubernetes
- Limited advanced orchestration features
- Declining adoption in favor of Kubernetes
- Fewer community tools and integrations
- Less flexibility for large-scale distributed systems

---
### `Connected Notes`

- [[Container Orchestrators]]