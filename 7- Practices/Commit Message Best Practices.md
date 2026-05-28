
Commit message best practices exist to ensure that every code change is **clear, traceable, and meaningful**, making collaboration and version history easier to understand for both humans and automated tools.

---
### `Key Ideas`

- **Use a Clear, Concise Summary:**  
    Keep the first line under ~50 characters and describe _what_ changed.

- **Write in the Imperative Mood:**  
    ("Add feature", not "Added feature" or "Adds feature") — matches Git’s internal phrasing.

- **Provide Detailed Context in the Body:**  
    Explain _why_ the change was made, not just what changed.

- **Reference Issues or Tickets:**  
    Link related tasks (e.g., `Fixes #123`) for traceability.

- **Group Logical Changes:**  
    One commit = one meaningful change. Avoid mixing unrelated updates.

- **Avoid Meaningless Messages:**  
    (“fix”, “update”, “commit”) — they provide no insight.

- **Use Extended Descriptions for Complex Changes:**  
    Helps reviewers understand reasoning, trade-offs, and implications.

---
### `Challenges`

- **Too Vague or Short:**  
    Messages like "misc fixes" or "update" make history difficult to navigate.

- **Overly Long Summaries:**  
    Key information gets lost when the commit title becomes a paragraph.

- **Mixing Multiple Changes:**  
    Harder to review, revert, or isolate bugs later.

- **Inconsistent Styles Across Teams:**  
    Without team conventions (e.g., Conventional Commits), history becomes messy.

---
### `Connected Notes`

- [[Commit]]