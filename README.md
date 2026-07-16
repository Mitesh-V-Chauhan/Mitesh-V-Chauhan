<!-- HEADER -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=6E40C9&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Mitesh+%F0%9F%91%8B;I+ship+backend+%2B+AI+infra%2C+solo;Chemical+Engineering+on+paper%2C+not+in+practice;Building+in+public+%2F+DMs+open+%F0%9F%9A%80" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=Mitesh-V-Chauhan&style=flat-square&color=6E40C9" alt="Profile Views" />
<a href="https://www.linkedin.com/in/mitesh-chauhan-9a079631a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:miteshvchauhan984@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Open%20to%20Work-2ea44f?style=flat-square" />

</div>

<br/>

Studying Chemical Engineering at IIT Gandhinagar. Not writing this README to explain that away — writing it because the projects below speak for themselves.

I don't build tutorial clones. I build the thing, benchmark it, and ship the number: an async memory service that gives AI agents long-term recall, a C++ route solver that does **31,000+ requests/sec**, a Git-inspired VCS built from raw bytes up — CLI, storage, dashboard, all of it.

Bias toward shipping over planning. If it doesn't work in a week, I kill it and try the next thing.

<br/>

## 🚀 Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [Memory Layer](https://github.com/Mitesh-V-Chauhan/memory-layer)
**A long-term memory service for AI agents.**

Most agents forget everything between sessions — and vector search alone can't explain *why* it remembers something. Memory Layer fixes both.

- 14 FastAPI endpoints; Gemini 2.5 Flash extracts structured facts from raw conversation
- Gemini function-calling resolves `ADD` / `UPDATE` / `DELETE` — memory stays consistent, not just accumulated
- Dual-mode retrieval: **Qdrant** (vector) + **Neo4j** (graph) for both similarity *and* relationships
- Fully async — `asyncpg`, `AsyncQdrantClient`, `AsyncGraphDatabase` — nothing blocks the event loop

`FastAPI` `Qdrant` `Neo4j` `PostgreSQL` `Vertex AI`

</td>
<td width="50%" valign="top">

### ⚡ [Velox](https://github.com/Mitesh-V-Chauhan/velox)
**A route-optimization engine in C++17.**

Dijkstra, A\*, and TSP/VRP heuristic solvers — exposed to Python via `pybind11`, served through FastAPI, rendered on real OSRM road geometry.

- **31,325 req/sec** — ~0.032 ms/request on a 100-node graph
- 22 pytest API/integration tests + 19 CTest C++ unit tests
- Next.js frontend for live route visualization

`C++17` `pybind11` `FastAPI` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗃️ [stgit](https://github.com/Mitesh-V-Chauhan/stgit)
**A Git-inspired VCS — built from scratch to understand Git at depth.**

Custom Python CLI *and* a full GitHub-style web dashboard, not just a clone of `git log`.

- Bearer-token auth (bcrypt) with private-repo access control
- Commit snapshots stored as blobs on Google Cloud Storage
- Async MongoDB schema for repos, users, and follower graphs
- Packaged and published as an installable **PyPI** package

`Next.js` `FastAPI` `MongoDB` `GCP`

</td>
<td width="50%" valign="top">

### 🤖 [Blink](https://github.com/Mitesh-V-Chauhan/blink)
**Describe an app. Blink writes and runs it.**

An autonomous AI coding agent that generates *and executes* code live, in an isolated sandbox — not just a code generator that stops at the output.

- LangGraph-orchestrated multi-step agent reasoning
- E2B Sandboxes for isolated, real-time code execution
- Streaming output from generation straight to a running app

`Next.js` `TypeScript` `LangGraph` `E2B` `FastAPI`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

**[FinPilot AI](https://github.com/Mitesh-V-Chauhan/algofest)** — Enterprise LLM app for financial queries via a reactive state machine: multi-step reasoning, dynamic tool calls, real-time streaming.
`LangGraph` `FastAPI` `React` `TypeScript`

**[AI Architecture Generator](https://github.com/Mitesh-V-Chauhan/ai-architecture-generator)** — Plain English in → boilerplate code, DB schemas, and architecture diagrams out.
`Python` `LangChain` `React` `Prisma` `Supabase`

</details>

<br/>

## 🔨 Shipping Log

What I'm building right now — updated as it happens, not after the fact.

- [ ] **[Project name]** — one-line problem statement. *Status: scoping / building / shipped.*

<sub>This section stays live. If it's empty, I'm between ships — ping me, I probably have an idea half-formed already.</sub>

<br/>

## 🛠️ Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=cpp,c,python,typescript,javascript,react,nextjs,fastapi,docker,gcp,supabase,firebase,vercel&theme=dark" />
</div>

**Databases:** SQL · MongoDB · PostgreSQL · Neo4j · Qdrant · Firebase · Supabase
**Also:** gRPC · Inngest · pybind11

<br/>

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Mitesh-V-Chauhan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mitesh-V-Chauhan&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="165"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=Mitesh-V-Chauhan&theme=tokyonight&hide_border=true" />
</div>

<br/>

## 🏆 Highlights

- 🥈 **Runner-up, UpGrad CodeEd Hackathon** — advanced to the national finale in Mumbai; pitched the product to Ronnie Screwvala. Two-person team going up against groups of 4–5.
- 🛠️ **Secretary, Metis App/Web Dev Club, IIT Gandhinagar** — run React.js workshops, coordinate the club's induction hackathon, and represent the club's project pipeline as a stakeholder for Summer Siege.

<br/>

## 📬 Let's talk

Open to **remote internships** and building real things with people who move fast. If you're a founder and something above is relevant to what you're building — just email me, I'll respond same day.

<div align="center">
<a href="https://www.linkedin.com/in/mitesh-chauhan-9a079631a">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:miteshvchauhan984@gmail.com">
<img src="https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
</div>
