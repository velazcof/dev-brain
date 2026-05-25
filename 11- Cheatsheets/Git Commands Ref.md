### `Definition`

A practical reference for commonly used **Git commands**, explaining what each command does and how it’s typically used during development.

---
### `Structure`

##### ==`Initialize & Inspect`==

- `git init` — initialize a new Git repository
- `git version` — show installed Git version
- `git status` — show working directory and staging state
- `git log` — view commit history


##### ==`Staging & Committing`==

- `git add <file>` — stage a specific file
- `git add .` — stage all changes in current directory
- `git add -A` — stage all changes in the repo
- `git commit -m "message"` — save staged changes


##### ==`Branching & Navigation`==

- `git branch` — list branches
- `git branch <name>` — create branch
- `git branch -d <name>` — delete branch
- `git checkout <branch>` — switch branches (legacy)
- `git switch <branch>` — switch branches (modern)
- `git switch -c <branch>` — create + switch


##### ==`Merging & Comparing`==

- `git merge <branch>` — merge another branch into current
- `git diff` — show uncommitted changes
- `git diff <branch1> <branch2>` — compare branches


##### ==`Undoing Changes`==

- `git reset` — unstage changes
- `git reset --hard HEAD` — discard all uncommitted changes ⚠️
- `git revert HEAD` — undo last commit safely (creates new commit)


##### ==`Remote Repositories`==

- `git clone <url>` — copy a remote repository locally
- `git remote` — list remotes
- `git remote -v` — show remotes with URLs
- `git remote add origin <url>` — add remote
- `git remote rename origin upstream` — rename remote
- `git remote rm origin` — remove remote
- `git pull origin main` — fetch + merge from remote
- `git push origin <branch>` — push local commits


##### ==`Configuration`==
`
- `git config --global user.name "<name>"`
- `git config --global user.email "<email>"`


##### ==`Advanced / Niche`==

- `git format-patch HEAD~3` — create patch files
- `git am <patch>` — apply patch
- `git request-pull origin/main <branch>` — request merge via email
- `git send-email *.patch` — send patches by email
- `git rerere` — reuse previous conflict resolutions
- `git daemon` — expose repos via Git protocol
- `git instaweb` — launch lightweight repo browser

##### ==`GitHub CLI`==

- `gh auth login` — authenticate GitHub from terminal

---
### `Connected Notes`

- [[Git]]