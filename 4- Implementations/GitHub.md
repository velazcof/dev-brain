
**GitHub** is a cloud-based platform that hosts Git repositories and provides collaboration tools such as pull requests, code reviews, issue tracking, and CI/CD integration. It’s used to share, manage, and deploy software projects.

---
### `Key Capabilities`

- **Remote Git Hosting:**  
    Stores and synchronizes Git repositories for teams and individuals.
    
- **Pull Requests & Code Review:**  
    Structured workflow for proposing changes, reviewing code, and merging safely.
    
- **Issue Tracking & Project Boards:**  
    Manage bugs, features, and tasks alongside code.
    
- **CI/CD via GitHub Actions:**  
    Automate testing, builds, and deployments directly from the repository.
    
- **Access Control & Collaboration:**  
    Teams, permissions, reviews, and protected branches.
    
- **Community & Discovery:**  
    Open-source collaboration, forking, and social coding features.

---
### `Usage Basics`

```git
git remote add origin <repo-url>  # link local repo to GitHub 
git push -u origin main           # push first commit
```

**Common web actions:**

- Create a repository
    
- Open a pull request
    
- Review & merge changes
    
- Configure GitHub Actions workflows

---
### `Challenges`

- **Not Git Itself:**  
    GitHub depends on Git—confusion between the two is common.
    
- **Workflow Complexity:**  
    Large teams need clear branching and review policies.
    
- **CI/CD Setup Overhead:**  
    Actions are powerful but require YAML configuration and maintenance.
    
- **Vendor Lock-In (Potential):**  
    Tight integration can make migration non-trivial.

---
### `Connected Notes`

- [[Git]]
- [[Pull Request]]