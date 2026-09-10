# Vhutshilo Wade Mulaudzi

**Software Developer — C# / .NET · Angular · Microsoft Azure**
Midrand, Gauteng, South Africa

I build enterprise, multi-tenant web applications for South African local government: performance
management, risk management and municipal planning systems running in production for 24+
municipalities.

Most of my work sits where a business rule meets a database — approval workflows, tenant data
isolation, scheduled processing and the reporting that municipal officials rely on. I like problems
where the answer is a clear model rather than more code.

---

### Currently

**Junior Software Developer at CCG Systems** (since 2024, from a traineeship earlier that year).

Day to day I work across a multi-repository platform of six Angular applications and five
ASP.NET Core APIs over a shared SQL Server database project, delivering features end to end:
schema design, REST APIs, Angular screens, per-tenant database rollout and production support.

---

### Working with

**Backend** — C# 12 · .NET 8 · ASP.NET Core Web API · Entity Framework Core 8 · LINQ

**Frontend** — Angular · TypeScript · RxJS · PrimeNG · SCSS

**Data** — SQL Server · Azure SQL Database · T-SQL · stored procedures · SSDT database projects

**Cloud & DevOps** — Azure Functions · Key Vault · Application Insights · App Service ·
Static Web Apps · Azure DevOps pipelines · GitHub Actions · Docker

**Practices** — multi-tenant architecture · JWT authentication · role-based access control ·
clean architecture · repository pattern · dependency injection · xUnit · code review · Agile

---

### Featured project

**[TenantFlow](https://github.com/VhutshiloMulaudzi/TenantFlow)** — a multi-tenant purchase
requisition and approval platform in .NET 8 and Angular 18.

Each tenant configures its own approval chain by amount band, so a new approval tier is a database
row rather than a release. Tenant isolation is enforced in the persistence layer by EF Core global
query filters plus a write guard, not by developer discipline — with tests proving one tenant gets
a 404 for another tenant's record requested by its exact id.

`.NET 8` · `EF Core 8` · `Angular 18` · `JWT + RBAC` · `xUnit` · `Docker` · `CI`

---

### Certification

**Microsoft Certified: Azure Fundamentals (AZ-900)** — March 2025

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/vhutshilo-wade) · [wademulaudzi@gmail.com](mailto:wademulaudzi@gmail.com)
