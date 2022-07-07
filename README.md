# SQL-Languages

TYPES OF SQL LANGUAGES
1. DDL- Data Definiton Language
2. DML- Data Manipulation Language
3. DCL- Data Control Language
4. TCL- Transaction Control Language

![sql languages](https://user-images.githubusercontent.com/3311519/177560938-a25e1067-1927-4463-baf6-b3f6a897ed58.png)

1. DDL- Data Definiton Language

DDL actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database object in the database.
Example:-

    CREATE - is used to create the database or its objects (table, index, function, views, stored procedure and triggers)
    
    DROP - is used to delete objects from the database.
    
    ALTER - is used to alter the structure of the database.
    
    TRUNCATE - is used to remove all records from a table, including all spaces allocated for the records are removed.
    
    COMMENT - is used to add comment tp the data dictionary.
    
    RENAME - is used to rename an existing object in the database.
    
    
![sql 1](https://user-images.githubusercontent.com/3311519/177692314-c1ec5034-501f-42e9-ba66-26e1ffc4bf37.png)



2. DML- Data Manipulation Language

This SQL commands deal with the manipulation of data present in the database.
    
    INSERT - is used to insert data into a table.
    
    UPDATE - is used to update existing data within a table.
    
    DELETE - is used to delete records from a database table.
    
    SELECT - is used to retrieve data from the database.
    

![sql 2](https://user-images.githubusercontent.com/3311519/177692328-460f51bf-578e-4937-99a2-5141714c0c23.png)


3. DCL- Data Control Language

DCL includes commands such as GRANT and REVOKE which mainly deal with the rights, permission and other controls of the database system.

![grant-revoke](https://user-images.githubusercontent.com/3311519/177692823-ee6fd52b-8cde-48c9-a1d7-20866f96ce91.png)


GRANT- gives user access privilages to the database

REVOKE- withdraw user's access privilages given by using the GRANT command.

![diff grant-revoke](https://user-images.githubusercontent.com/3311519/177692997-8a147d5c-a112-462c-b7a6-a9337196cde8.png)


4. TCL- Transaction Control Language

TCL commands deal with the transaction within the database.

COMMIT- commits a Transaction

ROLLBACK- rollbacks a transaction in case of any error occurs.

SAVEPOINT- sets a savepoint within a transaction.

SET TRANSACTION- specify characteristics for the transaction.


![insert](https://user-images.githubusercontent.com/3311519/177693671-6fe75937-08c2-4f85-a204-a24e16e765d6.png)

COMMIT - If everything is in order with all statements within a single transaction, all changes are recorded together ub the database is called committed. The COMMIT command saves all the transactions to the database since the last COMMIT ot ROLLBACK command.


![commit](https://user-images.githubusercontent.com/3311519/177695034-94b8c061-a6d3-40d2-bff3-d3422d0c58cf.png)


ROLLBACK - If any error occurs with any of the SQL grouped statements, all changes need to be aborted. The process of reversing changes is called rollback. This command can only be used to undo transactions since last COMMIT or ROLLBACK command was issued. 

![rollback](https://user-images.githubusercontent.com/3311519/177695691-7f8110f5-ad8c-4264-9e47-13fdadb65c15.png)


SAVEPOINT - Creates points within the groups of transactions in which to ROLLBACK. A SAVEPOINT is a point in transaction in which you can roll the transaction back to a certain point without rolling back the entire transaction.


 ![rollback](https://user-images.githubusercontent.com/3311519/177701434-d89d092d-1f0f-422a-8dd4-ba486e796ef9.png)



    
