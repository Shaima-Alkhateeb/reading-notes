# Class 11: Mongo and Mongoose

## (nosql vs sql)

| SQL | NoSQL |
| ----------- | ----------- |
| primarily called Relational Databases (RDBMS) | primarily called non-relational or distributed database |
| predefined schema | dynamic schema |
| vertically scalable | horizontally scalable |
| uses SQL ( structured query language ) for defining and manipulating the data | UnQL (Unstructured Query Language) queries are focused on the collection of documents|
| scaled by increasing the horse-power of the hardware | scaled by increasing the databases servers in the pool of resources to reduce the load |

----

1. What kind of data is a good fit for an SQL database?
--> For the complex query-intensive environment
2. Give a real-world example.
-->  Netflix, Amazon, Flipkart, Instagram
3. What kind of data is a good fit for a NoSQL database?
--> Simple schema. High velocity read/write with no frequent updates. High performance and scalability. No complex queries involving multiple keys or joins
4. Give a real-world example.
--> MongoDB, CouchDB, CouchBase, Cassandra, HBase, Redis, Riak, Neo4J
5. Which type of database is best for hierarchical data storage?
--> NoSQL
6. Which type of database is best for scalability?
--> SQL

## sql vs nosql (Video)

1. What does SQL stand for?
-->Structured Query Language
2. What is a relational database?
--> Is a collection of data items with pre-defined relationships between them. These items are organized as a set of tables with columns and rows.
3. What type of structure does a relational database work with?
--> (One-to-One), (One-to-Many), and (Many-to-Many)
4. What is a ‘schema’?
--> It defines how data is organized within a relational database
5. What is a NoSQL database?
-->Its referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases.
6. How does it work?
--> It has a database but doesn't have tables instead their is Collections, inside the Collections, there are Documents(rows), and it stores data in documents rather than relational tables
7. What is inside a Mongo database?
-->stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.
8. Which is more flexible - SQL or MongoDB? and why.
-->MongoDB, because it has no Schema
9. What is the disadvantage of a NoSQL database?
-->There are some duplicates data
