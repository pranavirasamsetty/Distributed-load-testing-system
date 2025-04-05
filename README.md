# Distributed-load-testing-system

A scalable and efficient Distributed Load Testing System.This system is built to simulate high-load scenarios on web servers using multiple distributed nodes, with Kafka serving as the messaging backbone for seamless communication.

---

## What This Project Does

This system simulates realistic and large-scale traffic on a target server to test its performance under load. It uses multiple **Driver Nodes** coordinated by a central **Orchestrator**, all communicating via **Kafka**. You can configure different types of load tests like **Avalanche** or **Tsunami**, track live metrics, and scale the number of Driver Nodes as needed.

---

## How to Use It

### ✅ Prerequisites
- Python 3.x
- Kafka running on `localhost:9092`
- Flask (`pip install flask`)

---
