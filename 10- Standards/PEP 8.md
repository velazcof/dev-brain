
**PEP 8 (Python Enhancement Proposal 8)** is the **official style guide** for writing **idiomatic, readable Python code**. It defines conventions for **layout, naming, imports, whitespace, and formatting**, ensuring that Python code across projects maintains a consistent and predictable structure.

---
### `Purpose`

PEP 8 exists to promote **code readability**, one of Python’s core design values.

Its goals are to:

- Ensure Python code is **easy to read and understand** across teams and projects.
- Reduce cognitive overhead by establishing **consistent naming, spacing, and layout** rules.
- Minimize stylistic debate and fragmentation by providing a **single authoritative standard**.
- Improve maintainability and tooling compatibility (linters, formatters, IDEs).

In practice, PEP 8 acts as a **shared contract** that keeps Python codebases clean, expressive, and predictable.

---
### `Structure`

PEP 8 is organized around key style conventions, including:

- **Code Layout**
    - Maximum line length (`79` chars for code, `72` for docstrings).
    - Indentation via **4 spaces**, never tabs.
    - Blank line rules for separating classes, functions, and sections of logic.
    
- **Naming Conventions**
    - `snake_case` for functions and variables.
    - `PascalCase` for classes.
    - `UPPER_CASE` for constants.
    - Rules for private/internal names (`_leading_underscore`).
    
- **Imports**
    - One import per line; grouped as **standard library → third party → local**.
    - Avoid wildcard (`*`) imports.
    
- **Whitespace Rules**
    - No extraneous spaces around parentheses, before commas, or around `=` in keyword arguments.
    - Spaces around operators to improve clarity.
    
- **Programming Recommendations**
    - Prefer explicit over implicit expressions.
    - Avoid unnecessary complexity.
    - Use `is`/`is not` for identity checks; avoid comparing directly to `True`/`False`.

---
### `Connected Notes`

- [[Python Standards]]