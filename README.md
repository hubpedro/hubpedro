Pedro Barbosa — Backend Developer
Java backend developer focused on distributed systems, event-driven architecture, and concurrency-heavy domains.
I build systems where correctness under load is non-negotiable — reservation platforms that prevent double-bookings under parallel requests, payment services with idempotency guarantees, and APIs with fine-grained authorization beyond simple role checks.

Featured Projects
🎟️ Concert Reservation Platform
A two-service distributed system for concert seat booking.
ServiceWhat it solvesKey techmsreservasConcurrent seat locking — no double-bookings under parallel loadPessimistic Locking (SELECT FOR UPDATE), RabbitMQ, PostgreSQLmspaymentIdempotent payment processing — same payment never charged twiceIdempotency Key pattern, event-driven saga, RabbitMQ

💇 Beautique — Scheduling Microservice
Event-driven appointment system for the beauty domain.
CQRS with PostgreSQL (writes) + MongoDB (read-optimized views), async communication via RabbitMQ.

📚 Bookstore API
Full-featured REST API with JWT authentication, granular permission control (beyond roles), automatic fine calculation for overdue loans, and Optimistic Locking for concurrent stock updates.

Stack
Language   → Java 17/21
Framework  → Spring Boot 3, Spring Security, Spring Data JPA
Messaging  → RabbitMQ (Spring AMQP)
Databases  → PostgreSQL, MongoDB
Tooling    → Docker, Docker Compose, Flyway, MapStruct
Patterns   → CQRS, Event-Driven, Saga (Choreography), Idempotency Key

Currently
Working on legacy Java systems in production (yes, Java 6 + JBoss) while building modern distributed systems on the side.
Focused on bridging that gap — targeting a senior backend position by end of 2025.
