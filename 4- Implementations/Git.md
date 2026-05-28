
**Git** is a **distributed version control system** used to track changes in code, collaborate with others, and manage multiple versions of a project. It’s the industry standard for source control, from solo projects to large teams.

---
### `Key Capabilities`

- **Distributed Version Control:**  
    Every developer has a full copy of the repository and its history.
    
- **Branching & Merging:**  
    Lightweight branches make parallel work and experimentation easy.
    
- **Change History & Auditing:**  
    Detailed commit logs help understand and review changes over time.
    
- **Collaboration at Scale:**  
    Works seamlessly with remote repositories and team workflows.
    
- **Foundation for Modern Dev Practices:**  
    Enables CI/CD, code reviews, and structured release processes.

---
### `Usage Basics`

```git
git init                  # initialize a repo 
git clone <repo-url>      # copy a remote repo 
git status                # check working tree state 
git add .                 # stage changes 
git commit -m "message"   # commit changes 
git pull                  # fetch + merge remote changes 
git push                  # send commits to remote
```

---
### `Challenges`

- **Steep Learning Curve:**  
    Concepts like branching, rebasing, and detached HEAD can be confusing.
    
- **Merge Conflicts:**  
    Conflicts require manual resolution and good team practices.
    
- **History Rewriting Risks:**  
    Commands like `rebase` and `reset --hard` can cause data loss if misused.
    
- **Workflow Discipline Required:**  
    Poor branching or commit hygiene leads to messy repositories.

---
### `Connected Notes`

- [[Version Control System (VCS)]]
- [[Git Workflows]]
- [[GitHub]]