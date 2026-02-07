# Distributed Financial Transaction Processing System

A **cloud-native distributed microservices system** designed to ingest, process, categorize, and analyze financial transactions in real time.

The system leverages **event-driven architecture, asynchronous messaging, and cloud infrastructure** to ensure scalability, reliability, and low-latency processing.

This project demonstrates **distributed systems design, microservices communication, cloud provisioning, and GenAI integration** for practical financial workflow automation.

---

## Architecture Overview

The system follows a **microservices-based, event-driven architecture**:

- Multiple Spring Boot services communicate via **Kafka and RabbitMQ**
- Services are **Dockerized and independently deployable**
- AWS infrastructure is provisioned using **AWS CDK**
- Transaction ingestion is handled through a **Python-based GenAI service**
- Data persistence uses **relational databases with optimized schemas**


---

## Key Features

### Distributed Microservices Architecture
- 8+ Dockerized microservices
- Event-driven communication using Kafka
- Asynchronous workflows using RabbitMQ
- Fault-tolerant service interactions

### GenAI-Powered Transaction Ingestion
- Python ingestion service using **LangChain and LLM APIs**
- Extracts structured transaction data from **unstructured bank SMS**
- Automates expense tracking workflows

### Low-Latency Data Processing
- Optimized SQL schemas using:
  - indexing
  - partitioning
- Designed for **fast categorization and analytics**

### Cloud Infrastructure (AWS CDK)
Infrastructure provisioned programmatically:
- VPC configuration
- EC2 instances
- Load Balancers
- Auto-scaling setup
- High-availability design

---

## Tech Stack

### Backend
- Java
- Spring Boot
- Microservices architecture
- REST APIs

### Messaging & Streaming
- Apache Kafka
- RabbitMQ

### AI / Ingestion
- Python
- LangChain
- LLM APIs

### Cloud & DevOps
- AWS (EC2, VPC, Load Balancers)
- AWS CDK
- Docker

### Database
- MySQL / PostgreSQL

---

## System Design Goals

This project focuses on demonstrating:

- Distributed system communication patterns
- Event-driven processing pipelines
- Cloud infrastructure automation
- Low-latency transaction processing
- Fault-tolerant microservices design
- Integration of LLM workflows into backend systems

---

## Example Use Case

1. Bank SMS arrives
2. GenAI ingestion service extracts:
   - amount
   - merchant
   - timestamp
3. Transaction event published to Kafka
4. Processing services categorize the expense
5. Analytics service updates reports

---

## Why This Project Matters

This project demonstrates the ability to design and implement:

- Distributed microservices systems
- Event-driven architectures
- Cloud-native infrastructure
- AI-assisted data ingestion pipelines

It simulates **real-world financial transaction processing workflows** in a scalable, production-style architecture.



---

## Author

Tanmay Akhil Devikar  
GitHub: https://github.com/TanmayDevikar

LinkedIn: https://www.linkedin.com/in/td1101/