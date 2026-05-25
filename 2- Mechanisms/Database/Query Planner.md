
### `Definition`

**Query Planner** is the mechanism that determines how a parsed query should be executed by generating possible execution strategies. It transforms a structured query representation into one or more candidate execution plans.

---
### `How It Works`

- **Analyzes Query Structure**  
    Interprets the parsed representation of the query to understand required operations such as joins, filtering, and aggregation.

- **Generates Candidate Plans**  
    Produces alternative execution strategies based on available indexes and data access paths.

- **Defines Operator Ordering**  
    Determines the order of operations (e.g., join order, filter placement).

- **Produces an Execution Plan**  
    Outputs a structured plan that can be evaluated or refined before execution.

---
### `Why It Exists`

- To translate logical query intent into executable strategies
- To explore different ways of retrieving and combining data
- To prepare structured plans for cost evaluation and execution

---
### `Connected Notes`

- [[Query Processing]]