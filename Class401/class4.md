# Data Modeling

## NoSQL vs SQL

- _What type of database is the best fit for the complex query intensive environment?_

  - SQL databases are best for complex query environments

- _What type of database is the best fit for hierarchical data storage?_

  - NoSQL is best for hierarchical data storage because it follows the key-value pair for storage.

- _Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend._

  - SQL is scalable vertically, like its a list that you can continously add to the bottom or modify. NoSQL is scalable horizontally, meaning you can access it quicker because you don't have to load the whole table.

## SQL modeling techniques

- _Among data tables, what is a one-to-many relationship and how do we “relate” them?_

  - One to many refers to one table having many table related to it for example a persons table might have a phycical characteristics table and a likes table and a relatives table all connect to it. We connect them using a foreign key.

- _Prior to designing your relational database, it might be useful to *** a *** of the database tables and their relationships._

  - draw a whiteboard?

- _Explain the difference between a primary and foreign key._

  - A primary key is what the foreign key copies so that they maintain a relation to eachother. 

## Videos: SQL vs nosql

- _How do we treat keywords and parameters differently in SQL syntax?_

  - Keywords are predefined words, kind of like methods in javascript, where they have a specific meaning or function behind them. Parameters are just variables for the most part.

- _Define normalization within the context of schemas and data._

  - Normalization is taking data and breaking it down into 3 forms. One where the data is orginized with no repeating groups. Then the second form being data that is dependent on the primary key. The third form is data that doesn't need to be dependent on anything. 

- _Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter._

  - One to one is where one table is linked to only one table and that table is only linked to it. One to many is where many tables connect to one primary table. Many to many is  where mutliple tables have multiple connections. 
