
**Database Backup & Recovery** refers to the strategies and processes used to protect database data from loss and restore it after failures. It ensures that a database system can be returned to a consistent state following corruption, crashes, or accidental data deletion.

---
### `Key Ideas`

- **Data Protection Strategy**  
    Backups create restorable copies of database data to prevent permanent data loss.
    
- **Recovery Procedures**  
    Recovery restores the database to a previous consistent state using backups and transaction logs.
    
- **Full and Incremental Approaches**  
    Systems may perform complete backups or partial backups that capture only changes since the last backup.
    
- **Point-in-Time Recovery**  
    Some systems allow restoring data to a specific moment using logged operations.
    
- **Separation from Replication**  
    Replication improves availability, while backup ensures recoverability after corruption or catastrophic failure.
    
- **Operational Responsibility**  
    Backup and recovery planning is part of database operations rather than internal engine behavior.

---
### `Connected Notes`

- [[Database Operations]]