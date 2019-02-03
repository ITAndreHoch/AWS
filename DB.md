**RDS - SQL databases:**

* **Aurora:**
Amazon Aurora is a MySQL and PostgreSQL compatible relational database engine that combines the speed and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases. Amazon Aurora is up to five times faster than standard MySQL databases and three times faster than standard
PostgreSQL databases.

* **Mysql**
* **MariaDB**
* **PostgresSQL**
* **Oracle** 
* **MicrosoftSQL**
* **DB mirroring**, multi-subnet and clustering are not options provided by RDS
Read Replicas are used for read heavy DBs and replication is asynchronous


**DynamoDB - noSQL databases:**

- does NOT provide other noSQL software options
- can replace MongoDB, Cassandra, Oracle NoSQL
- can be scaled without incurring downtime


**ElasticCache** - web service for data caching to improve speed/performance Support two open source in-memory datastore and cache:

- **redis:** a fast, open source, in-memory data store and cache.

- **memcacheD:** a widely adopted memory object caching system



**RedSHIFT**  - data werehouse database to handle petabytes of data ,used for analytic not transactional databases - can be analyzed using SQL tools

Summary:

• Amazon RDS supports complex queries and joins and is suitable for a transactional database deployment

• Amazon DynamoDB is a NoSQL database and does not support to complex queries and joins

• Amazon RedShift is a data warehouse used for analytic not transactional databases

• Amazon EMR is a Hadoop service that is not suitable for transactional databases

***

* Amazon RDS DB snapshots and automated backups are stored in S3.

***
**QUESTIONS:**

* How can you obtain a discount on your RDS database instances?  - Reserved database instance

**AWS Database Migration Service DM** helps you migrate databases to AWS quickly and securely

Q: 
What features does Amazon RDS provide to deliver scalability, availability and durability? (choose 2)

- Multi-AZ: Multi-AZ RDS creates a replica in another AZ and synchronously
- Read Replicas: Read replicas are used for read heavy DBs and replication
