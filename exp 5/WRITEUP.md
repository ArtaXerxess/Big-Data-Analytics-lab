# NoSQL / MongoDB

### Aim: To understand and implement the basics of MongoDB and NoSQL

### Theory 

#### MongoDB
 
 MongoDB, the most popular NoSQL database, is an open-source document-oriented database. The term ‘NoSQL’ means ‘non-relational’. It means that MongoDB isn’t based on the table-like relational database structure but provides an altogether different mechanism for storage and retrieval of data. This format of storage is called BSON ( similar to JSON format).
 
#### Features of MongoDB:

Document Oriented: MongoDB stores the main subject in the minimal number of documents and not by breaking it up into multiple relational structures like RDBMS. For example, it stores all the information of a computer in a single document called Computer and not in distinct relational structures like CPU, RAM, Hard disk, etc.

Indexing: Without indexing, a database would have to scan every document of a collection to select those that match the query which would be inefficient. So, for efficient searching Indexing is a must and MongoDB uses it to process huge volumes of data in very less time.

Scalability: MongoDB scales horizontally using sharding (partitioning data across various servers). Data is partitioned into data chunks using the shard key, and these data chunks are evenly distributed across shards that reside across many physical servers. Also, new machines can be added to a running database.

Replication and High Availability: MongoDB increases the data availability with multiple copies of data on different servers. By providing redundancy, it protects the database from hardware failures. If one server goes down, the data can be retrieved easily from other active servers which also had the data stored on them.

Aggregation: Aggregation operations process data records and return the computed results. It is similar to the GROUPBY clause in SQL. A few aggregation expressions are sum, avg, min, max, etc

#### Commands (Nosql)

![insert command](https://user-images.githubusercontent.com/74452252/185842980-2f3477d5-83ba-4937-91a1-a55a887fec89.PNG)

![pretty command display](https://user-images.githubusercontent.com/74452252/185843053-b2872911-0820-46e1-acd9-2e6768df6007.PNG)

![image](https://user-images.githubusercontent.com/74452252/185843180-1f81180f-2add-4edb-a9eb-c263f95a2f09.png)

![update and find command ](https://user-images.githubusercontent.com/74452252/185843077-95e2f452-d5c8-4793-8d4d-2b0aec7d3566.PNG)




### Conclusion: MongoDB and NoQL are studied and implemented successfully
