
A **compiler** is a software tool that **translates source code written in a high-level language into a lower-level form**, such as machine code, bytecode, or another language. Compilation allows programs to run efficiently and independently of the original source.

---
### `Key Ideas`

- **Translation Pipeline:**  
    A compiler processes code through multiple stages—lexing, parsing, semantic analysis, optimization, and code generation.
    
- **Error Detection:**  
    Compilers catch syntax and type errors before runtime, improving program reliability.
    
- **Optimizations:**  
    Can transform code to run faster or use fewer resources (loop unrolling, inlining, dead code elimination, etc.).
    
- **Multiple Output Types:**
    
    - Native machine code (C, C++)
    - Bytecode (Java, C#, Python .pyc)
    - Transpiled code (TypeScript → JavaScript)
    
- **Separate from Execution:**  
    Unlike interpreters, compilers produce artifacts that can run later without the compiler.

---
### `Use Cases`

- Building high-performance native applications
- Producing portable bytecode for VM-based languages
- Transpiling from one language to another
- Enforcing static correctness before execution
- Generating optimized code for specific CPU architectures

---
### `Connected Notes`

- [[Compiled Languages]]