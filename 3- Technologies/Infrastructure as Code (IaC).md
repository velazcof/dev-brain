### `Definition`

**Infrastructure as Code (IaC)** is the practice of **managing and provisioning infrastructure through machine-readable configuration files** instead of manual processes. It treats servers, networks, and environments as **programmable resources**, allowing teams to automate setup, scaling, and maintenance with consistency and speed.

---
### `Key Ideas`

- **Declarative and versioned** → Infrastructure is defined as code (e.g., YAML, JSON, HCL) and stored in version control systems like Git, ensuring traceability and reproducibility.
    
- **Automation and consistency** → Environments can be created, destroyed, or replicated automatically — eliminating configuration drift and human error.
    
- **Containers as infrastructure units** → Container images represent executable, pre-configured environments that can be quickly deployed or replaced.
    
- **Ephemeral infrastructure** → Systems are treated as disposable — when something fails, it’s rebuilt from code rather than manually fixed (“cattle, not pets”).
    
- **Immutable design** → Instead of patching live systems, changes are applied to the base configuration or image and redeployed cleanly.
    
- **Tooling ecosystem** → Popular IaC tools include Terraform, Ansible, CloudFormation, and Pulumi.

---
### `Use Cases`

- **Automated environment setup** for development, testing, and production.
- **Cloud provisioning** — defining and managing servers, storage, and networking declaratively.
- **Disaster recovery** — quickly rebuilding systems from version-controlled configurations.
- **Scalable CI/CD pipelines** — spinning up environments on demand and tearing them down after testing.

---
### `Connected Notes`

- [[Infrastructure]]
- [[Containers]]
- [[CI-CD Pipelines]]