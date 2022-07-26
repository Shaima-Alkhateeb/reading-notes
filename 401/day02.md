# SQL database, ORM, Sequelize

## What's the difference between SQL  and NoSQL?

SQL: Structured Query Language 

NoSQL: not only SQL

| SQL | NoSQL |
| ----------- | ----------- |
| primarily called Relational Databases (RDBMS) | primarily called non-relational or distributed database |
| predefined schema | dynamic schema |
| vertically scalable | horizontally scalable |
| uses SQL ( structured query language ) for defining and manipulating the data | UnQL (Unstructured Query Language) queries are focused on the collection of documents|
| scaled by increasing the horse-power of the hardware | scaled by increasing the databases servers in the pool of resources to reduce the load |

## What is Sequlize and how to use it with Node js?

Sequelize is a promise-based, Node.js ORM (Object-relational mapping) for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server. It features solid transaction support, relations, eager and lazy loading, read replication, and more.

Also is an Object Relational Mapper for Node. js. Sequelize lets us connect to a database and perform operations without writing raw SQL queries. It abstracts SQL queries and makes it easier to interact with database models as objects.


## What is an ORM, how does it work, and how should I use one?

Object-relational mapping (ORM) is a programming technique in which a metadata descriptor is used to connect object code to a relational database. Object code is written in object-oriented programming (OOP) languages such as Java or C#. ORM converts data between type systems that are unable to coexist within relational databases and OOP languages.

How Does ORM Work? 

The main postulate that characterizes ORM is that it encapsulates database interaction inside an object. One part of the object keeps the data and the second one knows how to deal with the data and transfers it to the relational database (this functionality is implemented inside the ORM engine).

for example, rather than write this code 
```
book_list = new List();
sql = "SELECT book FROM library WHERE author = 'Linus'";
data = query(sql); // I over simplify ...
while (row = data.next())
{
     book = new Book();
     book.setAuthor(row.get('author');
     book_list.add(book);
}
```
it becomes like this with ORM
```
book_list = BookTable.query(author="Linus");
```

-----

- Which 3 things had you heard about previously and now have better clarity on?

SQL, database and CRUD


- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

More about SQL, Sequelize and ORM

- What are you most excited about trying to implement or see how it works?

The SQL 
