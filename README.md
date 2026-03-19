# Backend System Design for AI

A comprehensive collection of handwritten notes on backend system design concepts for AI applications.

For downloading notes : https://drive.google.com/drive/folders/1HeiTfb70as7mTTbolUF_78RXx68L5zGT?usp=drive_link
## Table of Contents

### Networking, Web & Security

- [1.1. Networking and Web Fundamentals](images/1.1_Networking_and_Web_Fundamentals) — [preview](images/1.1_Networking_and_Web_Fundamentals/01_Networking_and_Web_Fundamentals.jpeg)
- [1.2. Web Sockets + Authentication & Security](images/1.2_Web_Sockets_Authentication_and_Security) — [preview](images/1.2_Web_Sockets_Authentication_and_Security/01_WebSockets.jpeg)
- [1.3. Token Based Auth & Rate Limiting](images/1.3_Token_Based_Auth_and_Rate_Limiting) — [preview](images/1.3_Token_Based_Auth_and_Rate_Limiting/01_Token_Based_Auth.jpeg)
- [1.4. Prompt Injection & PII Masking](images/1.4_Prompt_Injection_and_PII_Masking) — [preview](images/1.4_Prompt_Injection_and_PII_Masking/01_Prompt_Injection.jpeg)
- [1.5. MCP Tool Authorisation](images/1.5_MCP_Tool_Authorisation) — [preview](images/1.5_MCP_Tool_Authorisation/01_MCP_Tool_Authorisation.jpeg)

### Databases

- [2.1. Database Fundamentals](images/2.1_Database_Fundamentals) — [preview](images/2.1_Database_Fundamentals/01_Database_and_Storage_Fundamentals.jpeg)
- [2.2. Indexes, Query Optimisation, Normalisation & Denormalisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation) — [preview](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/01_Database_Optimisation.jpeg)
- [2.3. Bloom Filter & Location Based Databases](images/2.3_Bloom_Filter_and_Location_Based_Databases) — [preview](images/2.3_Bloom_Filter_and_Location_Based_Databases/01_Bloom_Filters.jpeg)
- [2.4. Sharding & Replication](images/2.4_Sharding_and_Replication) — [preview](images/2.4_Sharding_and_Replication/01_Distributed_Databases.jpeg)
- [2.5. DB Migration, Connection Pooling & NoSQL Optimisation](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation) — [preview](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/01_DB_Migration.jpeg)

### Vector DB & Search

- [3. Vector DB, Metadata Filtering & Hybrid Search](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search) — [preview](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/01_AI_Specific_Storage.jpeg)

### Caching

- [4.1. Caching, Types of Caching, Redis and CDN](images/4.1_Caching_Types_of_Caching_Redis_and_CDN) — [preview](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/01_Caching.jpeg)
- [4.2. Distributed Caching, Cache Replacement Policies, Thrashing, AI Based Caching](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching) — [preview](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/01_Distributed_Caching.jpeg)

### System Design & Architecture

- [5.1. System Design](images/5.1_System_Design) — [preview](images/5.1_System_Design/01_System_Design.jpeg)
- [5.2. Monolith vs Microservices](images/5.2_Monolith_vs_Microservices) — [preview](images/5.2_Monolith_vs_Microservices/01_Monolith_vs_Microservices.jpeg)
- [5.3. Scaling, Load Balancing, Capacity Estimation, Consistent Hashing](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing) — [preview](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/01_Scaling.jpeg)
- [5.4. API Design, Patterns, GraphQL, gRPC, Streaming APIs for LLMs](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs) — [preview](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/01_REST_API_Design.jpeg)

- [5.5. Message Queues Kafka RabbitMQ Pub Sub model Event driven architecture DB as queues](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues) — [preview](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/01_Mes_cage_lay.jpeg)
---

## 1.1. Networking and Web Fundamentals

### Networking and Web Fundamentals

[Networking and Web Fundamentals](images/1.1_Networking_and_Web_Fundamentals/01_Networking_and_Web_Fundamentals.jpeg)

### What Happens When You Enter google.com

[What Happens When You Enter google.com](images/1.1_Networking_and_Web_Fundamentals/02_What_Happens_When_You_Enter_google.com.jpeg)

### DNS

