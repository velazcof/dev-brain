
containerd is a **container runtime** that manages the lifecycle of containers and container images on a host system. It provides the low-level functionality required to run containers, including image management, container execution, and resource isolation.

Originally developed as part of Docker and later extracted as a standalone project, containerd is widely used as the **container runtime layer in modern container orchestration systems**.

---
### `Key Capabilities`

- Executes containers using **container images**
    
- Manages the **container lifecycle** (create, start, stop, delete)
    
- Handles **container image storage and distribution**
    
- Interfaces with operating system mechanisms for **process isolation and resource control**
    
- Provides APIs used by higher-level platforms and orchestration systems
    
- Designed to be **lightweight and production-focused**
    
- Commonly used as the runtime layer in **container orchestration platforms**

---
### `Usage Basics`

Basic workflow typically involves interacting with containerd through CLI tools such as `ctr`.

**Pull a container image:**

```bash
ctr image pull docker.io/library/nginx:latest
```

**Run a container:**

```bash
ctr run -t docker.io/library/nginx:latest my-container
```

**List running containers:**

```bash
ctr containers list
```

---
### `Challenges`

- Lower-level tool compared to full container platforms
    
- CLI tooling (`ctr`) is less user-friendly than higher-level platforms
    
- Often intended to be used **indirectly through container platforms or orchestrators**
    
- Requires deeper understanding of container infrastructure
    
- Fewer developer-oriented workflows compared to Docker

---
### `Connected Notes`

- [[Container Runtime]]