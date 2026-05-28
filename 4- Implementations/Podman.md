
Podman is a **container platform** that allows developers to build, run, and manage containers and container images. It is designed as a **daemonless alternative to Docker**, enabling containers to run directly as processes on the host system.

Podman is commonly used in **Linux and enterprise environments**, particularly within the Red Hat ecosystem, and supports running containers in **rootless mode for improved security**.

---
### `Key Capabilities`

- Runs containers **without requiring a central daemon**
    
- Supports **rootless container execution**
    
- Compatible with **Docker container images and registries**
    
- Provides CLI commands largely **compatible with the Docker CLI**
    
- Supports **container image building**
    
- Integrates with **Kubernetes workflows**
    
- Manages container lifecycle operations (create, start, stop, remove)

---
### `Usage Basics`

**Basic workflow:**

1. Pull or build a container image
2. Run the container using Podman
3. Manage the container lifecycle through CLI commands

**Pull an image:**

```bash
podman pull nginx
```

**Run a container:**

```bash
podman run -d -p 8080:80 nginx
```

**List running containers:**

```bash
podman ps
```

---
### `Challenges`

- Smaller ecosystem compared to Docker
- Some Docker-specific tooling may not be fully compatible
- Requires familiarity with **Linux container environments**
- Enterprise-focused documentation can make onboarding harder
- Certain workflows still assume Docker in CI/CD pipelines

---
### `Connected Notes`

- [[Container Platforms]]