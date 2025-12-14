# cc-streaming-group9
# Cloud Computing Streaming Project – Apache Pulsar with Docker

## Overview
This project demonstrates a cloud-native streaming system using **Apache Pulsar** deployed locally via **Docker**. The system showcases:
- Multi-tenant message streaming
- Exclusive vs Shared subscriptions
- Message throughput and latency measurement
- Reproducible deployment using Docker Compose
- Automated demo using shell scripts

The project is designed for educational purposes and aligns with modern cloud computing principles such as containerization, scalability, and isolation.

---

## Technologies Used
- Apache Pulsar (Standalone mode)
- Docker & Docker Compose
- Bash scripting
- macOS (local testbed)

---

## System Features
- **Multi-tenancy**: Separate tenants (`tenant1`, `tenant2`)
- **Namespaces**: Logical isolation per tenant
- **Topics**: Independent message streams
- **Producers**: Publish messages to topics
- **Consumers**:
  - Exclusive subscription
  - Shared subscription
- **Metrics**:
  - Throughput (messages/sec)
  - Latency (approx.)

---

## Repository Structure
