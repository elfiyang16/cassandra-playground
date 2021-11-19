### An Experiment with Cassandra the Beast

Terminologies vs. RDBS

```
RDBS	      | CASSANDRA
--------------------------
Database	  | Keyspace
Table	      | Column Family
Primary Key   | Row Key
Structured 	  | Unstructured
Fixed Schema  |	Flexible Schema
```

Row:- A row is the collection of columns ordered columns.
Column:- A column is the collection of key/value pairs.
RowKey:- A primary key is called a row key.
Compound Primary Key:- A primary key consist of multiple columns. One part of that key then called Partition Key and rest a Cluster Key.
