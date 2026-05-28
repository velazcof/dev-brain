
A Blue/Green Deployment is a deployment strategy where **two separate production environments exist simultaneously**, with traffic switching from the current version to the new version once the new environment is validated.

One environment serves live traffic while the other hosts the new release candidate.

---
### `Key Ideas`

- **Dual-environment architecture**  
    Two independent environments are maintained:
    - the current live version (`Blue`)
    - the new version (`Green`)

- **Traffic switching**  
    Once the new environment is validated, traffic is redirected from the old environment to the new one.

- **Fast rollback capability**  
    If problems occur after deployment, traffic can quickly switch back to the previous environment.

- **Environment isolation**  
    Old and new application versions operate independently, reducing interference during deployment.

---
### `Pros & Cons`

- **Advantages**  
    Enables near-zero downtime deployments, rapid rollback, and safer production validation before traffic transition.

- **Disadvantages**  
    Requires duplicate infrastructure capacity since two environments must exist simultaneously.

- **Trade-offs**  
    Improves deployment safety and rollback speed at the cost of higher infrastructure complexity and resource usage.

---
### `Connected Notes`

- [[Deployment Strategies]]