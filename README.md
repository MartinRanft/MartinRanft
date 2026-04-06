# Martin Ranft

**.NET Backend Developer** · Germany

I build reliable backend systems, APIs, and automation tools with C# and .NET.  
My focus is on clean architecture, infrastructure automation, and pragmatic solutions for real-world problems — from Docker management platforms to EU regulatory compliance tooling.

---

### Tech Stack

**Languages & Frameworks**  
C# · .NET 8–10 · ASP.NET Core · Blazor Server · Avalonia UI · Entity Framework Core

**Cloud & Auth**  
Azure AD · JWT · Microsoft Graph API · ASP.NET Identity · OAuth · PBKDF2-SHA256

**Infrastructure & DevOps**  
Docker · Multi-Stage Builds · GitHub Actions · GitLab CI/CD · Linux (Arch) · Nginx · WireGuard

**Data & Caching**  
MySQL · MariaDB · SQL Server · SQLite · Redis · HybridCache · Stored Procedures · XML/XSD Serialization

**Integration**  
REST API Design · Swagger/OpenAPI · Scalar UI · Prometheus Metrics · SMTP · FTP · Docker Engine API

---

### Projects

#### [TibiaData](https://github.com/MartinRanft/tibiadata) · [Live Demo](https://tibiadata.bytewizards.de/)
High-performance REST API providing structured Tibia game data, synced from TibiaWiki.  
Replaces slow wiki page parsing with a fast, typed, cache-backed data layer.

- 42+ endpoint categories (Items, Creatures, Hunting Places, NPCs, Spells, Quests, and more)
- Multi-layer caching with HybridCache (L1 In-Memory + L2 Redis) and tag-based invalidation
- Automated background scraping with change detection, error tracking, and admin controls
- Security hardening: rate limiting (token bucket + concurrency), IP banning, brute force protection, PBKDF2-SHA256, security headers
- Prometheus metrics endpoint and Kubernetes-ready health checks (`/health/live`, `/health/ready`)

`C#` `ASP.NET Core` `.NET 10` `EF Core` `MariaDB` `Redis` `Docker` `Coravel` `Prometheus`

#### [TibiaHuntMaster](https://github.com/MartinRanft/TibiaHuntMaster)
Cross-platform desktop application for tracking and optimizing game sessions in Tibia.  
Built with **Avalonia UI** targeting Windows and Linux from a single codebase.

- Real-time session tracking with profit/loss analysis and loot calculations
- MVVM architecture with reactive UI bindings and 6-language localization
- 32 test files covering unit, integration, and concurrency scenarios
- Consumes data from TibiaData API, TibiaWiki, and TibiaPal

`C#` `Avalonia UI` `.NET 10` `EF Core` `SQLite` `MVVM` `Polly` `xUnit`

#### [DockerControl](https://github.com/MartinRanft/DockerControl) *(archived)*
Self-hosted web application for managing Docker containers, images, volumes, and networks through a browser UI. Built as an internal tool to replace CLI-based Docker management.

- Blazor Server frontend with Radzen components and real-time container status updates
- Direct Docker Engine API integration via Unix sockets (Linux) and TCP (Windows)
- Full auth system with ASP.NET Identity, role-based access control, and 2FA
- Docker Compose project management with YAML parsing and editing
- Private Docker Registry integration
- Multi-stage Dockerfile with embedded Python runtime for scripting support

`C#` `Blazor Server` `.NET 9` `Docker API` `EF Core` `SQLite` `ASP.NET Identity`

#### [APIExample](https://github.com/MartinRanft/APIExample)
Production-ready API template implementing clean architecture patterns.  
Designed as a reusable foundation for backend services.

- Layered architecture with clear separation of concerns
- Background service integration for async task processing
- Full CI/CD pipeline with GitLab

`C#` `ASP.NET Core` `.NET 8` `Docker` `GitLab CI`

#### [KaffeBot](https://github.com/MartinRanft/KaffeBot)
Discord bot service built with modern .NET patterns.  
Runs as a fully containerized service with automated deployments.

- Async command handling with dependency injection
- Backed by a dedicated REST API for data and configuration
- Dockerized with CI/CD-driven image builds and registry push

`C#` `.NET 8` `Docker` `REST API` `GitLab CI`

---

### Contact

📧 **Email** — [martin.ranft@tibiafun.eu](mailto:martin.ranft@tibiafun.eu)  
💼 **LinkedIn** — [linkedin.com/in/martin-ranft-57270121b](https://www.linkedin.com/in/martin-ranft-57270121b/)
