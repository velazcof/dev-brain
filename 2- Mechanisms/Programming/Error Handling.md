
### `Definition`

**Error handling** is the mechanism by which a system detects, represents, propagates, and responds to abnormal or failure conditions during execution, allowing programs to recover gracefully or fail safely.

---
### `How It Works`

- **Error detection** occurs when an operation cannot complete as expected (invalid input, resource failure, logic violation).
- The system **represents the error** using a defined form (return codes, exceptions, signals, error objects).
- The error is **propagated** to a handler through the call stack or control flow.
- A handler **responds** by:
    - recovering and continuing,
    - retrying the operation,
    - logging and aborting,
    - or escalating the failure.
- Control flow is altered to prevent undefined or unsafe execution.

---
### `Why It Exists`

- To **maintain program correctness** in the presence of failure.
- To **prevent crashes, corruption, or undefined behavior**.
- To enable **graceful degradation** instead of total failure.
- To make failures **observable and diagnosable**.
- To separate **normal execution logic** from failure-handling logic.

---
### `Connected Notes`

- [[Programming Fundamentals]]