# sillyQL


A C++ Project for my EECS 281: Data Structures & Algorithms class which emulates a basic relational database with an interface based on a subset of a standard query language. This relational database supported the following commands:
+ `CREATE`-creates a new database. Multiple databases may be active at the same time
+ `INSERT INTO`-inserts data into an existing table
+ `DELETE FROM` - deletes specific data from table
+ `GENERATE INDEX` - create either a hash or bst search index on the specified column to optimize certain operations
+ `PRINT` - print specified rows
+ `JOIN` - join two tables and print result. This was implemented using hash join to optimize efficiency
+ `REMOVE` - remove existing table from the database
