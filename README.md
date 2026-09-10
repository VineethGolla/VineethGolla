# Vineeth Golla

Software Engineer focused on backend systems, distributed services, and reliable product infrastructure.

I like building systems that are easy to reason about: clear APIs, predictable data flow, sensible failure handling, and code another engineer can pick up quickly.

**Core stack**  
Java · Spring Boot · Spring WebFlux · REST · gRPC · Kafka · Flink · Redis · PostgreSQL · MySQL · Solr · AWS · Kubernetes · Docker

**Engineering focus**  
System Design · Distributed Systems · DSA · OOP · Concurrency · Event-Driven Architecture · Reliability

**Selected work**

- [Payment Service - Stripe Integration](https://github.com/vineeth016/Payment-Service-Stripe-Integration-) - payment APIs, external service integration, and webhook handling.
- [User Authentication Service](https://github.com/vineeth016/User-Authentication-Service) - Spring Security, JWT, OAuth2, and secure REST APIs.
- [Service Discovery](https://github.com/vineeth016/ServiceDiscovery) - Spring Cloud Eureka service registry for microservice discovery.
- [Parking Lot Management System](https://github.com/vineeth016/Parking-Lot-Management-System) - Java low-level design with allocation, ticketing, and pricing logic.

**Quick backend puzzle**

A payment provider retries the same webhook three times after a timeout. What prevents the payment from being processed three times?

<details>
<summary>Show answer</summary>

Use an **idempotency key** (or stable event ID) and reject/reuse already-processed requests.

</details>

**Links**  
[Portfolio](https://github.com/vineeth016/Portfolio) · [LinkedIn](https://www.linkedin.com/in/vineeth-golla)
