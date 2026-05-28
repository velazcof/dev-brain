
### `Definition`

A Recreate Deployment is a deployment strategy where the **current application version is completely shut down before the new version is deployed**. Only one version of the application exists at a time during the deployment process.

---
### `Key Ideas`

- **Full application replacement**  
    The existing deployment is terminated entirely before the new version starts running.

- **Sequential deployment flow**  
    The deployment process follows a simple sequence:
    1. Stop the current version
    2. Deploy the new version
    3. Restore application availability

- **Single active environment**  
    Old and new versions never coexist, avoiding compatibility conflicts between application versions.

- **Simple operational model**  
    Recreate deployments are straightforward to configure and understand compared to more advanced rollout strategies.

---
### `Pros & Cons`

- **Advantages**  
    Simple setup, predictable behavior, and complete version replacement reduce orchestration complexity.

- **Disadvantages**  
    Temporary downtime occurs during deployment because the application becomes unavailable between shutdown and redeployment.

- **Trade-offs**  
    Best suited for systems where short downtime is acceptable or where multiple versions cannot safely operate simultaneously.

---
### `Connected Notes`

- [[Deployment Strategies]]