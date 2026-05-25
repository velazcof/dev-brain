
### `Definition`

A quick reference for core **Docker concepts and mental models**, explaining how Docker works under the hood (images, containers, registries, layers, etc.) and how these pieces interact.

---
### `Structure`

##### ==`Core Entities`==

- **Image** — read-only template used to create containers
- **Container** — running instance of an image
- **Dockerfile** — instructions to build an image
- **Registry** — remote storage for images (e.g., Docker Hub)


##### ==`Image & Build Model`==

- `FROM` — defines base image (starting environment)
- `RUN` — executes commands during build (creates layers)
- `COPY` / `ADD` — moves files into image
- `CMD` — default command when container starts
- `ENTRYPOINT` — fixed executable for container


##### ==`Layers & Caching`==

- Each Dockerfile instruction creates a **layer**
- Layers are **immutable** and **cached**
- Rebuilding reuses unchanged layers → faster builds
- Order matters (cache invalidation happens top-down)


##### ==`Execution Model`==

- Container = **process running inside isolated environment**
- Not a VM → shares host OS kernel
- Lightweight and fast to start/stop
- Ephemeral by default (data lost unless persisted)


##### ==`Storage Concepts`==

- **Volume** — managed persistent storage (recommended)
- **Bind Mount** — link host directory to container
- Containers should be **stateless** when possible


##### ==`Networking Concepts`==

- Containers communicate via **Docker networks**
- Each container gets an internal IP
- Can reference containers by **name** on same network
- Port mapping exposes container to host (`host:container`)


##### ==`Registries & Distribution`==

- Images are pulled from **registries** (Docker Hub, ECR, etc.)
- `name:tag` → identifies image version
- Images are composed of **layer stacks**
- Push/pull enables sharing across environments


##### ==`Multi-Container Systems`==

- One container = one responsibility (best practice)
- Use **Docker Compose** to orchestrate multiple services
- Services communicate via shared network


##### ==`Key Mental Models`==

- Image = **blueprint**
- Container = **running process**
- Dockerfile = **build recipe**
- Registry = **image marketplace**
- Layers = **incremental filesystem snapshots**


##### ==`Common Pitfalls`==

- Thinking containers are full VMs → they are not
- Storing data inside containers → data loss risk
- Ignoring layer order → slow builds
- Using `latest` tag → unpredictable behavior

---
### `Connected Notes`

- [[Docker]]