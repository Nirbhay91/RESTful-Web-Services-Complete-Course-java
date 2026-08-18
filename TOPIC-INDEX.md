# RESTful Web Services — Complete Topic Index

A structured, interview-focused navigation page for the complete REST/JAX-RS course.

> **How to use:** Topics marked **📘** are already covered in `README.md`. Topics marked **⭐** are important additions to study for a 5-year Java/Spring interview even if they are not separate chapters in this repository.

---

## 📚 Part 1 — REST Fundamentals

### 1. Designing RESTful Services
- 📘 [REST — Representational State Transfer](README.md#rest-representational-state-transfer)
- 📘 [REST and the Rebirth of HTTP in Java](README.md#rest-is-an-architectural-style-for-designing)
- 📘 [RESTful Architectural Principles](README.md#restful-architectural-principles)
  - Statelessness
  - Client–Server
  - Cacheability
  - Uniform Interface
  - Layered System
  - Code-on-Demand
- 📘 [Object Model](README.md#the-object-model)
- 📘 [Model the URIs](README.md#model-the-uris)
- 📘 [Defining Data Formats](README.md#defining-data-formats)
- 📘 [Assigning HTTP Methods](README.md#assigning-http-methods)

### 2. HTTP Methods & URI Matching
- 📘 Developing a JAX-RS RESTful Service
- 📘 Deploying RESTful Service
- 📘 Binding HTTP Methods
- 📘 Subresource Locators
- ⭐ Safe vs Unsafe HTTP Methods
- ⭐ Idempotent vs Non-Idempotent Methods
- ⭐ `GET` vs `POST` vs `PUT` vs `PATCH` vs `DELETE`
- ⭐ `PUT` vs `PATCH`
- ⭐ `HEAD` and `OPTIONS`
- ⭐ URI vs URL vs URN

### 3. JAX-RS Injection
- 📘 `@PathParam`
- 📘 `@MatrixParam`
- 📘 `@QueryParam`
- 📘 `@FormParam`
- 📘 `@HeaderParam`
- 📘 `@CookieParam`
- 📘 Common Functionality
- ⭐ `@DefaultValue`
- ⭐ Request/Response context

### 4. JAX-RS Content Handlers
- 📘 Built-in Content Marshalling — JAXB
- 📘 Custom Marshalling
- ⭐ Serialization vs Deserialization
- ⭐ Marshalling vs Unmarshalling
- ⭐ JSON vs XML
- ⭐ Jackson basics

### 5. Response Codes, Complex Responses & Exception Handling
- 📘 Default Response Codes
- 📘 Complex Responses
- 📘 Exception Handling
- ⭐ `200`, `201`, `202`, `204`
- ⭐ `400`, `401`, `403`, `404`, `409`, `422`, `429`
- ⭐ `500`, `502`, `503`, `504`
- ⭐ `401 Unauthorized` vs `403 Forbidden`
- ⭐ Consistent Error Response / Error Contract
- ⭐ Global Exception Handling

---

## 🚀 Part 2 — Advanced REST

### 6. HTTP Content Negotiation
- 📘 [Content Negotiation — Conneg](README.md#http-content-negotiation)
- 📘 Language Negotiation
- 📘 Encoding Negotiation
- 📘 JAX-RS and Conneg
- 📘 Leveraging Content Negotiation
- ⭐ `Accept` vs `Content-Type`
- ⭐ `Accept-Language`
- ⭐ `Accept-Encoding`
- ⭐ `406 Not Acceptable` vs `415 Unsupported Media Type`

### 7. HATEOAS
- 📘 [HATEOAS and Web Services](README.md#hateoas-and-web-services)
- 📘 [HATEOAS and JAX-RS](README.md#hateoas-and-jax-rs)
- 📘 Building Links and Link Headers
- ⭐ HATEOAS maturity concept
- ⭐ When HATEOAS is useful / unnecessary

### 8. Caching & Concurrency
- 📘 [Scaling JAX-RS Applications](README.md#scaling-jax-rs-applications)
- 📘 Caching
- 📘 ETags
- 📘 Cache-Control
- 📘 Concurrency Control
- ⭐ Strong vs Weak ETag
- ⭐ Conditional Requests
- ⭐ `If-Match` / `If-None-Match`
- ⭐ `Last-Modified` / `If-Modified-Since`
- ⭐ Optimistic Concurrency Control
- ⭐ Cache invalidation strategies

### 9. Deployment & Integration
- 📘 Deployment
- 📘 Configuration
- 📘 Spring Integration
- ⭐ Servlet/container basics
- ⭐ Reverse Proxy / Load Balancer
- ⭐ Stateless service deployment
- ⭐ Environment-specific configuration

### 10. Securing REST APIs
- 📘 Authentication
- 📘 Authorization
- 📘 JWT Authentication
- 📘 Role-Based Access Control
- 📘 Permission-Based Access Control
- 📘 Authentication & Authorization in JAX-RS
- ⭐ Basic Authentication
- ⭐ Bearer Token Authentication
- ⭐ OAuth 2.0 concepts
- ⭐ OpenID Connect basics
- ⭐ JWT structure: Header / Payload / Signature
- ⭐ Access Token vs Refresh Token
- ⭐ CORS
- ⭐ CSRF
- ⭐ HTTPS / TLS
- ⭐ Password hashing
- ⭐ API security best practices

### 11. RESTful Java Clients
- 📘 `java.net.URL`
- 📘 Apache HttpClient
- 📘 RESTEasy Client Proxies
- ⭐ Java 11+ `HttpClient`
- ⭐ Request headers / timeouts
- ⭐ Connection pooling
- ⭐ Retry and backoff
- ⭐ Client-side error handling

### 12. JAX-RS Implementations
- 📘 Jersey
- 📘 Apache CXF
- 📘 JBoss RESTEasy
- ⭐ JAX-RS specification vs implementation
- ⭐ Jersey vs RESTEasy vs CXF

---

# ⭐ Part 3 — REST API Design Topics You Should Add for Interviews

These are especially important for a 5-year Java/Spring developer and should be treated as a separate checklist.

### 13. API Resource Design
- ⭐ Resource vs Representation
- ⭐ Collection vs Single Resource
- ⭐ Nested Resources
- ⭐ URI naming conventions
- ⭐ Plural nouns vs verbs in URIs
- ⭐ Query parameters for filtering/search
- ⭐ Sorting
- ⭐ Pagination
- ⭐ Offset vs Cursor Pagination
- ⭐ API Versioning
  - URI versioning
  - Header versioning
  - Media-type versioning
- ⭐ Backward Compatibility

### 14. Request & Response Design
- ⭐ Request body vs query parameter vs path parameter
- ⭐ DTO vs Entity
- ⭐ Request DTO / Response DTO
- ⭐ Validation
- ⭐ Partial updates
- ⭐ Consistent response structure
- ⭐ Error response structure
- ⭐ Correlation ID / Request ID

### 15. API Reliability & Distributed Systems
- ⭐ Idempotency Keys
- ⭐ Retry strategy
- ⭐ Exponential Backoff
- ⭐ Timeout
- ⭐ Circuit Breaker
- ⭐ Rate Limiting / Throttling
- ⭐ Bulkhead Pattern
- ⭐ Load Balancing
- ⭐ Graceful Degradation
- ⭐ Fault Tolerance

### 16. API Observability
- ⭐ Structured Logging
- ⭐ Request/Response Logging
- ⭐ Correlation ID
- ⭐ Distributed Tracing
- ⭐ Metrics
- ⭐ Health Checks
- ⭐ Monitoring & Alerting
- ⭐ OpenTelemetry concepts

### 17. API Documentation & Testing
- ⭐ OpenAPI / Swagger
- ⭐ Swagger UI
- ⭐ Contract-first vs Code-first API design
- ⭐ Postman
- ⭐ curl
- ⭐ Unit Testing REST controllers/resources
- ⭐ Integration Testing
- ⭐ API Contract Testing
- ⭐ Mocking external REST services

### 18. Production REST API Architecture
- ⭐ API Gateway
- ⭐ Reverse Proxy
- ⭐ Load Balancer
- ⭐ Service Discovery
- ⭐ Microservices communication
- ⭐ REST vs Messaging/Kafka
- ⭐ Synchronous vs Asynchronous communication
- ⭐ Database-per-Service considerations
- ⭐ Security at Gateway vs Service level

---

# 🎯 Recommended Interview Revision Order

```text
1. REST Principles
        ↓
2. HTTP Methods + Safe/Idempotent Concepts
        ↓
3. URI / Resource Design
        ↓
4. HTTP Status Codes
        ↓
5. Headers + Content-Type + Accept
        ↓
6. PathParam / QueryParam / HeaderParam
        ↓
7. JSON / XML + Serialization
        ↓
8. Request/Response + DTO + Validation
        ↓
9. Exception Handling + Error Contract
        ↓
10. Pagination + Filtering + Sorting
        ↓
11. API Versioning
        ↓
12. Authentication + Authorization
        ↓
13. JWT + OAuth2 + CORS + HTTPS
        ↓
14. Idempotency + Retry + Timeout
        ↓
15. Caching + ETag + Concurrency
        ↓
16. HATEOAS
        ↓
17. API Documentation + Testing
        ↓
18. REST Clients
        ↓
19. API Gateway + Load Balancer
        ↓
20. Observability + Production Design
```

---

# 🔥 5-Year Experience — Must Be Able to Explain

| Priority | Topic | Interview Expectation |
|---|---|---|
| 🔥🔥🔥 | REST principles | Explain with real project example |
| 🔥🔥🔥 | HTTP methods | Semantics + safe/idempotent behavior |
| 🔥🔥🔥 | Status codes | Choose correct code for scenarios |
| 🔥🔥🔥 | URI/resource design | Design clean APIs from requirements |
| 🔥🔥🔥 | Idempotency | Explain retries and duplicate requests |
| 🔥🔥🔥 | Exception handling | Production-ready error contract |
| 🔥🔥🔥 | Authentication/Authorization | JWT/OAuth2 + 401/403 |
| 🔥🔥🔥 | Pagination | Offset vs cursor and performance |
| 🔥🔥🔥 | API versioning | Backward compatibility |
| 🔥🔥🔥 | Caching | Cache-Control + ETag + conditional requests |
| 🔥🔥 | Retry/Timeout | Distributed-service reliability |
| 🔥🔥 | Rate limiting | Protect APIs from abuse/overload |
| 🔥🔥 | API Gateway | Routing/security/rate limiting |
| 🔥🔥 | Observability | Logs + metrics + tracing |
| 🔥🔥 | OpenAPI/Swagger | API documentation |
| 🔥 | HATEOAS | Advanced REST maturity |
| 🔥 | JAX-RS implementations | Jersey/CXF/RESTEasy knowledge |

---

# 🔗 Repository

[Open the complete RESTful Web Services Course →](README.md)

[Open this Topic Index →](TOPIC-INDEX.md)

> **Important:** I have separated topics already present in the repository from additional interview-level topics. This prevents us from pretending a topic is covered in `README.md` when it is actually only a recommended addition.
