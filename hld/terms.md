# Interview tips
- Requirements (functional, non-functional)
- Core entities
- API
- High level desgin
- Deep dives

# Databases
- Read Heavy Database
  - Content Delivery Networks (CDNs) and Caching Systems
    - Redis: An in-memory key-value store often used for caching to speed up read operations.
    - Memcached: Another in-memory caching system designed for quick data retrieval.

  - E-commerce
    - Amazon DynamoDB: Optimized for fast and consistent read performance, often used in e-commerce for product catalogs.
    - Elasticsearch: Frequently used for searching and filtering product catalogs due to its efficient read capabilities.

  - Social Media
    - Cassandra: Known for its high availability and scalability, suitable for read-heavy workloads like social media feeds.
    - MongoDB: A NoSQL database that can be optimized for read-heavy applications like user profiles.

- Write Heavy Database
  - Financial Transaction Systems
    - PostgreSQL: A relational database known for its reliability and ACID compliance, making it suitable for financial transactions.
    - MySQL (with InnoDB): Another relational database with strong transaction support, commonly used in financial systems.

  - Sensor Data Collection
    - Apache Kafka: While not a traditional database, Kafka is often used as a high-throughput write-heavy pipeline for ingesting sensor data, which is then written to a database like Cassandra.

- Graph DB
  - Neo4j: One of the most widely used graph databases, known for its robust query language (Cypher) and large community.

# Caching

- Write-Through: Data is written to both the cache and storage simultaneously, ensuring consistency but increasing latency.
- Write-Around: Data is written directly to storage, bypassing the cache, reducing cache write load but increasing cache misses.
- Write-Back: Data is written to the cache first and later to storage, improving performance but risking data loss if the cache fails.
- Read-Through: Data is read from the cache; if missing, it's fetched from storage, cached, and returned.
- Read-Around: Data is read directly from storage, skipping the cache, often for data where caching isn't needed.

# Authentication

- Password based
- MFA
- Biometric
- Token based
  - JWT
  - OAuth: Client, Authorization Server, Resource Server, User
 
# Big Data

- Here

# Redis
- Single threaded, in memory, data structure server
- Common commands
  - SET foo 1
  - GET foo            // returns 1
  - INCR foo           // returns 2
- 

# Apache Kafka 
- <img src="https://github.com/user-attachments/assets/4d51b954-6ef2-4ddf-b4df-1e4959ec74fc" width="400" />
- <img src="https://github.com/user-attachments/assets/34333790-6539-4c05-8aef-8439e0293f44" width="400" />
- <img src="https://github.com/user-attachments/assets/63211778-99a3-4020-8744-3a1bd40a16bf" width="400" />

# Some terms

- Changed data capture

- Long polling vs Short polling

