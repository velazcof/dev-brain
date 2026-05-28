
**CI/CD Pipelines** are **automated workflows** that connect Continuous Integration (CI) and Continuous Delivery (CD) processes, enabling teams to build, test, and deploy software automatically. They ensure code changes move through a consistent, repeatable sequence from development to production with minimal manual intervention.

![[CI-CD Pipeline.png]]
![[CI-CD Responsibilities.png]]

---
### `Key Capabilities`

- **Automated builds and tests** → Every commit triggers validation to detect issues early.
    
- **Deployment automation** → Code is deployed to staging or production environments using predefined scripts or configurations.
    
- **Parallel and conditional stages** → Pipelines can run different steps (e.g., tests, linting, deployments) in parallel or only when conditions are met.
    
- **Integration with IaC and monitoring** → Ties into Infrastructure as Code (IaC) for environment setup and observability tools for feedback loops.
    
- **Rollback and recovery** → Pipelines can automatically revert failed deployments to maintain stability.

---
### `Usage Basics`

- Define pipeline stages in a configuration file (e.g., `.yaml`, `.yml`, or `.json`).
    
- Integrate with a version control system (e.g., GitHub, GitLab, Bitbucket).
    
- Tools like **GitHub Actions**, **GitLab CI**, **Jenkins**, **Azure DevOps**, and **CircleCI** run the pipeline automatically on commits or merges.

**Example**:

```yaml
stages:
  - build
  - test
  - deploy

build:
  script: npm install

test:
  script: npm test

deploy:
  script: npm run deploy
  when: manual
```

---
### `Challenges`

- **Pipeline complexity** → Large pipelines with many dependencies can be hard to maintain.
    
- **Flaky tests** → Unstable tests break automation reliability.
    
- **Infrastructure drift** → Mismatch between environments can cause failures despite automation.
    
- **Security and secrets management** → Pipelines must handle credentials safely during automated deployments.

---
### `Connected Notes`

- [[Infrastructure as Code (IaC)]]
- [[Continuous Integration (CI)]]
- [[Continuous Delivery (CD)]]
- [[DevOps]]

