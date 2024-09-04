# Databases

## 1. Read Heavy Database

### i. Content Delivery Networks (CDNs) and Caching Systems
- **Redis**: An in-memory key-value store often used for caching to speed up read operations.
- **Memcached**: Another in-memory caching system designed for quick data retrieval.

### ii. E-commerce
- **Amazon DynamoDB**: Optimized for fast and consistent read performance, often used in e-commerce for product catalogs.
- **Elasticsearch**: Frequently used for searching and filtering product catalogs due to its efficient read capabilities.

### iii. Social Media
- **Cassandra**: Known for its high availability and scalability, suitable for read-heavy workloads like social media feeds.
- **MongoDB**: A NoSQL database that can be optimized for read-heavy applications like user profiles.

## 2. Write Heavy Database

### i. Financial Transaction Systems
- **PostgreSQL**: A relational database known for its reliability and ACID compliance, making it suitable for financial transactions.
- **MySQL (with InnoDB)**: Another relational database with strong transaction support, commonly used in financial systems.

### ii. Sensor Data Collection
- **Apache Kafka**: While not a traditional database, Kafka is often used as a high-throughput write-heavy pipeline for ingesting sensor data, which is then written to a database like Cassandra.

## 3. Graph DB
- **Neo4j**: One of the most widely used graph databases, known for its robust query language (Cypher) and large community.
