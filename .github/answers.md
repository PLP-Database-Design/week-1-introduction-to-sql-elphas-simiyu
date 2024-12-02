1.State and Explain the components of a DBMS(Database Management System)
    A DBMS consists of the following key components:

    1.Data: Organized information stored in a structured format that the DBMS manages.
    2.Hardware: Physical devices like servers or storage systems where the database resides.
    3.Software: The DBMS application that provides tools to interact with the database (e.g., MySQL, Oracle).
    4.Users: Includes database administrators, developers, and end-users who interact with the database.
    5.Database Engine: Handles data storage, retrieval, and query execution.
    6.Query Processor: Interprets and executes user queries written in SQL.
    7.Metadata: Data about the data, such as structure, constraints, and indexing information.

2.What is a relational database? Give 4 examples
    -A relational database organizes data into tables (or relations) that are linked based on predefined relationships using keys. Each table consists of rows (records) and columns (attributes).
Examples:
    1.MySQL
    2.PostgreSQL
    3.Oracle Database
    4.Microsoft SQL Server

3.State and Explain three classifications of SQL?
    SQL is classified into three main categories:
    -Data Definition Language (DDL):
        -Used to define and manage database structure.
        -Examples: CREATE, ALTER, DROP.

    -Data Manipulation Language (DML):
        -Used to manipulate data in the database.
        -Examples: INSERT, UPDATE, DELETE, SELECT.

    -Data Control Language (DCL):
        -Used to control access to the database.
        -Examples: GRANT, REVOKE.

4.What is the difference between a Primary Key and a Foreign Key?
    Primary Key(PK)	Foreign Key(FK)
    PK-Uniquely identifies each record in a table.	
    FK-Links a record in one table to the primary key of another table.

    PK-Cannot contain null values.	
    FK-Can contain null values if the relationship allows it.

    PK-Each table has only one primary key.	
    FK-A table can have multiple foreign keys.

5.What is an Entity-Relationship Diagram?
    -An ERD is a graphical representation of the entities (tables) in a database and the relationships between them. It  is used during the design phase to model the logical structure of a database.
  Components of ERD:
    -Entities: Represented as rectangles (e.g., "Customer").
    -Attributes: Represented as ovals (e.g., "Customer ID").
    -Relationships: Represented as diamonds, showing how entities are connected.

6.What are the advantages of relational databases?
    -Data Integrity: Ensures accuracy and consistency of data.
    -Flexibility: Easily adapt to changes in structure or scale.
    -Data Security: Supports access controls to protect sensitive information.
    -Reduced Redundancy: Normalization minimizes duplicate data.
    -Ease of Use: Uses SQL for straightforward querying and data management.

7.State four types of data type used to store data in tables?
    -Integer: Stores whole numbers (e.g., INT, BIGINT).
    -String: Stores text (e.g., VARCHAR, CHAR).
    -Date/Time: Stores dates and times (e.g., DATE, TIMESTAMP).
    -Boolean: Stores true/false values (BOOLEAN).

8.What is the purpose of a database management system (DBMS)?
    The purpose of a DBMS is to efficiently store, retrieve, and manage data while ensuring data integrity, security, and consistency. 