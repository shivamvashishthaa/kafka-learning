# Kafka learning

Welcome to the GitHub Repository for **Kafka learning: To understand the concepts of Kafka**!

This repository is the central hub to understand Kafka — basics to Advance. It is focused on
building a strong conceptual foundation of Kafka.

---

## About

25-30 days Kafka + Spring Boot. Day-wise structured Repository for practise.

---

## Prerequisites

- Basic Java & Spring Boot
- Docker installed
- 8GB+ RAM

---

## Course Structure

### Part 1: Foundation (Day 1-2)

- [ ] System architecture & use cases
- [ ] Tools setup (Java, Docker, MySQL, Redis, Debezium, Kafdrop)

### Part 2: Core Kafka (Day 3-18)

- [ ] Producer/Consumer basics
- [ ] Error Handling + DLQ
- [ ] Transactions & Exactly Once
- [ ] Outbox Pattern
- [ ] Saga Pattern
- [ ] Event Sourcing
- [ ] Schema Registry + Avro
- [ ] Integration Testing

### Part 3: Kafka Connect (Day 19-23)

- [ ] Connect Fundamentals
- [ ] JDBC Connectors
- [ ] Debezium CDC
- [ ] Custom Connectors

### Part 4: Kafka Streams (Day 24-28)

- [ ] Streams Fundamentals
- [ ] Stateless Transformations
- [ ] Stateful Aggregations
- [ ] Joins & Enrichment
- [ ] Interactive Queries

### Part 5: Final Project (Day 29-33)

- [ ] System Integration
- [ ] Monitoring & Observability
- [ ] Security Hardening
- [ ] Deployment

---

## Daily Progress

| Day | Topic                                                       | Status | Notes |
|-----|-------------------------------------------------------------|--------|-------|
| 1   | Kafka Architecture & Real-World Use Cases                   | ⬜     |       |
| 2   | Tools Setup (Java, Docker, MySQL, Redis, Debezium, Kafdrop) | ⬜     |       |
| 3   | Kafka Fundamentals (Topics, Partitions, Offsets)            | ⬜     |       |
| 4   | Spring Boot Producer & Consumer Basics                      | ⬜     |       |
| 5   | Message Serialization & Deserialization                     | ⬜     |       |
| 6   | Order Service as Producer (Hands-on)                        | ⬜     |       |
| 7   | Consumer Groups & Partition Assignment                      | ⬜     |       |
| 8   | Advanced Consumers (Manual Commit, Batch)                   | ⬜     |       |
| 9   | Error Handling, Retries & Dead Letter Topics                | ⬜     |       |
| 10  | Order & Notification Services Integration                   | ⬜     |       |
| 11  | Kafka Configuration Best Practices                          | ⬜     |       |
| 12  | Message Ordering & Keying Strategies                        | ⬜     |       |
| 13  | Schema Registry & Avro Serialization                        | ⬜     |       |
| 14  | Saga Pattern (Distributed Transactions)                     | ⬜     |       |
| 15  | Kafka Connect Fundamentals                                  | ⬜     |       |
| 16  | JDBC Connectors (MySQL/PostgreSQL)                          | ⬜     |       |
| 17  | Debezium CDC (Change Data Capture)                          | ⬜     |       |
| 18  | Schema Registry Advanced + Avro Evolution                   | ⬜     |       |
| 19  | Kafka Streams Fundamentals                                  | ⬜     |       |
| 20  | Streams: Stateless Transformations (map, filter, flatMap)   | ⬜     |       |
| 21  | Streams: Stateful Operations & Aggregations                 | ⬜     |       |
| 22  | Streams: Windowing & Time Semantics                         | ⬜     |       |
| 23  | Streams: Joins & Enrichment Patterns                        | ⬜     |       |
| 24  | Streams: Exactly Once & Interactive Queries                 | ⬜     |       |
| 25  | Integration Testing with Embedded Kafka                     | ⬜     |       |
| 26  | Event Sourcing & Event Replay                               | ⬜     |       |
| 27  | Outbox Pattern (Reliable Publishing)                        | ⬜     |       |
| 28  | Idempotency & Transactions                                  | ⬜     |       |
| 29  | Monitoring & Observability (New Relic, Micrometer)          | ⬜     |       |
| 30  | Performance Tuning & Benchmarking                           | ⬜     |       |
| 31  | Security & Production Hardening                             | ⬜     |       |
| 32  | Deployment Strategies                                       | ⬜     |       |
| 33  | Final Project: E-commerce App (End-to-End)                  | ⬜     |       |

---

## Key Learnings

### Core Kafka

- Kafka architecture: Brokers, Topics, Partitions, Offsets, Replication
- Producer acks, retries, batching, compression
- Consumer groups, rebalancing, offset management
- Delivery semantics: at-most-once, at-least-once, exactly-once

### Spring Boot Integration

- @KafkaListener, KafkaTemplate, ConcurrentKafkaListenerContainerFactory
- Manual vs auto commit strategies
- Error handling with SeekToCurrentErrorHandler, DefaultErrorHandler
- Dead Letter Topic (DLT) configuration

### Advanced Patterns

- **Outbox Pattern**: Database + Kafka atomicity
- **Saga Pattern**: Distributed transaction management (Choreography vs Orchestration)
- **Event Sourcing**: Append-only event log, replay, snapshots
- **CQRS**: Command-Query separation with Kafka
- **Idempotency**: Duplicate-safe processing

### Schema Management

- Avro serialization/deserialization
- Schema Registry integration
- Backward/Forward/Full compatibility
- Schema evolution strategies

### Kafka Connect & CDC

- Source vs Sink connectors
- JDBC connectors for databases
- Debezium for Change Data Capture
- Custom connector development

### Kafka Streams

- KStream, KTable, GlobalKTable
- Stateless: map, filter, flatMap, branch
- Stateful: count, aggregate, reduce
- Windowing: Tumbling, Hopping, Sliding, Session
- Joins: Stream-Stream, Stream-Table, Table-Table
- Interactive Queries for real-time lookups
- Exactly-once processing (processing.guarantee=exactly_once_v2)

### Testing & Monitoring

- Embedded Kafka for integration tests
- Testcontainers for realistic testing
- Micrometer metrics, Prometheus, Grafana
- New Relic APM integration
- Consumer lag monitoring

### Production Best Practices

- Replication factor, min.insync.replicas
- Partition sizing and strategy
- Retention policies (delete vs compact)
- Security: TLS, SASL, ACLs
- Performance tuning for throughput vs latency

---

## 🌟 Star This Repository

If this repository helps you understand Java better, please give it a ⭐.
Your support motivates me to keep creating high-quality, free content.

---

## 📖 How to Use This Repository

1. **Clone the repository:**

```bash
git clone https://github.com/shivamvashishthaa/kafka-learning.git
```

2. **Navigate to the folder:**

```bash
cd kafka-learning
```

3. **Start practising:**
   Just understand the code and start practising on your device.

---

## 📬 Contact

- GitHub: [@ShivamVashishthaa](https://github.com/shivamvashishthaa)
- Email: shivam283097@gmail.com
- LinkedIn: [@shivamvashishtha1](https://www.linkedin.com/in/shivamvashishtha1/)

---
*This repository is my for personal learning. If you find any mistake, please let me know!*