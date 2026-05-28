
A reference for **Bash built-in commands** — commands that are **implemented directly by the Bash shell**, not executed as external programs.

These commands cease to exist if Bash is removed.

---
### `Structure`

##### ==`Core Built-ins`==

- `cd <dir>` — change current working directory
- `pwd` — print current working directory
- `echo <text>` — print text or variables
- `printf <fmt>` — formatted output
- `type <cmd>` — show how a command is resolved
- `history` — display command history
- `exit` — exit the current shell
- `exec <cmd>` — replace shell process with command


##### ==`Input & I/O Built-ins`==

- `read VAR` — read a line from stdin into a variable  
- `read -p "Prompt: " VAR` — prompt before reading input  
- `read -r VAR` — read raw input (disable backslash escaping)


##### ==`Environment & Context`==

- `export VAR=value` — export variable to child processes
- `set` — set shell options or list variables
- `unset VAR` — remove variable or function
- `umask` — show or set default file permission mask


##### ==`Aliases & Sourcing`==

- `alias name='cmd'` — define alias
- `unalias name` — remove alias
- `source <file>` / `. <file>` — execute file in current shell


##### ==`Job Control`==

- `jobs` — list background jobs
- `fg` — bring job to foreground
- `bg` — resume job in background
- `disown` — remove job from shell job table

---
### `Connected Notes`

- [[bash]]