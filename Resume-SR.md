# Predrag Jošić

Backend Developer — NestJS & TypeScript  
GitHub: https://github.com/Hogar77 | Email: safi@safi.rs | Lokacija: Srbija  
Preferirana stopa: $35/hr — po dogovoru

## Sažetak

Back-end developer sa ~2 godine praktičnog iskustva u izgradnji REST API‑ja, integracionih servisa i automatizaciji deploy procesa koristeći NestJS i TypeScript. Iskustvo u izradi pouzdanih rešenja za sinhronizaciju ERP ↔ cloud (T‑SQL + TypeScript workeri), rad sa PostgreSQL / MS SQL, kontejnerizacija (Docker), Nginx i automatsko TLS (Certbot). Fokus na čist kod, testiranje i sigurnu produkciju.

## Ključne veštine

- Jezici i framework‑ovi: TypeScript, Node.js, NestJS, JavaScript, T‑SQL
- Baze podataka: PostgreSQL, MS SQL
- DevOps / Infra: Docker, Docker Compose, Nginx, Certbot (Let’s Encrypt), systemd, VPS deploy
- Integracije: REST API, webhooks, reverse SSH (autossh), Cloudflare Tunnel, WireGuard
- Testiranje i alati: unit testovi, ESLint, Prettier, Git, GitHub Actions (CI/CD)
- Ostalo: Swagger/OpenAPI, JWT autentifikacija, logovanje i observability

## Izabrani projekti / Iskustvo

Hogar77 / sql-api — https://github.com/Hogar77/sql-api

- REST API razvijen u NestJS + TypeScript za ključne poslovne entitete (auth, users, CRUD).
- PostgreSQL, JWT autentifikacija, Swagger dokumentacija. Deploy preko Docker Compose; Nginx kao reverse proxy i Certbot za HTTPS. Implementirani unit testovi i osnovni CI.

Hogar77 / front-b2b — https://github.com/Hogar77/front-b2b

- B2B frontend (TypeScript) koji koristi sql-api endpoint‑e. Prikazani tokovi autentifikacije, refresh tokena i sigurno pozivanje API‑ja. Konfiguracija env varijabli i deploy preko Nginx‑a.

Hogar77 / erp-api-sync — https://github.com/Hogar77/erp-api-sync

- Servis za sinhronizaciju lokalnih ERP podataka sa eksternim API‑jima. Kombinacija T‑SQL stored procedura (change capture, normalizacija, conflict resolution) i TypeScript sync worker‑a. Podržane konekcione šeme za on‑premise sisteme bez fiksne IP (Cloudflare Tunnel, autossh, WireGuard). Uključeni runbook i uputstva za deploy.

## Postignuća / Uticaj

- Izgradio pouzdan sync pipeline između legacy ERP‑a i cloud servisa, čime je smanjena potreba za ručnom usklađivanjem podataka.
- Smanjio vreme i greške pri deploy‑u standardizacijom Docker Compose + Nginx + Certbot procesa.
- Isporučio produkcijski spremne API‑je sa testovima i dokumentacijom, korišćene od strane frontenda i trećih strana.

## Dostupnost

- Trenutna dostupnost: 20 h / nedeljno
- Preferisano angažovanje: remote, ugovori po milestonu ili po satu

## Linkovi

- GitHub: https://github.com/Hogar77
- Portfolio / Live demo: https://b2b.safi.rs/ & https://b2b.safi.rs/api
- LinkedIn: https://www.linkedin.com/in/predrag-jo%C5%A1i%C4%87-28639454/

## Napomene

- Mogu obezbediti pristup privatnim repozitorijima po zahtevu, ili privremene demo deploy‑e. Reference i primeri koda dostupni na zahtev.
