# __5 Advantages of NoSQL as Mangodb__

## <ins>1. Handle large volumes of data at high speed with a scale-out architecture</ins> :-
* SQL databases are most often implemented in a scale-up architecture, which is based on using ever-larger computers with more CPUs and more memory to improve performance.
* NoSQL databases were created in internet and cloud computing eras that made it possible to more easily implement a scale-out architecture. In a scale-out architecture, scalability is achieved by spreading the storage of data and the work to process the data over a large cluster of computers. To increase capacity, more computers are added to the cluster.
***

## <ins>2. Store unstructured, semi-structured, or structured data</ins> :-
* databases, a data model must be designed and then the data is transformed and loaded into the database.

* When data is used in applications, the data then must be retrieved using SQL, and adapted to the form used in the application. Then, when the data is written back, it must be transformed again back into the relational tables.
* NoSQL databases have proven popular because they allow the data to be stored in ways that are easier to understand or closer to the way the data is used by applications. Fewer transformations are required when the data is stored or retrieved for use. Many different types of data, whether structured, unstructured, or semi-structured, can be stored and retrieved more easily.
***
## <ins>3. Enable easy updates to schemas and fields</ins> :-
* Document databases don’t have a set data structure to start with, so a new document type can be stored just as easily as what is currently being stored.

* With key-value and column-oriented stores, new values and new columns can be added without disrupting the current structure.

* In response to new kinds of data, graph database developers add nodes with new properties and arcs with new meanings.
***
## <ins>4. Be developer-friendly</ins> :-
* Adoption of NoSQL databases has primarily been driven by uptake from developers who find it easier to create various types of applications compared to using relational databases.

* Document databases such as MongoDB use JSON as a way to turn data into something much more like code. This allows the structure of the data to be under the control of the developer.

* In addition, NoSQL databases store data in forms that are close to the kind of data objects used in applications, so fewer transformations are required when moving data in and out of the databases.
***
## <ins>5. Take full advantage of the cloud to deliver zero downtime</ins> :-
* The scale-out architecture that most NoSQL databases use does more than provide a clear path to scaling to accommodate huge datasets and high volumes of traffic. Delivering a database using a cluster of computers also allows the database to expand and contract capacity automatically.

# Reference :-
* [MongoDB No-Sql Reference ](https://www.mongodb.com/nosql-explained)
