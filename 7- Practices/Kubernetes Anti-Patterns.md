
### `Definition`

Kubernetes **anti**-**patterns** are implementation approaches and operational decisions that appear effective initially but introduce instability, operational complexity, scalability issues, or maintainability problems within Kubernetes environments.

Avoiding anti-patterns improves reliability, deployment consistency, and long-term maintainability of containerized systems.

---
### `Key Ideas`

- **Configuration separation**  
    Container images should remain environment-agnostic. Hardcoding configuration, secrets, or environment-specific values into images reduces portability and increases deployment risk.

- **Deployment lifecycle isolation**  
    Infrastructure and application deployment operate at different change frequencies. Separating deployment pipelines improves efficiency and reduces unnecessary infrastructure operations.

- **Resilience-first architecture**  
    Distributed systems experience delays and failures naturally. Kubernetes workloads should tolerate dependency failures rather than relying on fixed startup ordering assumptions.

- **Resource governance**  
    CPU and memory constraints prevent workloads from monopolizing cluster resources and improve cluster stability.

- **Immutable deployments**  
    Production environments should use explicit versioned container images rather than mutable identifiers like `latest`, improving reproducibility and rollback safety.

- **Environment isolation**  
    Production and non-production workloads benefit from separation to reduce security risks and operational complexity.

- **Declarative operations**  
    Direct cluster modifications create configuration drift. Cluster changes should flow through version-controlled deployment processes.

- **Operational health visibility**  
    Health probes allow Kubernetes to detect failures and make automated recovery decisions.

- **Centralized secret management**  
    Secrets should remain external to container images and use consistent handling mechanisms across environments.

- **Controller-driven workloads**  
    Production workloads should rely on Kubernetes controllers such as Deployments or StatefulSets rather than unmanaged pods.

---
### `Common Anti-Patterns`

- Baking configuration directly into container images
- Combining infrastructure and application deployment pipelines
- Depending on fixed deployment ordering
- Omitting CPU and memory limits
- Using `latest` container image tags in production
- Mixing production and non-production workloads
- Using ad-hoc cluster changes (`kubectl edit`, manual patches)
- Missing readiness and liveness probes
- Hardcoding secrets
- Running unmanaged pods directly in production

---
### `Connected Notes`

- [[Kubernetes]]