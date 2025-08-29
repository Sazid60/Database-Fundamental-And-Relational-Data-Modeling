
# RDBMS RECAP-1
Slide Link: https://drive.google.com/file/d/1T5ZsbQibyIerI-MiOtVjZVh4STQuXf73/view?usp=drive_link



In this module, you’ll learn the foundations of databases and the relational model. We’ll cover data vs. information, database models, tables, and different types of keys. You’ll also explore the database design process with ER diagrams and relationship cardinality—equipping you with the skills to design efficient relational databases.

## 42-1 Database and data vs information
- A database is a structured collection of related data, organized for efficient storage, retrieval, and management.
- data Is Everywhere and Data Is Everything. Data is heart of a application 

### What is Data ?
- Data is a fact that can be recorded in form of any format. 

### What is Information?
- Information is processed and organized data that provides meaningful context, insight or knowledge. 

![alt text](image.png)

## 42-2 Why File Systems Fail
- Full Form of dbms is database management system 

### How Do we Store Data Using File System? 
- We could use file system to store the data as well instead of database 
    1. We have Multiple formate data (.txt.mp4, etc). Combining these all and work will be a hassle because we have to make different program to grab information we need a specific system. 
    2. Data Redundancy (data duplication) problem will appear
    3. Data Inconsistency will appear
    4. No Concurrency Protocol (there is no fixed rules like which works will be done first)
    5. There will be security issue (Either we have to give full access to a user or none)

![alt text](image-1.png)

### For Solving the drawback of the file system dbms came 
- Dbms take all the responsibilities for managing data 

#### Popular database management system 
- `Relational` - Mysql, postgresql, sqlite, sql server
- `Document` - Mongodb, Dynamodb
- `Key value` - Redis 