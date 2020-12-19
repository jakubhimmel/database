# Database

Database Management System (DMS)
  - used to manage database 

Structured Query Language 
  - SQL
  - programming language used to manipulate with eelational databases
  - CRUD (Create, Read, Update, Delete)

## Types of Databases 

- <b>Relational databases</b> Relational databases became dominant in the 1980s. Items in a relational database are organized as a set of tables with columns and rows. Relational database technology provides the most efficient and flexible way to access structured information.

- <b>Object-oriented databases</b> Information in an object-oriented database is represented in the form of objects, as in object-oriented programming.

- <b>Distributed databases</b> A distributed database consists of two or more files located in different sites. The database may be stored on multiple computers, located in the same physical location, or scattered over different networks.

- <b>Data warehouses</b> A central repository for data, a data warehouse is a type of database specifically designed for fast query and analysis.

- <b>NoSQL databases</b> A NoSQL, or nonrelational database, allows unstructured and semistructured data to be stored and manipulated (in contrast to a relational database, which defines how all data inserted into the database must be composed). NoSQL databases grew popular as web applications became more common and more complex.

- <b>Graph databases</b> A graph database stores data in terms of entities and the relationships between entities.

- <b>OLTP databases</b> An OLTP database is a speedy, analytic database designed for large numbers of transactions performed by multiple users.

## Dataset
set = collection of similar things 
dataset = colection of rows with the same column definition

table = dataset that is physically stored on a disk

dataset relationships (Venn diagrams):
intersect 
union 
exept 

https://i.redd.it/p3q51rn2o2k41.png

# Database architecture 

PRIMARY KEY X UNIQUE KEY
Unique key
- unique for each entry (social security number), each row in a table can be identified
- guarantee that no data repeats within a column 
- can be null     
- more per table
- can be modified 

Primary key
- unique within a column (id)
- like unique keys but they gurantee that each row in the table can be uniquely identified
- never null 
- one per table 
- cannot be modified 
- auto incerementing number fields 

Foreign key 
- a pointer or a reference from one table to another
- both columns have to match in both tables 
- foreign key constraint = a rule enforced by the database desingner ensuring that the tables are connected (referentiall identity)
- foreign key values must also exist as a primary key in a reference table  

## Table relations 
one-to-one

one-to-many  
many instances of the foreign key, person table with eye color column (many) => eye table with id's and eye colors )

many-to-many
example = "orders and parts"

## Database schema


Entity–relationship model

Entity relationship Diagram notation: 
https://www.lucidchart.com/pages/ER-diagram-symbols-and-meaning

source: https://www.tutorialspoint.com/dbms/dbms_data_schemas.htm

## Tables join 
INNER and (left or right or full)OUTTER

## Set opearations
union
union all 
intersect 
exept

## sub querries



## Database modeling

tiers: 1,2,n-tier 

## Normalization of Database:
Braking data into sets base on similar atributes & replacing "STRINGS" into references e.g. a table with <u>id</u> and <u>product name</u> and a main table with sales stats where in <u>product</u> column you get a <u>id</u> from the prior table

decomposing tables to eliminate data redundancy and undesirable characteristics like Insertion, Update and Deletion Anamolies. It is a multi-step process that puts data into tabular form by removing duplicated data from the relation tables.

First Normal Form:

A database is in first normal form if it satisfies the following conditions:
Contains only atomic values
There are no repeating groups

source: https://medium.com/oceanize-geeks/concepts-of-database-architecture-dfdc558a93e4#:~:text=Database%20architecture%20uses%20programming%20languages,for%20businesses%2C%20agencies%20and%20institutions.

## Database analysis



## Database learning sources
https://www.1keydata.com/
https://db.grussell.org/
https://www.oracletutorial.com/getting-started/

## Oracle cheatsheet's
https://www.oracletutorial.com/oracle-basics/


