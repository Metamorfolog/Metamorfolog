<div align="center">

# Hi, I'm Roman 👋

**Full-stack developer · AI coding agents · Self-hosted infrastructure**

I build software that actually ships: from requirements and architecture to tested, deployed and running systems.

🇬🇧 English · 🇨🇿 [Česky](README.cs.md)

**[pikldev.cloud](https://pikldev.cloud)** · [Public projects](#public-projects) · [Production work](#private-work-in-production) · [How I work](#how-i-work)

</div>

---

### What I do

I design, build and operate complete applications: web and mobile frontends, APIs, databases and the Linux servers they run on. Coding agents like **Claude Code and Codex** write much of the code. I set the direction, review every diff, test it and answer for the result.

### Public projects

| Project | What it does | Highlights |
| --- | --- | --- |
| 🗂️ **[FileAction](https://github.com/Metamorfolog/file_action)** | Click-free file conversion: drag a file, tap a key, drop it on a radial wheel. Fully local. | Windows / Linux · tests + CI · 15 releases · [website](https://fileaction.apexpiksel.cz) |
| 📲 **[PhoneDrop](https://github.com/Metamorfolog/phonedrop)** | Drop a file on a small Windows window and it lands on your Android phone; APKs install with one tap. | Windows · Android · macOS · QR pairing · signed self-updates · [website](https://phonedrop.apexpiksel.cz) |

### Private work in production

Client and commercial systems stay private. Case studies with screenshots from demo data are on **[pikldev.cloud](https://pikldev.cloud)**.

- **ReadyOps + Dispatch** — operations platform for large automotive events: guest registration and QR/NFC check-in, fleet, test drives, handovers, and a live GPS dispatch map. Dispatch ran at NATO Days 2026 with 25 cars and drivers. *NestJS · Next.js · Flutter · PostgreSQL · SSE · Mapbox*
- **Účto** — AI processing of accounting documents (upload or e-mail intake, LLM extraction, human review, export to accounting software). Used by three companies. *NestJS · Next.js · BullMQ · Claude*
- **Roster** — shift scheduling with an OR-Tools CP-SAT solver, Next.js admin and Flutter app. *FastAPI · PostgreSQL · Alembic*
- **Attendance SaaS** — attendance and staff admin with QR check-in hardware (ESP32), multi-tenant via Postgres RLS. *Next.js · Supabase*
- **Nightshift** — task runner that executes Claude Code on my own servers from a Postgres queue, with verification gates and an Android client.

### How I work

1. **Define the outcome** — real workflow, edge cases, acceptance criteria.
2. **Design first** — data model, boundaries, what must be enforced by the database.
3. **Orchestrate agents** — small independent tasks, parallel runs, clear briefs.
4. **Verify, don't assume** — read every diff, typecheck, lint, tests, second-pass review.
5. **Ship and operate** — Docker behind Caddy on my own Linux servers, backups, migrations, logs.

### Tech stack

**Web & backend:** TypeScript, React, Next.js, Node.js, NestJS, Fastify, Python, FastAPI
**Data & infra:** PostgreSQL, Supabase, Redis, Docker, Caddy, Linux, WireGuard, GitHub Actions
**Apps & hardware:** Flutter/Dart, Kotlin, C#/.NET, Swift, ESP32
**AI:** Claude Code, Codex, Claude API, OpenRouter, Ollama, MCP

---

<div align="center">

🇨🇿 Based in Czechia · **[pikldev.cloud](https://pikldev.cloud)**

</div>
