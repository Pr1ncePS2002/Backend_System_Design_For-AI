# Backend System Design for AI

A comprehensive collection of handwritten notes on backend system design concepts for AI applications.

> **Note:** The original scanned PDFs are available in the repository root. Below are the rendered page images for easy viewing directly on GitHub.

## Table of Contents

### Networking, Web & Security

- [1.1. Networking and Web Fundamentals](#11-networking-and-web-fundamentals) ([PDF](1.1.%20Networking%20and%20Web%20Fundamentals.pdf))
- [1.2. Web Sockets + Authentication & Security](#12-web-sockets--authentication--security) ([PDF](1.2.%20Web%20Sockets%20%2B%20Authentication%20%26%20Security%20.pdf))
- [1.3. Token Based Auth & Rate Limiting](#13-token-based-auth--rate-limiting) ([PDF](1.3.%20Token%20Based%20Auth%20%26%20Rate%20Limiting%20.pdf))
- [1.4. Prompt Injection & PII masking](#14-prompt-injection--pii-masking) ([PDF](1.4.%20Prompt%20Injection%20%26%20PII%20masking.pdf))
- [1.5. MCP Tool Authorisation](#15-mcp-tool-authorisation) ([PDF](1.5.%20MCP%20Tool%20Authorisation%20.pdf))

### Databases

- [2.1. Database Fundamentals](#21-database-fundamentals) ([PDF](2.1.%20Database%20Fundamentals%20.pdf))
- [2.2. Indexes, Query Optimisation, Normalisation ve Denormalisation](#22-indexes-query-optimisation-normalisation-ve-denormalisation) ([PDF](2.2.%20Indexes%2C%20Query%20Optimisation%2C%20Normalisation%20ve%20Denormalisation.pdf))
- [2.3. Bloom Filter & Location based databases](#23-bloom-filter--location-based-databases) ([PDF](2.3.%20Bloom%20Filter%20%26%20Location%20based%20databases%20.pdf))
- [2.4. Sharding & Replication](#24-sharding--replication) ([PDF](2.4.%20Sharding%20%26%20Replication.pdf))
- [2.5. DB Migration, Connection Pooling & NoSQL Optimisation](#25-db-migration-connection-pooling--nosql-optimisation) ([PDF](2.5.%20DB%20Migration%2C%20Connection%20Pooling%20%26%20NoSQL%20Optimisation%20.pdf))

### Vector DB & Search

- [3. Vector DB, Metadata Filtering & Hybrid Search](#3-vector-db-metadata-filtering--hybrid-search) ([PDF](3.%20Vector%20DB%2C%20Metadata%20Filtering%20%26%20Hybrid%20Search%20.pdf))

### Caching

- [4.1. Caching, Types of Caching, Redis and CDN](#41-caching-types-of-caching-redis-and-cdn) ([PDF](4.1.%20Caching%20%2C%20Types%20of%20Caching%2C%20Redis%20and%20CDN.pdf))
- [4.2. Distributed Caching, Cache Replacement Policies, Thrashing, AI based caching](#42-distributed-caching-cache-replacement-policies-thrashing-ai-based-caching) ([PDF](4.2.%20Distributed%20Caching%2C%20Cache%20Replacement%20Policies%2C%20Thrasing%2C%20AI%20based%20caching%20.pdf))

### System Design & Architecture

- [5.1. System Design](#51-system-design) ([PDF](5.1.%20System%20Design.pdf))
- [5.2. Monolith vs Microservices](#52-monolith-vs-microservices) ([PDF](5.2.%20Monolith%20vs%20Microservices%20.pdf))
- [5.3. Scaling, Load Balancing, Capacity Estimation, Consistent Hashing](#53-scaling-load-balancing-capacity-estimation-consistent-hashing) ([PDF](5.3.%20Scaling%20%2C%20Load%20Balancing%2C%20Capacity%20Estimation%2C%20Consistent%20Hashing%20.pdf))

---

## 1.1. Networking and Web Fundamentals

📄 [View original PDF](1.1.%20Networking%20and%20Web%20Fundamentals.pdf)

### Networking and Web Fundamentals

![Networking and Web Fundamentals](images/1.1_Networking_and_Web_Fundamentals/Networking_and_Web_Fundamentals.jpeg)

### What Happens When You Enter google.com

![What Happens When You Enter google.com](images/1.1_Networking_and_Web_Fundamentals/What_Happens_When_You_Enter_google.com.jpeg)

### DNS

![DNS](images/1.1_Networking_and_Web_Fundamentals/DNS.jpeg)

### DNS Records

![DNS Records](images/1.1_Networking_and_Web_Fundamentals/DNS_Records.jpeg)

---

## 1.2. Web Sockets + Authentication & Security

📄 [View original PDF](1.2.%20Web%20Sockets%20%2B%20Authentication%20%26%20Security%20.pdf)

### WebSockets

![WebSockets](images/1.2_Web_Sockets_Authentication_and_Security/WebSockets.jpeg)

### Authentication and Security

![Authentication and Security](images/1.2_Web_Sockets_Authentication_and_Security/Authentication_and_Security.jpeg)

### Sessions

![Sessions](images/1.2_Web_Sockets_Authentication_and_Security/Sessions.jpeg)

### Hashing and Salting

![Hashing and Salting](images/1.2_Web_Sockets_Authentication_and_Security/Hashing_and_Salting.jpeg)

---

## 1.3. Token Based Auth & Rate Limiting

📄 [View original PDF](1.3.%20Token%20Based%20Auth%20%26%20Rate%20Limiting%20.pdf)

### Token Based Auth

![Token Based Auth](images/1.3_Token_Based_Auth_and_Rate_Limiting/Token_Based_Auth.jpeg)

### Access Control List and Rule Engine

![Access Control List and Rule Engine](images/1.3_Token_Based_Auth_and_Rate_Limiting/Access_Control_List_and_Rule_Engine.jpeg)

### Rate Limiting

![Rate Limiting](images/1.3_Token_Based_Auth_and_Rate_Limiting/Rate_Limiting.jpeg)

### Distributed Rate Limiting

![Distributed Rate Limiting](images/1.3_Token_Based_Auth_and_Rate_Limiting/Distributed_Rate_Limiting.jpeg)

---

## 1.4. Prompt Injection & PII Masking

📄 [View original PDF](1.4.%20Prompt%20Injection%20%26%20PII%20masking.pdf)

### API Keys

![API Keys](images/1.4_Prompt_Injection_and_PII_Masking/API_Keys.jpeg)

### Prompt Injection

![Prompt Injection](images/1.4_Prompt_Injection_and_PII_Masking/Prompt_Injection.jpeg)

### PII Masking Implementation

![PII Masking Implementation](images/1.4_Prompt_Injection_and_PII_Masking/PII_Masking_Implementation.jpeg)

---

## 1.5. MCP Tool Authorisation

📄 [View original PDF](1.5.%20MCP%20Tool%20Authorisation%20.pdf)

### MCP Tool Authorisation

![MCP Tool Authorisation](images/1.5_MCP_Tool_Authorisation/MCP_Tool_Authorisation.jpeg)

### Checklist Before Executing a Tool

![Checklist Before Executing a Tool](images/1.5_MCP_Tool_Authorisation/Checklist_Before_Executing_a_Tool.jpeg)

---

## 2.1. Database Fundamentals

📄 [View original PDF](2.1.%20Database%20Fundamentals%20.pdf)

### Database and Storage Fundamentals

![Database and Storage Fundamentals](images/2.1_Database_Fundamentals/Database_and_Storage_Fundamentals.jpeg)

### SQL vs NoSQL

![SQL vs NoSQL](images/2.1_Database_Fundamentals/SQL_vs_NoSQL.jpeg)

### NoSQL Types

![NoSQL Types](images/2.1_Database_Fundamentals/NoSQL_Types.jpeg)

### Transactions

![Transactions](images/2.1_Database_Fundamentals/Transactions.jpeg)

---

## 2.2. Indexes, Query Optimisation, Normalisation ve Denormalisation

📄 [View original PDF](2.2.%20Indexes%2C%20Query%20Optimisation%2C%20Normalisation%20ve%20Denormalisation.pdf)

### Database Optimisation

![Database Optimisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/Database_Optimisation.jpeg)

### Indexing Strategies

![Indexing Strategies](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/Indexing_Strategies.jpeg)

### Query Optimisation

![Query Optimisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/Query_Optimisation.jpeg)

### Normalisation vs Denormalisation

![Normalisation vs Denormalisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/Normalisation_vs_Denormalisation.jpeg)

---

## 2.3. Bloom Filter & Location Based Databases

📄 [View original PDF](2.3.%20Bloom%20Filter%20%26%20Location%20based%20databases%20.pdf)

### Bloom Filters

![Bloom Filters](images/2.3_Bloom_Filter_and_Location_Based_Databases/Bloom_Filters.jpeg)

### Location Based Databases

![Location Based Databases](images/2.3_Bloom_Filter_and_Location_Based_Databases/Location_Based_Databases.jpeg)

---

## 2.4. Sharding & Replication

📄 [View original PDF](2.4.%20Sharding%20%26%20Replication.pdf)

### Distributed Databases

![Distributed Databases](images/2.4_Sharding_and_Replication/Distributed_Databases.jpeg)

### Types of Sharding

![Types of Sharding](images/2.4_Sharding_and_Replication/Types_of_Sharding.jpeg)

### Replication

![Replication](images/2.4_Sharding_and_Replication/Replication.jpeg)

---

## 2.5. DB Migration, Connection Pooling & NoSQL Optimisation

📄 [View original PDF](2.5.%20DB%20Migration%2C%20Connection%20Pooling%20%26%20NoSQL%20Optimisation%20.pdf)

### NoSQL Optimisation

![NoSQL Optimisation](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/NoSQL_Optimisation.jpeg)

### DB Migration

![DB Migration](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/DB_Migration.jpeg)

### Connection Pooling

![Connection Pooling](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/Connection_Pooling.jpeg)

---

## 3. Vector DB, Metadata Filtering & Hybrid Search

📄 [View original PDF](3.%20Vector%20DB%2C%20Metadata%20Filtering%20%26%20Hybrid%20Search%20.pdf)

### AI Specific Storage

![AI Specific Storage](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/AI_Specific_Storage.jpeg)

### Why Indexing

![Why Indexing](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/Why_Indexing.jpeg)

### Embedding Storage

![Embedding Storage](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/Embedding_Storage.jpeg)

### Metadata Filtering

![Metadata Filtering](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/Metadata_Filtering.jpeg)

### Hybrid Search

![Hybrid Search](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/Hybrid_Search.jpeg)

### RAG and Document Retrieval

![RAG and Document Retrieval](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/RAG_and_Document_Retrieval.jpeg)

---

## 4.1. Caching, Types of Caching, Redis and CDN

📄 [View original PDF](4.1.%20Caching%20%2C%20Types%20of%20Caching%2C%20Redis%20and%20CDN.pdf)

### Caching

![Caching](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/Caching.jpeg)

### Caching Strategies

![Caching Strategies](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/Caching_Strategies.jpeg)

### Redis

![Redis](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/Redis.jpeg)

### Content Delivery Network

![Content Delivery Network](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/Content_Delivery_Network.jpeg)

---

## 4.2. Distributed Caching, Cache Replacement Policies, Thrashing, AI Based Caching

📄 [View original PDF](4.2.%20Distributed%20Caching%2C%20Cache%20Replacement%20Policies%2C%20Thrasing%2C%20AI%20based%20caching%20.pdf)

### Distributed Caching

![Distributed Caching](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/Distributed_Caching.jpeg)

### Cache Replacement Policies

![Cache Replacement Policies](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/Cache_Replacement_Policies.jpeg)

### Cache Thrashing

![Cache Thrashing](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/Cache_Thrashing.jpeg)

### AI Response Caching

![AI Response Caching](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/AI_Response_Caching.jpeg)

---

## 5.1. System Design

📄 [View original PDF](5.1.%20System%20Design.pdf)

### System Design

![System Design](images/5.1_System_Design/System_Design.jpeg)

### Trade-offs and Limitations

![Trade-offs and Limitations](images/5.1_System_Design/Trade_offs_and_Limitations.jpeg)

---

## 5.2. Monolith vs Microservices

📄 [View original PDF](5.2.%20Monolith%20vs%20Microservices%20.pdf)

### Monolith vs Microservices

![Monolith vs Microservices](images/5.2_Monolith_vs_Microservices/Monolith_vs_Microservices.jpeg)

### Microservices Architecture

![Microservices Architecture](images/5.2_Monolith_vs_Microservices/Microservices_Architecture.jpeg)

### Monolith to Microservice Migration

![Monolith to Microservice Migration](images/5.2_Monolith_vs_Microservices/Monolith_to_Microservice_Migration.jpeg)

---

## 5.3. Scaling, Load Balancing, Capacity Estimation, Consistent Hashing

📄 [View original PDF](5.3.%20Scaling%20%2C%20Load%20Balancing%2C%20Capacity%20Estimation%2C%20Consistent%20Hashing%20.pdf)

### Scaling

![Scaling](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Scaling.jpeg)

### Real System Example

![Real System Example](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Real_System_Example.jpeg)

### Capacity Estimation

![Capacity Estimation](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Capacity_Estimation.jpeg)

### Load Balancing

![Load Balancing](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Load_Balancing.jpeg)

### Consistent Hashing

![Consistent Hashing](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Consistent_Hashing.jpeg)

### Virtual Nodes

![Virtual Nodes](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Virtual_Nodes.jpeg)

### Scaling LLM Workloads

![Scaling LLM Workloads](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Scaling_LLM_Workloads.jpeg)

### Cost Based Scaling

![Cost Based Scaling](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/Cost_Based_Scaling.jpeg)

---
