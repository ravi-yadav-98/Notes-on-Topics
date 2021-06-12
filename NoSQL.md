## NoSQL
- NoSQL Database is a non-relational Data Management System, that does not require a fixed schema.
- major purpose of using a NoSQL database is for distributed data stores with humongous data storage needs
- NoSQL is used for Big data and real-time web apps
- a NoSQL database system encompasses a wide range of database technologies that can store structured, semi-structured, unstructured and polymorphic data
- **Example:  Documents, key-value pair, graphs etc

### Why NoSQL ?
  - The system response time becomes slow when you use RDBMS for massive volumes of data.
  - To resolve this problem, we could "scale up" our systems by upgrading our existing hardware. This process is expensive.
  - alternative for this issue is to distribute database load on multiple hosts whenever the load increases. This method is known as "scaling out."
  - NoSQL database is non-relational, so it scales out better than relational databases as they are designed with web applications in mind.


- NoSQL is Schema-Free
- Offers easy to use interfaces for storage and querying data provided
- Multiple NoSQL databases can be executed in a distributed fashion

### Types of NoSQL DataBases:
- 1. Key-Value: Key-value pair storage databases store data as a hash table where each key is unique, and the value can be a JSON, BLOB(Binary Large Objects), string, etc.
- 2. Column based: Column-oriented databases work on columns and are based on BigTable paper by Google. Every column is treated separately. 
Values of single column databases are stored contiguously.
- 3. Document-Oriented:Document-Oriented NoSQL DB stores and retrieves data as a key value pair but the value part is stored as a document. 
 The document is stored in JSON or XML formats. 
- 4. Graph-Based: A graph type database stores entities as well the relations amongst those entities. The entity is stored as a node with the relationship as edges. 
An edge gives a relationship between nodes. Every node and edge has a unique identifier.Graph database is a multi-relational in nature

### Query Mechanism tools for NoSQL
- The most common data retrieval mechanism is the REST-based retrieval of a value based on its key/ID with GET resource


## Cap Theorem:
- Consistency
- Availability
- Partition Tolerance

### BASE stands for Basically Available, Soft state, Eventual consistency
#### The term "eventual consistency" means to have copies of data on multiple machines to get high availability and scalability






