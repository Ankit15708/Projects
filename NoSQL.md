## SQL
It is stands for "Structured Query Language". As a developer or a programmer or in any field either it is sales or maketing or finance, we have to deal with data every day.Data is required to move at any conclusion.
SQL is a language that is used to communicate with DataBase, DataBase is a place where we can save our data files online. DataBase are like wherehouses it can have a lot of containere where we can save our files.
***
## NoSQL
It refers to "Not Only SQL" or Non-SQL" or Non-Relational". Before NoSQL we used to store the relational data in DataBases. A relational data is stands for the same type of data, it means the key and value stands same for every entry in data logs.
But in NoSQL we can store or retrieve non relational data in the DataBase. That kind of data is existed in late 1960s but the name NoSQL is occured in 21st century.

There are few problems in SQL, why we have to come up with NoSQL:-
- The development in the SQL DataBase is very slow
- To handle the structure of many different types of data is difficult in SQL
- It needs too much time and work to fetch a large ammount of data from different Data Tables
###### Types of NoSQL DataBases
Here are four main types of NoSQL DataBase are listed below:-
- Document DataBases
- Key-Value Stores
- Column Oriented DataBases
- Graph Databases
1. In document DataBases data is stored in the form of JSON, BSON, xml files. In this type of DataBase files can be nested, it means we can store a file inside another file. Data is stored in a manner as that data is much closer to the Data Objects when ever we want to store or retrieve, it can be easily accessed.
It is popular between developers becase it has the ability to transform DataBase according to user requirements, if a user want to add new things in their data logs, it can be done by Document DataBase.
2. The Key-Value is the simplest type of No-SQL DataBase. Every data log has a specific data entry which is not same for two or more data logs, it is defined as a key and every data log is joined by that key in DataBase. It is like relational DataBase, their is a key  and other part is value. But in this DataBase the value can be another data set which can be different for every data log.
3. In this type of DataBases the data is stored in column-oriented manner it means whenever we want to fetch a particular column in the DataBase we can directly fetch data without going threw the each data log, as in relational DataBases data is stored row by row. This type of DataBases are useful for analysis.
But there is a dark side of these kind of DataBases is that, it write data in a manner that it becomes very inconsistent because it store data in DataBases after performing multiple events on disk.
4. Agraph-DataBase is centralized between the elements of data logs. Every element is stored as a node. The relation between every element is called Link or Relation. In graph databases the first class elements are presentation of a data set, that are associated with the link of relational database. A graph DataBase is used for finding relation between data elements.
***
Here are few NoSQL DataBases :-
1. **Mongo DB:-** It is a "Document" based NoSQL DataBase. It co-ordinate and control changes to the structure of documents using schema validation. It creates the DataBase in a manner that it can be serched and indexed very easily and in a fast manner.
2. **Elastic Search :-** It is also known are 'ES' and it is free and open source DataBase built with java. It is very useful when full text search is part of your solution. It means when we want to search any thing, the search engine examines all of the words in every stored documents
3. **Dynamo DB :-** It is a "Key-Value Stores" NoSQL data type. It is known for its scalability, which refers to the ability of DataBase to allow it to store the increasing ammount of data. It means when we have to store different type of data elements in different logs.
4. **HBase :-** It is a "Column-Oriented DataBase". It runs on the top of Hadoop Distributed file system (HDFS). It is highly scalable and open source DataBase systems. If you have a requirement to store petabytes of data then it is the most effective DataBase to be used.
5. **Cassandra :-** It is built by facebook. It is one of the most scalable as it can perform operation on petabytes of information and thousands of querys at a time. It is one of the open source NoSQL DataBases.
***
# References:-
 SQL:- https://www.youtube.com/watch?v=27axs9dO7AE
 NoSQL:- https://www.youtube.com/watch?v=AWEUeucIiWA
 Why to use NoSQL:- https://www.youtube.com/watch?v=xQnIN9bW0og&t=563s
 Types of NoSQL DataBases:- https://www.mongodb.com/scale/types-of-nosql-databases
 5 NoSQL DataBases:- https://content.techgig.com/top-5-nosql-databases-for-data-scientists-in-2020/articleshow/78330888.cms
