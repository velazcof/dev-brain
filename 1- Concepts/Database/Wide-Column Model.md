
The **Wide-Column Model** (also known as the Column-Family Model) is a database model that organizes data into rows identified by a primary key, where each row can contain a flexible and potentially large set of columns grouped into families.

It is designed for distributed systems that prioritize scalability and partition-based data access.

---
### `Key Ideas`

- **Row-Oriented with Flexible Columns**  
    Each row is uniquely identified by a key, but the number and type of columns can vary between rows.
    
- **Column Families**  
    Related columns are grouped together, enabling efficient storage and retrieval based on access patterns.
    
- **Partition-Centric Design**  
    Data is organized around partition keys, which determine how data is distributed across nodes.
    
- **Query-Driven Modeling**  
    Data schemas are designed around expected query patterns rather than normalized relational structure.
    
- **Limited Join Support**  
    Traditional relational joins are not supported; relationships are typically modeled through denormalization.
    
- **Distributed System Orientation**  
    Commonly used in horizontally scalable architectures requiring high write throughput and availability.

---
### `Connected Notes`

- [[Database Models]]
- [[NoSQL Paradigms]]