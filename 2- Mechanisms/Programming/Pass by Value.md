
### `Definition`

**Pass by value** is a parameter-passing behavior where a function receives a **copy of the argument’s value**, rather than direct access to the original value.

---
### `How It Works`

- When a function is called, the argument’s value is **copied** into the function’s parameter.
    
- The function operates on its **own local copy**.
    
- Any modification to the parameter **does not affect** the original argument.
    
- The copied value is typically stored in the function’s stack frame.
    
- For large values, the copy operation may be optimized or abstracted by the language/runtime.

---
### `Why It Exists`

- To **isolate function behavior** and avoid unintended side effects.
    
- To make programs **easier to reason about**.
    
- To improve **safety and predictability**.
    
- To support functional and immutable programming styles.
    
- To simplify parameter semantics in many languages.

---
### `Connected Notes`

- [[Memory & References]]