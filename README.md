# Real-Time Financial Transaction Monitoring & Alerting System (Kotlin Edition - Advanced Microservices)

I built this sample project to tackle a challenge: keeping financial transactions secure and spotting fraud in real time. It’s a robust, scalable system crafted with Kotlin (version 2.1) and powered by the Spring ecosystem (Spring Boot and Spring Cloud, version 3.5) with Apache Kafka as the backbone for seamless event-driven communication.

Key architectural features:
* **Spring Cloud:** API Gateway, Service Discovery, centralized Configuration Server and Circuit Breakers for enhanced resilience and manageability.
* **gRPC:** For efficient, high-performance, type-safe inter-service communication for specific synchronous internal operations, complementing Kafka's asynchronous event flow.
* **Kafka Streams:** For sophisticated complex event processing and real-time analytics.

I designed this sample project with a mix of distributed systems know-how, software engineering and business applications. It’s been a labor of love, and I’m excited to share it with you!

**Live Demo:** //TODO: `[Link to deployed demo]`
**Related Article:** `[Link]`

## ✨ Features

* **Centralized Entry Point:** Secure API access via **Spring Cloud Gateway**.
* **Dynamic Service Landscape:** Services registered and discoverable via **Spring Cloud Service Discovery** (Eureka).
* **Externalized Configuration:** Application configurations managed by **Spring Cloud Config Server**.
* **Fault Tolerance:** Enhanced system resilience using **Circuit Breakers** (Resilience4j) on inter-service calls (both gRPC and REST).
* **Real-Time Transaction Ingestion:** High-throughput ingestion API.
* **Advanced Anomaly Detection with Kafka Streams:** Stateful processing, joins, windowing and custom Kotlin processors.
* **Efficient Inter-Service Communication:** Use of **gRPC** with Protocol Buffers for performance-critical synchronous internal service calls.
* **Kotlin-Powered Microservices:** Idiomatic Kotlin, coroutines for concurrency.
* **Event-Driven Core:** Logic orchestrated via Kafka events.
* **Modern API Security:** Endpoints secured using Spring Security (OAuth2/JWT), enforced at the Gateway and service levels.
* **Comprehensive Testing:** Unit, integration (including Kafka, gRPC, Spring Cloud components) and contract tests.
* **API Documentation:** Auto-generated OpenAPI 3 documentation (for REST APIs) and clear gRPC service definitions.
* **Containerized:** Fully containerized using Docker and orchestrated with Docker Compose.


