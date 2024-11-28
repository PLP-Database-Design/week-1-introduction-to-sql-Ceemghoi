--Question one
1. Database Engine
- The core component responsible for data storage, retrieval, and management
- Processes and manages data at the most fundamental level

2. Query Processor
- Interprets and processes user queries
- Translates SQL commands into executable instructions

3. Transaction Management Subsystem
- Ensures data consistency and reliability
- Manages concurrent database access
- Implements ACID (Atomicity, Consistency, Isolation, Durability) properties

4. Storage Management Subsystem
- Manages physical storage of data
- Handles data file organization

5. Security and Authorization Manager
- Controls user access to database objects
- Implements authentication and authorization mechanisms
- Manages user roles and permissions

6. Data Dictionary/Metadata Repository
- Stores information about database schema
- Maintains details about tables, columns, and relationships

7. Backup and Recovery Manager
- Creates and manages database backups
- Implements disaster recovery strategies

8. Database Administration Tools
- Provide interfaces for database management
- Support performance monitoring
- Enable schema modifications

--Question Two
Relational Database:
A relational database is a type of database that stores and provides access to data points that are related to one another through tables with rows and columns. Each table represents an entity, and relationships between tables are established using keys.

Four Examples of Relational Database Management Systems (RDBMS):
a) MySQL
Open-source relational database
Widely used for web applications

b) PostgreSQL
Advanced open-source relational database
Known for its extensibility and complex query support

c) Oracle Database
Enterprise-level relational database
Highly scalable and robust
Widely used in large corporations and government agencies

d) Microsoft SQL Server
Integrated with Windows ecosystem
Supports business intelligence and analytics
Commonly used in financial and healthcare sectors

--Qestion Three
Three Classifications of SQL:
a) Data Definition Language (DDL)
Used to define and modify database structure
Commands include:
CREATE: Creates new database objects
ALTER: Modifies existing database objects
DROP: Deletes database objects
TRUNCATE: Removes all records from a table without deleting the table structure

b) Data Manipulation Language (DML)
Used to manipulate data within the database
Commands include:
SELECT: Retrieves data from tables
INSERT: Adds new records to a table
UPDATE: Modifies existing records
DELETE: Removes records from a table

c) Data Control Language (DCL)
Used to control access and permissions
Commands include:
GRANT: Provides specific privileges to users
REVOKE: Removes previously granted privileges
Manages user access rights and security

--Question Four
Primary Key vs. Foreign Key:
Primary Key:
Unique identifier for each record in a table
Ensures each row can be uniquely identified
Cannot contain null values
Each table can have only one primary key
Uniquely identifies a record in a table

Foreign Key:
References the primary key of another table
Establishes relationships between tables
Can contain null values
Multiple foreign keys can exist in a single table
Creates links between related tables

--Question Five
Entity-Relationship Diagram (ERD):
A graphical representation of entities in a database and their relationships, which includes:
Entities (tables)
Attributes (columns)
Relationships between entities
Cardinality of relationships (one-to-one, one-to-many, many-to-many)
Primary and foreign keys
Visualizes the logical structure of a database

--Question Six
Advantages of Relational Databases:
Data integrity and consistency
Efficient data retrieval through structured queries
Support for complex relationships between data
ACID properties ensure reliable transactions
Easy to understand and maintain
Supports multiple user access
Robust security mechanisms
Scalability and performance optimization

--Question Seven
Four Types of Data Types:
a) Numeric Types:
INTEGER
DECIMAL
FLOAT
REAL
b) String Types:
VARCHAR
CHAR
TEXT
NVARCHAR
c) Date and Time Types:
DATE
DATETIME
TIMESTAMP
TIME
d) Boolean Type:
BOOLEAN (TRUE/FALSE)

--Question Eight
Purpose of Database Management System (DBMS):
Efficient data storage and organization
Accurate and quick data retrieval
Comprehensive data management
Robust data security
Concurrent user access
Maintaining data integrity
Backup and recovery mechanisms
Performance optimization
Providing a centralized data management approach
