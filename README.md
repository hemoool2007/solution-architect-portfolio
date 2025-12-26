<p align="right">
  <a href="README.md">Tiếng Việt</a> | <a href="README.en.md">English</a>
</p>

# Solution Architect Portfolio (.NET)
## 👤 Tác giả

**Bùi Văn Hậu**  


## 🎯 Mục tiêu

Repository này là **portfolio tổng hợp** cho lộ trình phát triển của tôi theo hướng  
**Solution Architect .NET**.

Mục tiêu chính:
- Hệ thống hóa kiến thức kiến trúc phần mềm
- Ôn tập và đào sâu từng domain thông qua demo & lab thực tế
- Thể hiện tư duy kiến trúc, quyết định thiết kế và trade-off
- Sử dụng làm portfolio khi ứng tuyển các vị trí Senior / Solution Architect

---

## 🧠 Định hướng Solution Architect .NET

Tôi tập trung vào việc thiết kế và xây dựng hệ thống backend trên nền tảng **.NET / ASP.NET Core**, với các tiêu chí:

- Scalability (khả năng mở rộng)
- Reliability (độ ổn định, chịu lỗi)
- Maintainability (dễ bảo trì, mở rộng)
- Security (bảo mật)
- Trade-off rõ ràng theo bối cảnh thực tế

---

## 🗺️ Bản đồ kỹ năng (Skill Map)

### 1️⃣ System Design & Architecture

**Trọng tâm:**
- C4 Model (Context / Container / Component)
- Monolith vs Modular Monolith vs Microservices
- Bounded Context
- Sync vs Async communication
- API contract & versioning

**.NET focus:**
- ASP.NET Core architecture
- Clean / Onion / Hexagonal Architecture
- Dependency Injection
- Middleware pipeline
- Minimal API vs Controller

👉 Repo chuyên sâu: `architecture-system-design-dotnet`

---

### 2️⃣ API & Backend Design (.NET)

**Trọng tâm:**
- RESTful API design
- Idempotency
- Pagination / filtering / sorting
- Rate limiting
- Backward compatibility

**.NET focus:**
- ASP.NET Core Web API
- Model binding & validation
- Filters vs Middleware
- Swagger / OpenAPI

👉 Repo chuyên sâu: `architecture-api-design-dotnet`

---

### 3️⃣ Database & Data Architecture

**Trọng tâm:**
- Data modeling
- Transaction & isolation
- Migration strategy (expand–contract)
- Read / write scaling
- Indexing & partitioning

**.NET focus:**
- EF Core internals
- EF Core vs Dapper
- Tracking vs No-tracking
- SQL Server / PostgreSQL

👉 Repo chuyên sâu: `architecture-database-dotnet`

---

### 4️⃣ Distributed Systems & Scalability

**Trọng tâm:**
- Horizontal scaling
- Stateless services
- Cache strategy
- Async processing
- Backpressure

**.NET focus:**
- Redis
- BackgroundService
- Hangfire / Quartz
- gRPC
- Polly

👉 Repo chuyên sâu: `architecture-scalability-dotnet`

---

### 5️⃣ Reliability, Resilience & Fault Tolerance

**Trọng tâm:**
- Retry / timeout
- Circuit breaker
- Idempotency
- Graceful degradation
- Health checks

**.NET focus:**
- Polly integration
- ASP.NET Core HealthChecks
- Idempotent consumer pattern

👉 Repo chuyên sâu: `architecture-reliability-dotnet`

---

### 6️⃣ Security Architecture

**Trọng tâm:**
- Authentication vs Authorization
- RBAC / ABAC
- Token-based security
- Secrets management
- Audit logging

**.NET focus:**
- ASP.NET Core Identity
- JWT / OAuth2 / OpenID Connect
- Duende / IdentityServer
- Policy-based authorization
- Data Protection API

👉 Repo chuyên sâu: `architecture-security-dotnet`

---

### 7️⃣ Multi-tenant Architecture

**Trọng tâm:**
- Tenant isolation strategies
- Data isolation
- Config per tenant
- Feature flag per tenant
- Billing & quota

**.NET focus:**
- Tenant middleware
- DbContext per tenant
- Connection string per tenant
- EF Core model cache

👉 Repo chuyên sâu: `architecture-multi-tenant-dotnet`

---

### 8️⃣ Event-driven & Messaging

**Trọng tâm:**
- Event vs Command
- At-least-once delivery
- Idempotent consumer
- Event versioning
- Saga (basic)

**.NET focus:**
- Kafka / RabbitMQ
- MassTransit
- Outbox pattern
- Background consumer

👉 Repo chuyên sâu: `architecture-event-driven-dotnet`

---

### 9️⃣ DevOps, CI/CD & Deployment

**Trọng tâm:**
- CI/CD pipeline
- Blue–Green / Canary deployment
- Rollback strategy
- Infrastructure as Code

**.NET focus:**
- Dockerizing ASP.NET Core
- Multi-stage Docker build
- GitHub Actions / GitLab CI
- Kubernetes (fundamental)

👉 Repo chuyên sâu: `architecture-devops-dotnet`

---

### 🔟 Observability & Monitoring

**Trọng tâm:**
- Logging
- Metrics
- Tracing
- Alerting

**.NET focus:**
- Serilog
- OpenTelemetry
- Prometheus
- Grafana
- ASP.NET Core diagnostics

👉 Repo chuyên sâu: `architecture-observability-dotnet`

---

### 1️⃣1️⃣ Performance & Optimization

**Trọng tâm:**
- Bottleneck analysis
- Async I/O
- Cache vs DB
- Memory management

**.NET focus:**
- async / await internals
- ThreadPool
- GC basics
- BenchmarkDotNet
- dotnet-counters

👉 Repo chuyên sâu: `architecture-performance-dotnet`

---

### 1️⃣2️⃣ Architecture Decision & Trade-offs

**Trọng tâm:**
- Decision log
- Trade-off analysis
- Cost vs complexity
- Build vs buy

**.NET focus:**
- EF Core vs Dapper
- Minimal API vs MVC
- Modular Monolith vs Microservices
- Cloud-native vs cloud-agnostic

👉 Repo chuyên sâu: `architecture-decisions-dotnet`

---

## 📌 Cách sử dụng portfolio này

- **Recruiter:** đọc README để nắm tổng quan
- **Interviewer:** chọn 1 domain và đi sâu vào repo chuyên biệt
- **Cá nhân:** dùng như sổ tay kiến trúc + lab thực hành

---

