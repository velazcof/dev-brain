
A **Traceability Matrix** is a structured document or table that maps **relationships between related artifacts** (such as requirements, design elements, test cases, and implementations) to ensure coverage, consistency, and accountability.

It answers the question:

> _“Can we trace this thing back to why it exists, and forward to how it’s verified?”_

---
### `Key Ideas`

- **Bidirectional Traceability**  
    Links artifacts both:
    - **Forward** (e.g. requirement → test case)
    - **Backward** (e.g. test failure → originating requirement)

- **Coverage Verification**  
    Ensures that:
    - Every requirement is implemented
    - Every implementation is tested
    - No orphaned work exists

- **Change Impact Analysis**  
    Helps identify what is affected when:
    - A requirement changes
    - A design decision is modified
    - A test fails

- **Cross-Artifact Mapping**  
    Common mappings include:
    - Requirements ↔ Design
    - Requirements ↔ Test cases
    - User stories ↔ Acceptance criteria
    - Regulations ↔ Controls

- **Often Tabular, Not Conceptual**  
    Typically implemented as:
    - Tables
    - Spreadsheets
    - Structured documents  
        rather than diagrams.

- **Common in Regulated or Complex Systems**  
    Especially important where:
    - Compliance is required
    - Systems are safety- or mission-critical

---
### `Example`

|Requirement ID|Requirement Description|Design Component|Implementation|Test Case|
|---|---|---|---|---|
|R-001|User can log in|Auth Service|Login API|TC-01|
|R-002|Passwords are encrypted|Security Module|Hashing Logic|TC-02|
|R-003|Failed login is rate-limited|Rate Limiter|Auth Middleware|TC-03|
|R-004|User session expires|Session Manager|Token Expiry|TC-04|
(This table shows how each requirement is traced through design, implementation, and testing.)

---
### `Connected Notes`

- [[QA Documentation]]