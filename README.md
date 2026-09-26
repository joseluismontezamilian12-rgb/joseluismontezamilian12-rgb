# José Luis Monteza Milian

**Backend / Full-Stack Developer — .NET (C#) · React · TypeScript**
Lima, Peru (GMT-5, overlaps US hours) · open to remote Backend or Full-Stack .NET roles

I build transactional systems in C#/.NET and React/TypeScript: REST APIs with Clean Architecture, EF Core, JWT/RBAC security and tested business rules. I came to software after 3+ years leading retail operations teams, so my projects attack problems I have owned first-hand — inventory, shrinkage and demand planning.

- **Own product:** **[Odontario](https://odontario.up.railway.app)**, a SaaS for dental practices in Peru, in production — **129 automated tests**, encrypted backups, clinical records under MINSA standards.
- **Now:** IT support contractor at Peru's National Elections Jury (JNE) for the rollout of its collections module, plus freelance Node.js work.
- **Previously:** Full-Stack Developer at **Manzana Verde** (food-tech, 1.4M+ orders, Jul–Sep 2026) — automated the daily production-allocation decision across 7 partner kitchens with a TypeScript engine backed by **176 automated tests**.
- **Studying:** Systems Engineering at UPN, Lima.

[Portfolio](https://joseluismontezamilian12-rgb.github.io/portafolio-frontend/) · [LinkedIn](https://www.linkedin.com/in/joseluismonteza) · [CV (EN)](https://joseluismontezamilian12-rgb.github.io/portafolio-frontend/Jose_Luis_Monteza_CV_FullStack_Developer.pdf) · [CV (ES)](https://joseluismontezamilian12-rgb.github.io/portafolio-frontend/Jose_Luis_Monteza_CV_FullStack_Developer_ES.pdf) · joseluismontezamilian12@gmail.com

---

## Projects you can run right now

| Project | What it is | Try it |
| :-- | :-- | :-- |
| **[SupplyChainCore](https://github.com/joseluismontezamilian12-rgb/SupplyChainCore-FullStack)** | Inventory system on an **immutable ledger** that rejects negative stock in the service layer. Clean Architecture (4 projects), JWT + RBAC, PBKDF2 hashing, movement authorship taken from the token. **57 unit tests** (xUnit + Moq) run by GitHub Actions. .NET 10 · EF Core · Azure SQL · React. | [Live API + Swagger](https://supplychaincore-api-lnxj7c.azurewebsites.net) |
| **[ECommerceEcosystem](https://github.com/joseluismontezamilian12-rgb/ECommerceEcosystem)** | Two independently deployable .NET services — `Catalog.API` (Azure SQL) and `Basket.API` (Redis) — over HTTP. The basket re-reads every price from the catalog: post a 1,200 laptop priced at 1.00 and it answers 1,200. | [Catalog](https://ecommerce-catalog-lnxj7c.azurewebsites.net) · [Basket](https://ecommerce-basket-lnxj7c.azurewebsites.net) |
| **Odontario** *(private code)* | SaaS for dental practices with 1–3 dentists: appointments, clinical records (NTS 139, ICD-10), odontogram (NTS 188), payments and cash register, role-based permissions. Daily AES-256-GCM backups to another data centre and a tested restore drill. Node.js 24 · Express · SQLite · React 19. | [Demo](https://odontario-demo-production.up.railway.app) |
| **[Merma AI](https://github.com/joseluismontezamilian12-rgb/merma-ai)** | Ordering and shrinkage control for food retail, piloted in a real store against its 78-SKU catalog. Deterministic, explainable recommendations. React 19 · Vite. | [Live demo](https://joseluismontezamilian12-rgb.github.io/merma-ai/) |
| **[ECS Dashboard](https://github.com/joseluismontezamilian12-rgb/ecs-dashboard)** | Retro-terminal React SPA: 60 Hz telemetry and native canvas rendering of 150 entities. | [Live demo](https://joseluismontezamilian12-rgb.github.io/ecs-dashboard/) |

---

## Stack

- **Languages:** C#, TypeScript, JavaScript (ES6+), SQL, HTML5, CSS3
- **Backend:** .NET 10 / .NET 8, ASP.NET Core Web API, Minimal APIs, EF Core, Clean Architecture, Repository Pattern, LINQ, async/await, JWT, RBAC, Node.js
- **Frontend:** React 19, Vite, Recharts, responsive design
- **Data:** SQL Server, Azure SQL, Redis, SQLite, EF Core Migrations
- **Testing & delivery:** xUnit, Moq, Playwright, GitHub Actions, Docker, Azure App Service, Swagger / OpenAPI, Git / GitFlow
- **AI-assisted engineering:** GitHub Copilot, Cursor, Claude Code
- **Business systems:** SAP (inventory & logistics), Kronos (workforce management)
- **Languages spoken:** Spanish (native) · English (B1, async-first: comfortable in written technical English)
