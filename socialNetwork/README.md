# Microservices Profiling for Social Networks

This project presents a comprehensive deployment and performance evaluation of the DeathStarBench social network, a microservices-based application. We have integrated a full monitoring stack—including Prometheus, Grafana, Jaeger, cAdvisor, and Blackbox Exporter—to achieve deep observability into the system's performance under various workloads. [cite: 794, 908, 944]

The primary goals were to deploy the application, simulate realistic user traffic using `wrk2`, trace requests with Jaeger, and analyze performance data to identify and address system bottlenecks. [cite: 653, 656, 897, 899]

---

## 📚 Project Documentation

For a detailed breakdown of the project, please see the documents below:

* **[Architecture Deep Dive](docs/ARCHITECTURE.md)**: Understand the system design, communication patterns, and the integrated monitoring stack.
* **[Setup and Usage Guide](docs/SETUP.md)**: Step-by-step instructions to deploy the application, run load tests, and access the monitoring dashboards.
* **[Evaluation and Results](docs/EVALUATION.md)**: A complete analysis of the performance tests, including identified bottlenecks and optimization recommendations.

---

## 🎯 Project Goals

* **Deploy:** Successfully deploy all social network microservices using Docker Compose. [cite: 654, 898]
* **Load Testing:** Execute a realistic read/write workload using `wrk2` to stress-test the system. [cite: 655, 899]
* **Monitoring & Tracing:** Instrument and monitor services using Jaeger, Prometheus, and Grafana to record and visualize performance data. [cite: 656]
* **Bottleneck Identification:** Analyze trace and metrics data to discover performance hotspots and sources of latency. [cite: 657, 900]

---
