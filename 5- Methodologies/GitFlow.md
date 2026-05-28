
**Gitflow** is a branching methodology for Git that organizes development work using long-lived branches and structured workflows. It separates feature development, releases, and hotfixes into clearly defined branch types to support teams with planned release cycles.

---
### `Key Ideas`

- **Long-Lived Branches:**  
    Two permanent branches:
    
    - `main` → always production-ready
    - `develop` → integration branch for upcoming releases
    
- **Feature Branches:**  
    Created from `develop` and merged back once completed (`feature/*`).
    
- **Release Branches:**  
    Created from `develop` to finalize a release (`release/*`), allowing stabilization and bug fixes without blocking new feature work.
    
- **Hotfix Branches:**  
    Created from `main` to fix urgent production issues (`hotfix/*`), then merged into both `main` and `develop` to keep histories aligned.
    
- **Predictable Workflow:**  
    Ideal for teams with scheduled deployments, versioning, and multiple contributors.

---
### `Challenges`

- **Heavy Process Overhead:**  
    Too many branch types can slow down small teams or fast-moving projects.
    
- **Not Ideal for Continuous Deployment:**  
    Multiple long-lived branches introduce delays between development and production.
    
- **High Merge Complexity:**  
    Frequent merging between `main`, `develop`, and release/hotfix branches can complicate history.
    
- **Overkill for Simple Projects:**  
    Small repos or solo developers often benefit more from simpler branching models.

---
### `Connected Notes`

- [[Git Workflows]]