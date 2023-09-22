# Data Modeling

### Nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?

* A "relational" database, which is usually a SQL-esque database.

2. What type of database is the best fit for hierarchial data storage?

* NoSQl Databases (MongoDB)

3. Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend

* Okay bro so check this out. You want to get bigger and be able to do way more right? Boom. SQL. You wanna be strong but a little more focused? Boom. NoSQl.

### sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we "relate" them?

* "An entry in one table can be related to more than one entry in another." 

2. Prior to designing your relational database, it might be useful to __ a __ of the database tables and their relationships.

* Create a diagram

3. Explain the difference between a primary and foreign key

* A primary key are unique identifiers for each row in a atable. A foreign key is a set of columns that match a primary key in another table.


### sql vs nosql (videos)

1. How do we treat keywords and parameters differnetly in SQL syntax?

* Keywords are special reserved words in SQL.
* Paramaters are values that make SQL dynamic
* Maybe use the keywords to find the type of information you want, and then parameters in order to filter the results.

2. Define normalization within the context of schemas and data.

* Normalization is like sorting a bunch of tools into a toolbox based on the the most basic features of the tools. So screwdrivers and flatheads would go in one box, Power-drills/saws would go in another because they both use power, etc.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

* One-to-one is having a specific key for one lock
* One-to-many is having a lock with many different keys, but individual keys only work with one special lock. So a lock with many different keys, and a key for many different locks.
* Many-to-Many is like having a bunch of tools in your toolbox, and each tool fixes multiple problems. 
