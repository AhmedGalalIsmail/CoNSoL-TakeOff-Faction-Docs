# Layer 03 - Database Design

## Purpose

Design a database architecture that is reliable, scalable, maintainable, secure, and optimized for application requirements.

The database is the source of truth for business data and must support both current and future application needs.

---

## AI Agent Mission

Act as a Database Architect responsible for:

- Data modeling
- Schema design
- Query performance
- Data integrity
- Scalability planning
- Recovery planning

---

## Objectives

- Design a maintainable schema
- Minimize data duplication
- Ensure data integrity
- Optimize read/write performance
- Support future growth
- Protect critical business data

---

## Required Deliverables

### Conceptual Design

Produce:

- Business Entities
- Entity Relationships
- Domain Model

### Logical Design

Produce:

- ERD
- Relationship Matrix
- Data Dictionary

### Physical Design

Produce:

- Tables
- Constraints
- Indexes
- Views
- Stored Procedures (when justified)

### Operational Design

Produce:

- Backup Strategy
- Recovery Strategy
- Archiving Strategy

---

## Execution Tasks

### Task Group 01 - Business Data Analysis

Agent must:

- Identify business entities
- Identify business rules
- Identify ownership of data
- Identify lifecycle of records

Examples:

- Customer
- Order
- Invoice
- Product
- Subscription

Validation:

- Every business process maps to data entities.

---

### Task Group 02 - Entity Relationship Design

Agent must:

- Define primary entities
- Define relationships
- Define cardinality

Examples:

- One-to-One
- One-to-Many
- Many-to-Many

Validation:

- No ambiguous relationships.
- Every relationship has a business justification.

---

### Task Group 03 - Schema Design

Agent must:

- Create tables
- Define columns
- Define keys
- Define constraints

Validation:

- Primary Keys exist.
- Foreign Keys exist.
- Naming standards are enforced.

---

### Task Group 04 - Normalization

Agent must:

- Apply 1NF
- Apply 2NF
- Apply 3NF

Avoid:

- Duplicate columns
- Repeating groups
- Data anomalies

Validation:

- Redundancy minimized.

---

### Task Group 05 - Performance Design

Agent must:

- Create indexes
- Analyze query patterns
- Optimize joins
- Reduce expensive scans

Validation:

- Critical queries meet performance targets.

---

### Task Group 06 - Data Integrity

Agent must:

- Enforce business constraints
- Enforce referential integrity
- Use transactions when required

Validation:

- Invalid data cannot enter the system.

---

### Task Group 07 - Security

Agent must:

- Protect sensitive data
- Encrypt where required
- Restrict access

Examples:

- Passwords
- Tokens
- Financial data
- Personal information

Validation:

- Least-privilege principle enforced.

---

### Task Group 08 - Backup & Recovery

Agent must:

- Define backup schedule
- Define restore procedures
- Test recovery plans

Validation:

- Recovery procedures documented and tested.

---

## Success Criteria

Database Design is complete when:

- ERD approved
- Schema approved
- Integrity validated
- Performance validated
- Security reviewed
- Recovery plan tested