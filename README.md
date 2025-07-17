# DATABASE-MIGRATION
Database Migration – MySQL to PostgreSQL

This task focused on simulating a real-world database migration from one RDBMS to another — specifically, from MySQL to PostgreSQL — while preserving data integrity, schema structure, and relational consistency.


📌 Objective:


To perform a seamless migration of both schema and data between two different database systems and validate the correctness of the transferred information.


🧠 Description:

In this task, I simulated a cross-database migration by:

Exporting data from MySQL-friendly tables

Rewriting equivalent PostgreSQL-compatible schemas

Inserting data into the new system while maintaining data types and key constraints

Running validation queries to confirm data accuracy and relational integrity

Though this task was simulated using SQL Fiddle, the logic and structure reflect real migration workflows carried out in production environments.


⚙️ Migration Workflow:


Schema Translation – Adjusted data types and syntax between MySQL and PostgreSQL

Data Transfer – Used INSERT INTO ... SELECT * style queries to simulate the transfer

Validation – Performed count checks, NULL checks, and relationship validations post-migration

Documentation – Summarized the migration process, challenges, and best practices


📄 What I Learned:


Translating schema definitions between SQL dialects

Handling data compatibility and constraint enforcement

Ensuring referential integrity during migrations

Simulating real-world database operations in a test-safe environment


🛠 Tools Used:

SQL Fiddle (MySQL & PostgreSQL environments)

Manual schema rewriting for compatibility

VS Code for SQL script development

📁 Files:

bash
Copy
Edit

📂 Task3_Migration


├── mysql_schema.sql              # Source MySQL schema and sample data
├── postgresql_schema.sql         # Target PostgreSQL-compatible schema
├── migration_queries.sql         # Data insertion simulation & migration logic
├── migration_summary.md          # Explanation of the steps, decisions, and validations


✅ This task enhanced my backend data engineering perspective and taught me how to handle real-world schema conversions with attention to detail and precision.
