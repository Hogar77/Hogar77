# Predrag Jošić — Backend Developer (NestJS, TypeScript)

Backend developer with ~2 years of experience building production REST APIs, integration services and deployment automation. I specialize in NestJS and TypeScript, ERP↔cloud synchronization (T-SQL + TypeScript workers), containerized deployments (Docker), and Nginx + automated TLS (Certbot).

Contact

- GitHub: https://github.com/Hogar77
- Email: safi@safi.rs
- Location: Serbia
- Preferred rate:   Open to discussion
- Availability: 20 hrs/week

Quick links

- Backend (sql-api): [https://github.com/Hogar77/sql-api-readme]
- Frontend demo (front-b2b): https://github.com/Hogar77/front-b2b
- ERP sync (erp-api-sync): [https://github.com/Hogar77/erp-api-sync-readme]
- Live demo / API: https://b2b.safi.rs/ & https://b2b.safi.rs/api
- LinkedIn: https://www.linkedin.com/in/predrag-jošić-28639454/

Core skills

- Languages & frameworks: TypeScript, Node.js, NestJS, JavaScript, T-SQL
- Databases: PostgreSQL, MS SQL
- DevOps & infra: Docker, Docker Compose, Nginx, Certbot, systemd, VPS deploy
- Integrations: REST APIs, webhooks, reverse SSH (autossh), Cloudflare Tunnel, WireGuard
- Testing & tooling: unit tests, ESLint, Prettier, Git, GitHub Actions (CI/CD)
- Other: Swagger/OpenAPI, JWT auth, logging & observability

Selected projects

- sql-api — REST API (NestJS) for core business entities (auth, users, CRUD). PostgreSQL, JWT, Swagger. Deployed via Docker Compose + Nginx + Certbot.
- front-b2b — B2B frontend (TypeScript) consuming sql-api, demonstrating auth flows, token refresh and secure API calls.
- erp-api-sync — ERP ↔ cloud sync service combining T-SQL stored procedures and TypeScript sync workers. Supports on-prem connectivity patterns (Cloudflare Tunnel, autossh, WireGuard). Includes runbook and deployment instructions.

Quick start (backend)

1. Clone:
   git clone https://github.com/Hogar77/sql-api-copy.git
2. Create .env from .env.example and fill placeholders (DO NOT commit real secrets).
3. Install & run:
   npm install
   npm run build
   npm run start:dev

Deployment notes

- Recommended: Docker Compose for simple deploys; use Nginx as reverse proxy and Certbot for TLS. For on-prem ERP, use Cloudflare Tunnel or reverse SSH to expose a secure endpoint.
- Store secrets in your host/CI secret manager (GitHub Actions Secrets, Vault, etc.).

Security

- Never commit real credentials (.env, private keys). If secrets were exposed, rotate them immediately.
- Use httpOnly cookies or secure token storage; avoid putting sensitive tokens in localStorage.

Resume & translations

- Full English resume: add RESUME.pdf to this repo for direct download.
- Serbian version: RESUME-SR.md (optional) or a section at the bottom of this README.

If you need private repo access for reviews, I can grant it on request.

Topics
nestjs, typescript, nodejs, rest-api, erp, integration, docker, nginx, certbot, t-sql, postgresql, deployment, devops
