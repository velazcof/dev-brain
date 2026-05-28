
A Rolling Deployment is a deployment strategy where the **new application version is gradually introduced by incrementally replacing instances of the old version over time**. 

Both versions temporarily coexist during the deployment process until the rollout completes.

---
### `Key Ideas`

- **Incremental replacement**  
    Old application instances are replaced progressively rather than shutting down the entire application at once.

- **Continuous availability**  
    Parts of the application remain operational during deployment, reducing or eliminating downtime.

- **Controlled rollout process**  
    The deployment occurs in stages, allowing the system to monitor stability while transitioning traffic to the new version.

- **Rollback support**  
    If issues are detected during rollout, the deployment can be paused or reverted before the entire system is updated.

---
### `Pros & Cons`

- **Advantages**  
    Maintains application availability during deployment, reduces deployment risk, and supports gradual rollout behavior.

- **Disadvantages**  
    Old and new versions coexist temporarily, which may introduce compatibility concerns between application versions.

- **Trade-offs**  
    More reliable than recreate deployments but operationally more complex due to staged rollout coordination.

---
### `Connected Notes`

- [[Deployment Strategies]]