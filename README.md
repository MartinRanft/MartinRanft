# Martin Ranft

**.NET Backend Developer** · Germany

I build reliable backend systems, APIs, and automation tools with C# and .NET.  
My focus is on clean architecture, infrastructure automation, and pragmatic solutions for real-world problems — from Docker management platforms to EU regulatory compliance tooling.

---

### Tech Stack

**Languages & Frameworks**  
C# · .NET 8–10 · ASP.NET Core · Blazor Server · Avalonia UI · Entity Framework Core

**Cloud & Auth**  
Azure AD · JWT · Microsoft Graph API · ASP.NET Identity · OAuth

**Infrastructure & DevOps**  
Docker · Multi-Stage Builds · GitLab CI/CD · Linux (Arch) · Nginx · WireGuard

**Data**  
MySQL · MariaDB · SQL Server · SQLite · Stored Procedures · XML/XSD Serialization

**Integration**  
REST API Design · Swagger/OpenAPI · SMTP · FTP · Docker Engine API

---

### Projects

#### [TibiaHuntMaster](https://github.com/MartinRanft/TibiaHuntMaster)
Cross-platform desktop application for tracking and optimizing game sessions in Tibia.  
Built with **Avalonia UI** targeting Windows and Linux from a single codebase.

- Real-time session tracking with profit/loss analysis and loot calculations
- MVVM architecture with reactive UI bindings
- Cross-platform build pipeline

`C#` `Avalonia UI` `.NET 10` `MVVM` `Cross-Platform`

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

### Professional Experience

Beyond personal projects, I have built internal business tools in professional settings, including:

- **Enterprise statistics platform** — REST API aggregating email and telephony data via Microsoft Graph API and Starface PBX, secured with Azure AD and JWT
- **EU Intrastat automation** — Console application generating XML declarations against official INSTAT XSD schemas, with data validation, SQL Server integration, and automated SMTP delivery
- **Multi-environment CI/CD pipelines** — GitLab CI configurations with branch-based tagging strategies (dev/prod/feature/tag), Docker registry integration, and multi-stage builds

---

### GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MartinRanft&show_icons=true&theme=default&include_all_commits=true&count_private=true&hide_border=true&hide_title=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MartinRanft&layout=compact&theme=default&hide_border=true&hide_title=true)

---

### Contact

📧 **Email** — [martin.ranft@tibiafun.eu](mailto:martin.ranft@tibiafun.eu)  
💼 **LinkedIn** — [linkedin.com/in/martin-ranft-57270121b](https://www.linkedin.com/in/martin-ranft-57270121b/)
