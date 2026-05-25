
### `Definition`

A **compiled language** follows an execution mechanism in which source code is **translated into machine code before execution**, producing a standalone binary that can run directly on the target system.

This mechanism separates translation from runtime execution.

---
### `How It Works`

Source code is processed ahead of time by a compilation step that analyzes, transforms, and translates the program into machine-level instructions. The resulting executable is then loaded and run by the operating system without requiring further translation during execution.

Any change to the source code requires repeating the compilation step.

---
### `Why It Exists`

- To enable **efficient, direct execution** on hardware
- To allow **ahead-of-time optimization** of program behavior
- To reduce runtime overhead by shifting work to the translation phase
- To support **predictable performance characteristics**

---
### `Connected Notes`

- [[High-level Languages]]
- [[Compiler]]
- [[Build Tools]]