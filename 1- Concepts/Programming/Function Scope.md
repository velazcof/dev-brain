
**Function scope** defines the **visibility and lifetime of identifiers declared within a function**. It determines which variables, parameters, and nested identifiers can be accessed inside the function body and where they are hidden from the rest of the program.

---
### `Key Ideas`

- **Boundary of Visibility**  
    Identifiers declared inside a function are accessible only within that function.

- **Local vs External Access**  
    Functions can typically access:
    - their own local identifiers
    - parameters passed into them
    - identifiers from enclosing scopes (depending on language rules)

- **Lifetime Tied to Execution**  
    Identifiers in function scope usually exist only while the function is executing.

- **Encapsulation of Logic**  
    Function scope prevents accidental interference between unrelated parts of a program.

- **Foundation for Abstraction**  
    Enables functions to be treated as self-contained units of behavior.

- **Language-Defined Rules**  
    Scoping behavior varies across languages (block-scoped vs function-scoped variables).

---
### `Connected Notes`

- [[Functions]]