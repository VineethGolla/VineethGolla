# Vineeth Golla

Software Engineer focused on backend systems, distributed services, and reliable product infrastructure.

I like building systems that are easy to reason about: clear APIs, predictable data flow, sensible failure handling, and code that another engineer can pick up without a map.

## What I work with

| Area | Stack |
| --- | --- |
| Languages | Java, Python, SQL, JavaScript, TypeScript |
| Backend | Spring Boot, Spring WebFlux, REST, gRPC, JPA/Hibernate |
| Distributed systems | Kafka, Flink, Redis, service discovery, event-driven design |
| Data & search | PostgreSQL, MySQL, Solr, OpenSearch |
| Cloud & delivery | AWS, Kubernetes, Docker, Helm, CI/CD |
| Engineering fundamentals | System design, DSA, OOP, concurrency, design patterns |

## Selected work

- [**Payment Service — Stripe Integration**](https://github.com/vineeth016/Payment-Service-Stripe-Integration-) — payment APIs, external service integration, and webhook handling.
- [**User Authentication Service**](https://github.com/vineeth016/User-Authentication-Service) — secure login and registration with Spring Security, JWT, and OAuth2.
- [**Service Discovery**](https://github.com/vineeth016/ServiceDiscovery) — Spring Cloud Eureka service registry for microservice discovery.
- [**Parking Lot Management System**](https://github.com/vineeth016/Parking-Lot-Management-System) — Java low-level design with object-oriented modeling, allocation, tickets, and pricing.

## Currently sharpening

System design, distributed systems, concurrency, and problem solving in Java.

## Quick break — one tiny backend game

A payment provider retries the **same webhook three times** after a timeout. What keeps the service from processing the same payment more than once?

<details>
<summary><b>A. Add more threads</b></summary>

Not quite. More concurrency can make the duplicate-processing problem worse.

</details>

<details>
<summary><b>B. Use an idempotency key</b></summary>

Correct. Store and check a stable event or idempotency key before applying the operation again.

</details>

<details>
<summary><b>C. Increase the timeout</b></summary>

That may reduce retries, but it does not make duplicate delivery safe.

</details>

## Elsewhere

[Portfolio](https://github.com/vineeth016/Portfolio) · [LinkedIn](https://www.linkedin.com/in/vineeth-golla)
