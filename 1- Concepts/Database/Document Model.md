
The **Document Model** is a database model that represents data as self-contained documents, typically structured in hierarchical or nested formats. Each document encapsulates related data together, rather than distributing it across multiple tables.

---
### `Key Ideas`

- **Document as Primary Unit**  
    Data is stored as independent documents that group related fields together.
    
- **Flexible Schema**  
    Documents can vary in structure, allowing fields to differ between records.
    
- **Hierarchical Structure**  
    Supports nested objects and arrays, enabling representation of complex data within a single document.
    
- **Entity-Centric Design**  
    Data that belongs together conceptually is stored together physically and logically.
    
- **Reduced Need for Joins**  
    Relationships are often embedded rather than referenced, minimizing cross-document operations.
	
- **Implementation-Specific Languages**  
    Query languages vary by system (e.g., JSON-based or SQL-like dialects) and are not universally standardized.
    
- **Flexible Query Expressiveness**  
    Languages are often designed to match nested document structures rather than relational joins.

---
### `Connected Notes`

- [[Database Models]]