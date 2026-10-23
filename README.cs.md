<div align="center">

# Ahoj, jsem Roman 👋

**Full-stack vývojář · AI coding agenti · self-hosted infrastruktura**

Stavím software, který opravdu běží: od požadavků a architektury po otestované, nasazené a provozované systémy.

🇬🇧 [English](README.md) · 🇨🇿 Česky

**[pikldev.cloud](https://pikldev.cloud/cs)** · [Veřejné projekty](#veřejné-projekty) · [Projekty v provozu](#soukromé-projekty-v-provozu) · [Jak pracuji](#jak-pracuji)

</div>

---

### Co dělám

Navrhuji, vyvíjím a provozuji kompletní aplikace: webové a mobilní frontendy, API, databáze i Linux servery, na kterých běží. Velkou část kódu píšou coding agenti jako **Claude Code a Codex**. Já určuji směr, čtu každý diff, testuji a za výsledek odpovídám.

### Veřejné projekty

| Projekt | Co dělá | Hlavní body |
| --- | --- | --- |
| 🗂️ **[FileAction](https://github.com/Metamorfolog/file_action)** | Konverze souborů bez klikání: chytni soubor, ťukni na klávesu a pusť ho na kruhové menu. Vše lokálně. | Windows / Linux · testy + CI · 15 vydání · [web](https://fileaction.apexpiksel.cz) |
| 📲 **[PhoneDrop](https://github.com/Metamorfolog/phonedrop)** | Pustíš soubor do malého okna ve Windows a objeví se v Android telefonu; APK se nainstaluje jedním ťuknutím. | Windows · Android · macOS · párování QR kódem · podepsané aktualizace · [web](https://phonedrop.apexpiksel.cz) |

### Soukromé projekty v provozu

Klientské a komerční systémy zůstávají soukromé. Případové studie se screenshoty z demo dat jsou na **[pikldev.cloud](https://pikldev.cloud/cs)**.

- **ReadyOps + Dispatch** — provozní platforma pro velké automobilové akce: registrace hostů a check-in přes QR/NFC, flotila, testovací jízdy, předávky a živá GPS dispečerská mapa. Dispatch běžel na Dnech NATO 2026 s 25 vozy a řidiči. *NestJS · Next.js · Flutter · PostgreSQL · SSE · Mapbox*
- **Účto** — AI zpracování účetních dokladů (příjem nahráním nebo e-mailem, vytěžení pomocí LLM, kontrola člověkem, export do účetního programu). Používají ho tři firmy. *NestJS · Next.js · BullMQ · Claude*
- **Roster** — plánování směn se solverem OR-Tools CP-SAT, administrace v Next.js a aplikace ve Flutteru. *FastAPI · PostgreSQL · Alembic*
- **Docházka SaaS** — docházka a správa zaměstnanců s QR terminálem (ESP32), multi-tenant přes RLS v Postgresu. *Next.js · Supabase*
- **Nightshift** — task runner, který na mých serverech spouští Claude Code z fronty v Postgresu, s ověřovacími branami a Android klientem.

### Jak pracuji

1. **Definovat výsledek** — skutečný proces, okrajové případy, akceptační kritéria.
2. **Nejdřív návrh** — datový model, hranice, co musí hlídat databáze.
3. **Orchestrace agentů** — malé nezávislé úlohy, paralelní běhy, jasná zadání.
4. **Ověřovat, ne předpokládat** — přečíst každý diff, typecheck, lint, testy, druhé review.
5. **Nasadit a provozovat** — Docker za Caddy na vlastních Linux serverech, zálohy, migrace, logy.

### Technologie

**Web a backend:** TypeScript, React, Next.js, Node.js, NestJS, Fastify, Python, FastAPI
**Data a infrastruktura:** PostgreSQL, Supabase, Redis, Docker, Caddy, Linux, WireGuard, GitHub Actions
**Aplikace a hardware:** Flutter/Dart, Kotlin, C#/.NET, Swift, ESP32
**AI:** Claude Code, Codex, Claude API, OpenRouter, Ollama, MCP

---

<div align="center">

🇨🇿 Česká republika · **[pikldev.cloud](https://pikldev.cloud/cs)**

</div>