[DNS](images/1.1_Networking_and_Web_Fundamentals/03_DNS.jpeg)

### DNS Records

[DNS Records](images/1.1_Networking_and_Web_Fundamentals/04_DNS_Records.jpeg)

---

## 1.2. Web Sockets + Authentication & Security

### WebSockets

[WebSockets](images/1.2_Web_Sockets_Authentication_and_Security/01_WebSockets.jpeg)

### Authentication and Security

[Authentication and Security](images/1.2_Web_Sockets_Authentication_and_Security/02_Authentication_and_Security.jpeg)

### Sessions

[Sessions](images/1.2_Web_Sockets_Authentication_and_Security/03_Sessions.jpeg)

### Hashing and Salting

[Hashing and Salting](images/1.2_Web_Sockets_Authentication_and_Security/04_Hashing_and_Salting.jpeg)

---

## 1.3. Token Based Auth & Rate Limiting

### Token Based Auth

[Token Based Auth](images/1.3_Token_Based_Auth_and_Rate_Limiting/01_Token_Based_Auth.jpeg)

### Access Control List and Rule Engine

[Access Control List and Rule Engine](images/1.3_Token_Based_Auth_and_Rate_Limiting/02_Access_Control_List_and_Rule_Engine.jpeg)

### Rate Limiting

[Rate Limiting](images/1.3_Token_Based_Auth_and_Rate_Limiting/03_Rate_Limiting.jpeg)

### Distributed Rate Limiting

[Distributed Rate Limiting](images/1.3_Token_Based_Auth_and_Rate_Limiting/04_Distributed_Rate_Limiting.jpeg)

---

## 1.4. Prompt Injection & PII Masking

### API Keys

[API Keys](images/1.4_Prompt_Injection_and_PII_Masking/02_API_Keys.jpeg)

### Prompt Injection

[Prompt Injection](images/1.4_Prompt_Injection_and_PII_Masking/01_Prompt_Injection.jpeg)

### PII Masking Implementation

[PII Masking Implementation](images/1.4_Prompt_Injection_and_PII_Masking/03_PII_Masking_Implementation.jpeg)

---

## 1.5. MCP Tool Authorisation

### MCP Tool Authorisation

[MCP Tool Authorisation](images/1.5_MCP_Tool_Authorisation/01_MCP_Tool_Authorisation.jpeg)

### Checklist Before Executing a Tool

[Checklist Before Executing a Tool](images/1.5_MCP_Tool_Authorisation/02_Checklist_Before_Executing_a_Tool.jpeg)

---

## 2.1. Database Fundamentals

### Database and Storage Fundamentals

[Database and Storage Fundamentals](images/2.1_Database_Fundamentals/01_Database_and_Storage_Fundamentals.jpeg)

### SQL vs NoSQL

[SQL vs NoSQL](images/2.1_Database_Fundamentals/02_SQL_vs_NoSQL.jpeg)

### NoSQL Types

[NoSQL Types](images/2.1_Database_Fundamentals/03_NoSQL_Types.jpeg)

### Transactions

[Transactions](images/2.1_Database_Fundamentals/04_Transactions.jpeg)

---

## 2.2. Indexes, Query Optimisation, Normalisation & Denormalisation

### Database Optimisation

[Database Optimisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/01_Database_Optimisation.jpeg)

### Indexing Strategies

[Indexing Strategies](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/02_Indexing_Strategies.jpeg)

### Query Optimisation

[Query Optimisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/03_Query_Optimisation.jpeg)

### Normalisation vs Denormalisation

[Normalisation vs Denormalisation](images/2.2_Indexes_Query_Optimisation_Normalisation_and_Denormalisation/04_Normalisation_vs_Denormalisation.jpeg)

---

## 2.3. Bloom Filter & Location Based Databases

### Bloom Filters

[Bloom Filters](images/2.3_Bloom_Filter_and_Location_Based_Databases/01_Bloom_Filters.jpeg)

### Location Based Databases

[Location Based Databases](images/2.3_Bloom_Filter_and_Location_Based_Databases/02_Location_Based_Databases.jpeg)

---

## 2.4. Sharding & Replication

### Distributed Databases

[Distributed Databases](images/2.4_Sharding_and_Replication/01_Distributed_Databases.jpeg)

### Types of Sharding

