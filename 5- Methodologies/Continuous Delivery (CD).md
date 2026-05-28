
**Continuous Delivery (CD)** is a **software delivery methodology** that builds upon Continuous Integration (CI) by automating the process of **deploying code to production-like environments** once it passes all quality checks.  

Its goal is to ensure that software is **always in a deployable state**, allowing releases to happen frequently, safely, and predictably.

---
### `Key Ideas`

- **Build quality in** → Each change passes through automated tests, code reviews, and CI/CD pipelines to maintain a stable release candidate.
    
- **Work in small batches** → Smaller, incremental updates reduce complexity, testing time, and deployment risk.
    
- **Automate repetitive tasks** → Automation handles builds, tests, deployments, and environment setup — freeing developers to focus on problem-solving.
    
- **Continuous improvement** → Teams measure lead time, deployment frequency, and failure recovery to refine processes continuously.
    
- **Shared responsibility** → Everyone on the team owns delivery quality — if the build breaks, the team fixes it together.
    
- **Continuous Deployment (not the same)** → Continuous _Deployment_ means automatically releasing to production after every successful pipeline run, while Continuous _Delivery_ keeps releases ready but triggered manually.


---
### `Challenges`

- **Cultural alignment** → Requires trust, collaboration, and a DevOps mindset; without it, automation alone won’t improve delivery.
    
- **Pipeline complexity** → Maintaining reliable pipelines across multiple environments and dependencies can be difficult.
    
- **Testing bottlenecks** → Slow or unreliable automated tests delay delivery cycles.
    
- **Environment parity** → “Production-like” environments must closely mirror actual production to avoid deployment surprises.


---
### `Connected Notes`

- [[Continuous Integration (CI)]]
- [[CI-CD Pipelines]]
