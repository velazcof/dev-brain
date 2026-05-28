
Container images are **immutable, layered packages that encapsulate an application and all the dependencies required to run it inside a container**. They act as the blueprint from which container instances are created by a container runtime.

Rather than representing a running system, a container image defines the **filesystem, runtime environment, and configuration** needed for a containerized application.

---
### `How It Works`

Container images are typically built from a sequence of instructions that produce **layered filesystem snapshots**.

Key operational ideas:

- An image is composed of **multiple read-only layers**, each representing a filesystem change
- These layers are **stacked together using a union filesystem**
- When a container is started, a **writable layer is added on top of the image**
- The container runtime uses the image as a **template to instantiate container processes**
- Images are stored and distributed through **container registries**
- Multiple containers can be created from the **same image**

This layered design allows **efficient reuse and caching of shared components** across images.

---
### `Why It Exists`

Container images solve the problem of **environment portability and reproducibility**.

Traditional deployments often suffer from inconsistencies between development, testing, and production environments. Container images address this by packaging the application together with its runtime dependencies into a **single portable artifact**.

This enables:

- consistent execution across environments
- reliable deployment artifacts
- simplified distribution of application environments
- efficient reuse of shared system layers

---
### `Connected Notes`

- [[Containers]]