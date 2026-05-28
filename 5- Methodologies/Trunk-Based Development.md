
**Trunk-Based Development (TBD)** is a branching strategy where developers work in **small, frequent changes directly on a single main branch** (often called `trunk`). Feature work happens in very short-lived branches or directly on trunk, enabling rapid integration and continuous delivery.

---
### `Key Ideas`

- **Single Source of Truth:**  
    All developers commit to one primary branch (`main`/`trunk`), keeping the codebase unified.
    
- **Short-Lived Branches:**  
    If branches are used, they last only hours or a day or two — not weeks.
    
- **Continuous Integration:**  
    Developers merge changes into trunk multiple times per day, supported by automated tests.
    
- **Feature Flags:**  
    Incomplete or experimental work is hidden behind feature toggles instead of long-lived branches.
    
- **Fast Feedback:**  
    Frequent merges reduce merge conflict risk and make issues easier to detect early.
    
- **Ideal for CI/CD:**  
    Works extremely well with pipelines that deploy small increments continuously.

---
### `Challenges`

- **Requires Strong Test Automation:**  
    Without reliable tests, frequent merging increases breakage risk.
    
- **Demands High Team Discipline:**  
    Developers must commit small, incremental changes rather than large feature chunks.
    
- **Increases Need for Feature Flags:**  
    Feature flagging must be managed carefully to avoid clutter or technical debt.
    
- **May Feel Unnatural Initially:**  
    Teams used to Gitflow or long-lived branches often struggle with the mindset shift.

---
### `Connected Notes`

- [[Git Workflows]]