
An **Assembler** is a **program that translates assembly language** (human-readable mnemonics) **into machine code** (binary instructions that a CPU can execute). It acts as the bridge between **low-level symbolic code** and the processor’s **native instruction set**.

---
### `Key Ideas`

- **Translation Process:**  
    Each assembly statement is converted into one corresponding **machine instruction** (a one-to-one mapping).
    
- **Stages:**
    
    1. **Lexical Analysis:** Breaks code into tokens.
        
    2. **Opcode Translation:** Converts mnemonics like `ADD` or `MOV` into binary opcodes.
        
    3. **Address Resolution:** Maps symbolic labels or variables to memory addresses.
        
    4. **Output Generation:** Produces an executable or object file ready for linking.
    
- **Assembler Types:**
    
    - **One-Pass Assembler:** Translates in a single pass — faster but limited in handling forward references.
        
    - **Two-Pass Assembler:** Scans twice to resolve symbols and addresses accurately.
    
- **Output:**  
    Produces object files (`.obj`, `.o`) or binaries that can be loaded directly by the system.

---
### `Use Cases`

- Building embedded or OS-level components.
- Translating custom assembly into executables.
- Debugging or analyzing firmware code.

---
### `Connected Notes`

- [[Low-level Languages]]