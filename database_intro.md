# Introduction to Database

<img src="https://media.istockphoto.com/vectors/database-icon-vector-id1238951588?k=20&m=1238951588&s=170667a&w=0&h=6uKvHgbQoo1loizz9vvhFAt_u4ciiEDpWnkSamYKNSw=" width="300" height="300" />

The Database is an essential part of our life. As we encounter several activities that involve our interaction with databases, for example in the bank, in the railway station, in school, in a grocery store, etc. These are the instances where we need to store a large amount of data in one place and fetch these data easily. 

A database is a collection of data that is organized, which is also called structured data. It can be accessed or stored in a computer system. It can be managed through a Database Management System (DBMS), a software used to manage data. Database refers to related data in a structured form.

>A database is a persistent, logically coherent collection of inherently meaningful data, relevant to some aspects of the real world.

Types of Databases:
- Hierarchical databases
- Network databases
- Object-oriented databases
- Relational databases
- NoSQL databases


## NoSQL Vs SQL

![SQL vs NOSQL](https://www.clariontech.com/hs-fs/hubfs/SQL-NOSQL.png?width=1220&name=SQL-NOSQL.png)

| | SQL Databases | NoSQL Databases|
| --- | --- | ---|
Data Storage Model | Tables with fixed rows and columns | Document: JSON documents, Key-value: key-value pairs, Wide-column: tables with rows and dynamic columns, Graph: nodes and edges|
Development History | Developed in the 1970s with a focus on reducing data duplication | Developed in the late 2000s with a focus on scaling and allowing for rapid application change driven by agile and DevOps practices.
Examples | Oracle, MySQL, Microsoft SQL Server, and PostgreSQL | Document: MongoDB and CouchDB, Key-value: Redis and DynamoDB, Wide-column: Cassandra and HBase, Graph: Neo4j and Amazon Neptune
Primary Purpose | General purpose | Document: general purpose, Key-value: large amounts of data with simple lookup queries, Wide-column: large amounts of data with predictable query patterns, Graph: analyzing and traversing relationships between connected data
Schemas | Rigid | Flexible
Scaling | Vertical (scale-up with a larger server) | Horizontal (scale-out across commodity servers)
Multi-Record ACID Transactions |Supported | Most do not support multi-record ACID transactions. However, some—like MongoDB—do.
Joins | Typically required | Typically not required
Data to Object Mapping | Requires ORM (object-relational mapping) | Many do not require ORMs. MongoDB documents map directly to data structures in most popular programming languages.



## Step 1 — Installing MongoDB 

Ubuntu >> [digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-20-04)

Mac >> [Watch on youtube](https://www.youtube.com/watch?v=MIByvzueqHQ&feature=emb_logo)



## Step 2 - Installing pymongo
```$ python -m pip install pymongo```

https://pymongo.readthedocs.io/en/stable/

## step 3 - mongodb compass
https://www.mongodb.com/try/download/compass

## Relational Database
![Relationship Diagram Example](https://www.guru99.com/images/1/100518_0621_ERDiagramTu1.png)
Relationship Diagram Example

## SQLite
<img src="https://www.sqlitetutorial.net/wp-content/uploads/2021/04/sqlite-tutorial-homepage.svg" width="200" height="200" />

learn SQLite from [here](https://www.sqlitetutorial.net/)


**Sources:**

[geeksforgeeks.org](https://www.geeksforgeeks.org/what-is-database/?ref=lbp)

[digitalocean.com](https://www.digitalocean.com)

[mongodb.com](https://www.mongodb.com/nosql-explained/nosql-vs-sql)

https://docs.mongodb.com

[esp.org](http://www.esp.org/db-fund.pdf)