[Types of Sharding](images/2.4_Sharding_and_Replication/02_Types_of_Sharding.jpeg)

### Replication

[Replication](images/2.4_Sharding_and_Replication/03_Replication.jpeg)

---

## 2.5. DB Migration, Connection Pooling & NoSQL Optimisation

### NoSQL Optimisation

[NoSQL Optimisation](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/02_NoSQL_Optimisation.jpeg)

### DB Migration

[DB Migration](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/01_DB_Migration.jpeg)

### Connection Pooling

[Connection Pooling](images/2.5_DB_Migration_Connection_Pooling_and_NoSQL_Optimisation/03_Connection_Pooling.jpeg)

---

## 3. Vector DB, Metadata Filtering & Hybrid Search

### AI Specific Storage

[AI Specific Storage](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/01_AI_Specific_Storage.jpeg)

### Why Indexing

[Why Indexing](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/02_Why_Indexing.jpeg)

### Embedding Storage

[Embedding Storage](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/03_Embedding_Storage.jpeg)

### Metadata Filtering

[Metadata Filtering](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/04_Metadata_Filtering.jpeg)

### Hybrid Search

[Hybrid Search](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/05_Hybrid_Search.jpeg)

### RAG and Document Retrieval

[RAG and Document Retrieval](images/3_Vector_DB_Metadata_Filtering_and_Hybrid_Search/06_RAG_and_Document_Retrieval.jpeg)

---

## 4.1. Caching, Types of Caching, Redis and CDN

### Caching

[Caching](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/01_Caching.jpeg)

### Caching Strategies

[Caching Strategies](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/02_Caching_Strategies.jpeg)

### Redis

[Redis](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/03_Redis.jpeg)

### Content Delivery Network

[Content Delivery Network](images/4.1_Caching_Types_of_Caching_Redis_and_CDN/04_Content_Delivery_Network.jpeg)

---

## 4.2. Distributed Caching, Cache Replacement Policies, Thrashing, AI Based Caching

### Distributed Caching

[Distributed Caching](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/01_Distributed_Caching.jpeg)

### Cache Replacement Policies

[Cache Replacement Policies](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/02_Cache_Replacement_Policies.jpeg)

### Cache Thrashing

[Cache Thrashing](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/03_Cache_Thrashing.jpeg)

### AI Response Caching

[AI Response Caching](images/4.2_Distributed_Caching_Cache_Replacement_Policies_and_AI_Caching/04_AI_Response_Caching.jpeg)

---

## 5.1. System Design

### System Design

[System Design](images/5.1_System_Design/01_System_Design.jpeg)

### Trade-offs and Limitations

[Trade-offs and Limitations](images/5.1_System_Design/02_Trade_offs_and_Limitations.jpeg)

---

## 5.2. Monolith vs Microservices

### Monolith vs Microservices

[Monolith vs Microservices](images/5.2_Monolith_vs_Microservices/01_Monolith_vs_Microservices.jpeg)

### Microservices Architecture

[Microservices Architecture](images/5.2_Monolith_vs_Microservices/02_Microservices_Architecture.jpeg)

### Monolith to Microservice Migration

[Monolith to Microservice Migration](images/5.2_Monolith_vs_Microservices/03_Monolith_to_Microservice_Migration.jpeg)

---

## 5.3. Scaling, Load Balancing, Capacity Estimation, Consistent Hashing

### Scaling

[Scaling](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/01_Scaling.jpeg)

### Real System Example

[Real System Example](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/02_Real_System_Example.jpeg)

### Capacity Estimation

[Capacity Estimation](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/03_Capacity_Estimation.jpeg)

### Load Balancing

[Load Balancing](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/04_Load_Balancing.jpeg)

### Consistent Hashing

[Consistent Hashing](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/05_Consistent_Hashing.jpeg)

### Virtual Nodes

[Virtual Nodes](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/06_Virtual_Nodes.jpeg)

### Scaling LLM Workloads

[Scaling LLM Workloads](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/07_Scaling_LLM_Workloads.jpeg)

### Cost Based Scaling

[Cost Based Scaling](images/5.3_Scaling_Load_Balancing_Capacity_Estimation_Consistent_Hashing/08_Cost_Based_Scaling.jpeg)

---

## 5.4. API Design, Patterns, GraphQL, gRPC, Streaming APIs for LLMs

