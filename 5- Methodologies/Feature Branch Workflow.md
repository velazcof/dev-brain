
The **Feature Branch Workflow** is a Git branching strategy where **each new feature or change is developed in its own dedicated branch**, separate from the main branch.  
Work is done, tested, and reviewed in isolation, then merged back once it’s ready.

---
### `Key Ideas`

- **Isolated Feature Branches**  
    Each feature, bugfix, or task gets its own branch (e.g., `feature/login-page`, `fix/cart-bug`), created from `main` or `develop`.
    
- **Clean Main Branch**  
    The `main` (or `master`) branch always represents stable, deployable code. Work-in-progress never lives directly on it.
    
- **Pull Requests / Merge Requests**  
    Changes from a feature branch are merged through a code review step (PR/MR), enabling discussion, feedback, and validation.
    
- **Short-Lived Branches**  
    Feature branches should exist only for the duration of that task, then be merged and deleted to keep history clean.
    
- **Frequent Sync with Main/Develop**  
    Regularly rebasing or merging `main` into the feature branch reduces merge conflicts later.

---
### `Challenges`

- **Long-Lived Branches**  
    If a branch stays open too long, it drifts from `main`, causing painful merge conflicts and harder reviews.
    
- **Overloaded Branches**  
    Putting multiple unrelated changes into a single feature branch makes review and rollback difficult.
    
- **Heavy PRs**  
    Huge pull requests are harder to review properly and may slow down delivery.
    
- **Coordination Overhead**  
    Teams must agree on naming conventions, review rules, and when a branch is “ready” to merge.

---
### `Connected Notes`

- [[Git Workflows]]
