
### `Definition`

**Execution Engine** is the mechanism that carries out a selected query plan by performing the actual data operations required to produce results.

It executes low-level operations such as scans, joins, filtering, and aggregation against storage and memory structures.

---
### `How It Works`

- **Receives an Execution Plan**  
    Accepts a finalized query plan produced by the planning and optimization stages.

- **Executes Physical Operators**  
    Performs operations such as table scans, index lookups, joins, sorting, and grouping.

- **Interacts with Storage and Memory**  
    Requests pages from the storage subsystem and coordinates with buffer management for data access.

- **Streams or Materializes Results**  
    Produces result sets either incrementally (streaming) or after full computation.

- **Handles Runtime Conditions**  
    Manages resource usage, temporary data structures, and intermediate results during execution.

---
### `Why It Exists`

- To transform a logical execution plan into actual data retrieval and modification operations
- To coordinate physical access to storage and memory structures
- To produce query results efficiently and predictably

---
### `Connected Notes`

- [[Query Processing]]