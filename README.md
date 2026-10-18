# Antoine Dupuy

Computer engineering student at **ESIEE Paris** (5th year, graduating 2027).

I build tools that automate real operations with LLMs, and I like working close to the people who use them.

**Looking for a 6-month end-of-studies internship starting February 8, 2027.**

[![Portfolio](https://img.shields.io/badge/Portfolio-adk783.github.io-0A66C2?style=flat-square)](https://adk783.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-antdupuy-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antdupuy/)
[![Email](https://img.shields.io/badge/Email-antoine.dupuy01%40gmail.com-555555?style=flat-square&logo=gmail&logoColor=white)](mailto:antoine.dupuy01@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-555555?style=flat-square)](https://adk783.github.io/assets/Antoine-Dupuy-CV.pdf)

---

## Latest experience

**Customer Care & Product Builder at Daisy** (internship, Apr. to Aug. 2026, Paris)

SaaS for booking creative workshops. I handled technical onboarding, level 2 support on the production PostgreSQL database, and built two internal AI automation tools:

| Tool | What it does | Result |
| --- | --- | --- |
| **dataimport-studio** | Detects the format of a workshop's previous booking software and converts its exports into import-ready files. Deterministic rules first, LLM only for ambiguous cases, read-only DB access, mandatory human review. | From 45-60 min to a few minutes per client import, ~95% of rows handled by tested rules |
| **daisy-scan** | From a workshop's website URL, crawls pages and PDFs, extracts its classes, prices and schedules with an LLM and drafts an editable catalog. Hardened against SSRF. | Used daily by the Customer Success team, much faster than recreating catalogs by hand |

<sub>Next.js, TypeScript, PostgreSQL, Playwright, Claude, Gemini. Internal tools, private code.</sub>

---

## Featured projects

### [Puma Club website](https://pumaclubmma.com/)
Live website for a martial arts club with two gyms (Noisy-le-Grand and Villeparisis): disciplines, schedules, pricing, registration and free trial.

All content lives in typed data files, so a schedule or price change updates every page and the "next class" widget at once. Schedule logic is unit tested, and a GitHub Actions workflow runs tests, type checks and the build before deploying to Cloudflare Pages on every push.

<sub>Astro, TypeScript, Cloudflare Pages, GitHub Actions. Private code.</sub>

### [News Agents](https://github.com/adk783/Projet-News-Agents/tree/version-finale-v3)
Financial news analysis by AI agents, a 4th year project for IMGT Group (team of 6).

I was one of the two developers of the technical core: news collection per ticker (yfinance), full text extraction with fallback, SQLite storage, and the search methods feeding the agents. The final pipeline chains LLM filtering, specialized agents (FinBERT, Ollama) and a Flask dashboard.

<sub>Python, SQLite, FinBERT, Ollama, Flask</sub>

### [Ocean Navigator](https://github.com/adk783/boatproject)
Realistic boat simulation on a dynamic ocean in Godot 4 (team of 3, I owned physics and navigation).

Buoyancy points synced with wave height, directional drag on 3 axes, vector based stabilization for motion without oscillation.

<sub>Godot 4, GDScript, GDShader</sub>

### [ConcenTrade](https://github.com/raphDucour/ConcenTrade)
Anti-distraction app for Windows (team of 5): detects and blocks targeted processes in real time during work sessions.

<sub>C#, .NET, Windows API</sub>

---

## Stack

[![Stack](https://skillicons.dev/icons?i=ts,py,cs,java,cpp,nextjs,astro,postgres,sqlite,flask,godot,git,vscode&perline=13)](https://skillicons.dev)

Also: LLM automation, multi-agent systems, Playwright, Ollama.

## Beyond code

- French (native), English B2 (TOEIC 900/990), Erasmus semester at the University of West Bohemia (Czech Republic)
- Customer facing experience: Daisy, summer jobs at Crédit Mutuel (2023 to 2025), Red Cross volunteer