### REST API Design

[REST API Design](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/01_REST_API_Design.jpeg)

### Best Practices in REST API Design

[Best Practices in REST API Design](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/02_Best_Practices_in_REST_API_Design.jpeg)

### GraphQL

[GraphQL](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/03_GraphQL.jpeg)

### gRPC

[gRPC](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/04_gRPC.jpeg)

### Asynchronous APIs

[Asynchronous APIs](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/05_Asynchronous_APIs.jpeg)

### API Gateway Pattern

[API Gateway Pattern](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/06_API_Gateway_Pattern.jpeg)

### Backend for Frontend

[Backend for Frontend](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/07_Backend_for_Frontend.jpeg)

### Streaming APIs for LLMs

[Streaming APIs for LLMs](images/5.4_API_Design_Patterns_GraphQL_gRPC_Streaming_APIs_for_LLMs/08_Streaming_APIs_for_LLMs.jpeg)

---

## Adding New Notes

Scanned PDFs (e.g. from iPhone's **Scan Documents** feature) are processed automatically. Follow the naming convention below and simply push the PDF — a GitHub Actions workflow will convert each page to a JPEG, update this README, and remove the PDF.

### Naming convention

| What you upload | Where the images land |
|---|---|
| `{N.M}_{Topic_Name}.pdf` | `images/{N.M}_{Topic_Name}/` |

**Examples:**

```
# Single-page PDF
6.1_Message_Queues.pdf              →  images/6.1_Message_Queues/01_6.1_Message_Queues.jpeg

# Multi-page PDF — each page is named after its heading (extracted via OCR)
6.2_Event_Driven_Architecture.pdf   →  images/6.2_Event_Driven_Architecture/01_Event_Driven_Architecture.jpeg
                                       images/6.2_Event_Driven_Architecture/02_Kafka_Internals.jpeg
                                       images/6.2_Event_Driven_Architecture/03_Dead_Letter_Queues.jpeg
                                       …
```

**Multi-page PDFs**: the workflow reads each page in upload order (not lexicographic order) and extracts the heading using a two-step strategy:
1. **`pdftotext`** — reads the embedded OCR text from the PDF (iPhone's Scan Documents embeds this automatically). The first 5 non-blank lines are scanned to find a usable heading.
2. **`tesseract`** — if `pdftotext` yields nothing usable, the workflow runs Tesseract OCR directly on the converted JPEG image as a fallback.

If neither method extracts a heading, the page falls back to `{name}_page_01.jpeg`, `{name}_page_02.jpeg`, ….

### Repairing existing images

If any folder already contains images with fallback names (ending in `_page_NN.jpeg`), you can repair them automatically by triggering the workflow manually from the GitHub Actions tab — no new PDF upload required.

> **Tips:**
> - Name the PDF exactly as you want the folder and README section to appear, using underscores instead of spaces (e.g. `6.1_Message_Queues_and_Kafka.pdf`).
> - Spaces, dots, and other special characters in the PDF filename are automatically converted to underscores.
> - For best topic-wise naming, ensure each page starts with a clearly written heading — iPhone's OCR will pick it up automatically.

---

## 5.5. Message Queues Kafka RabbitMQ Pub Sub model Event driven architecture DB as queues

### Mes cage lay

[Mes cage lay](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/01_Mes_cage_lay.jpeg)

### Natix event sheanung ova

[Natix event sheanung ova](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/02_Natix_event_sheanung_ova.jpeg)

### cK QueLiE 4

[cK QueLiE 4](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/03_cK_QueLiE_4.jpeg)

### Publish Subseri be Modof

[Publish Subseri be Modof](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/04_Publish_Subseri_be_Modof.jpeg)

### Evert Diiwen Archi tecture

[Evert Diiwen Archi tecture](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/05_Evert_Diiwen_Archi_tecture.jpeg)

### eye 7

[eye 7](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/06_eye_7.jpeg)

### Ez workloads like LLM calls embedding generaon bat

[Ez workloads like LLM calls embedding generaon bat](images/5.5_Message_Queues_Kafka_RabbitMQ_Pub_Sub_model_Event_driven_architecture_DB_as_queues/07_Ez_workloads_like_LLM_calls_embedding_generaon_bat.jpeg)

