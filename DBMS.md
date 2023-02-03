<details>
<summary>DBMS Notes</summary>

SQL commands are categorized into below 5 categories:

- DDL – Data Definition Language
- DQL – Data Query Language
- DML – Data Manipulation Language
- DCL – Data Control Language
- TCL - Transaction Control Language
    
![image](https://user-images.githubusercontent.com/117622722/202619753-ff0bda2a-9973-4f55-b998-8174392d5c7a.png)


- **DDL** or Data definition language is actually the definition or description of the database structure or schema, it won't change the data inside the database. Create, modify, and delete the database structures, but not the data. Only These commands are not done by all the users, who have access to the database via an application.
- **DQL** or data query language is to perform the query on the data inside the schema or object (ie table, index, view, function, etc). With the help of DQL query we can get the data from the database to perform actions or operations like analysing the data.
- **DML** or Data Manipulation Language is to manipulate the data inside the database. With the help of DML commands, we can insert, delete, change the data inside the database.
- **DCL** or Data Control Language is to provide rights, permissions, and other controls of the database system.
- **TCL** or Transaction Control Language happens to a transaction in the database.

[Resource](https://www.c-sharpcorner.com/article/sql-commands-ddl-dql-dml-dcl-tcl-with-examples/)
    
- DDL Commands
    - Create the database or its object (ie table, index, view, function etc.).
    - Drop command helps to delete the object from the database (ie table, index, view, function, etc.).
    - Alter command is helpful to change or modify the structure of the database or its object.
    - Truncate command helps to remove all records from a table.
    - Comment is helpful to add comments to the data dictionary."--" is used to comment the notes.
    - Rename is helpful to rename an object existing in the database.
    
- DQL Commands
    - Select query on a table or tables to view the temporary table output from the database.

- DML Commands
    - Insert command is helpful to insert the data into a table.
    - Update command is helpful to update the existing data in a table.
    - Delete command helps to delete the records from a database table.
    - Call command is helping to Call a PL/SQL or JAVA subprogram.
    - Lock command is helpful to lock the table to control concurrency.
    - EXPLAIN PLAN - It describes the access path to the data.
    
- DCL Commands
    - GRANT command is helpful to provide privileges to the database.
    - Revoke command is to withdraw the user’s access privileges given by using the GRANT command.
    
- TCL Commands
    - Commit command is to commit Transaction after insert or delete in the database.
    - Rollback command is to rollback a transaction in case of any error occurs.
    - Savepoint command is to Set a savepoint within a transaction. If transaction happens in big data, then for checking and rollup can't do it with all the data, to rollback the small part of the data we use savepoint query.
    - SET TRANSACTION - Set command is to Specify the characteristics of the transaction.
    
</details>
