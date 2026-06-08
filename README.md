# 🏛️ Aspect | Systems Engineer

<pre>
    _                     _           
   / \   ___ _ __   ___  | |_   ___   
  / _ \ / __| '_ \ / _ \ | __| / _ \  
 / ___ \\__ \ |_) |  __/ | |_ | (_) | 
/_/   \_\___/ .__/ \___|  \__| \___/  
            |_|                        
</pre>

---

### 💻 Profile Summary

Senior Java Software Developer specializing in **high-concurrency ecosystem engineering**, **multi-provider distributed integrations**, and **secure financial transactions** within the high-throughput iGaming (Gaming Service Provider) sector.

In addition to core enterprise engineering, I design systems from the ground up to experiment with emerging JVM features, assess system topology trade‑offs, and strengthen production‑ready design practices.

---

### 🛠️ Core Engineering & Architectural Stack

| Layer | Technologies & Frameworks | Architectural Principles |
| :--- | :--- | :--- |
| **Runtime & Frameworks** | Java 8–25, Spring Boot (1.5 to 3.x), Spring MVC, Maven, Gradle | Java 21+ Virtual Threads, Records, Sealed Classes, Pattern Matching |
| **HTTP & Integration** | Feign, WebClient, HttpClient (Java 11+), RestTemplate | Decoupled Provider Abstraction Patterns, Strategic Client Selection |
| **Persistence & Cache** | MySQL, JPA / Hibernate (Specifications & Native), Redis, MongoDB | Pessimistic Locking, Explicit Transaction Boundaries, Index Optimization |
| **Security & Resilience** | JWT, OAuth2, Bucket4j Rate Limiting, OWASP Top 10 Sanitization | Concurrency Safety, Thread-safe Data Structures, Circuit Breaking |
| **DevOps & Reliability** | Docker, Docker Compose, GitHub Actions, Jenkins | Spring Boot Actuator, System Monitoring & Health Checks |
| **Quality Assurance** | JUnit 5, Mockito, Integration Testing Architectures | TDD, Design for Testability, SOLID, Explicit-over-Implicit Style |

---

### 📊 System Design Philosophy

<pre>
  [ Client Tier ] ──► [ Rate Limiter / Gateway ]
                             │
                             ▼
                    [ Spring Boot App ] ──► [ Redis Cache ]
                             │
            ┌────────────────┴────────────────┐
            ▼                                 ▼
   [ Relational DB ]                 [ Provider Integration ]
   (MySQL / Locking)                  (WebClient / Feign)
</pre>

*   **Code Quality:** Zero placeholders. Explicit over implicit. Fully realized production-ready implementations with strict SLF4J logging, rigid null-safety, and input validation.
*   **System Topology:** Layered architecture (`Controller` → `Service` → `Repository`), strict interface-driven designs, and a focus on scalability, maintainability, and domain modeling.

---

### 🧮 Tech Stack Ecosystem

![Java](https://img.shields.io/badge/Java-8--25-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-1.5--3.x-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.x-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Cache-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)

---

### 📬 Connect & Collaborate

*   **GitHub:** [![Followers](https://img.shields.io/github/followers/aspect-study?style=social&label=Follow)](https://github.com/aspect-study)
*   **Architectural Reviews:** Open to discussing system design exploration, critical thinking challenges, and deep technical post-mortems.
