<p align="center">
  <img src="https://raw.githubusercontent.com/PepperX-Dev/QueryForge/main/icon.png" width="110" alt="PepperX" />
</p>

<h1 align="center">PepperX</h1>

<p align="center">
  <strong>High-performance, enterprise-grade engines and tools for the .NET & JS ecosystems.</strong><br/>
  Built to be safe by default, and designed to get out of your way.
</p>

<p align="center">
  <a href="https://github.com/PepperX-Dev/QueryForge"><img src="https://img.shields.io/badge/QueryForge-Dynamic_Queries-512BD4?style=for-the-badge&logo=github&logoColor=white" alt="QueryForge"></a>
  <a href="https://github.com/PepperX-Dev/SqliteGate"><img src="https://img.shields.io/badge/SqliteGate-SQLite_Concurrency-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SqliteGate"></a>
  <a href="https://www.nuget.org/profiles/AmirHosseinMp02"><img src="https://img.shields.io/badge/NuGet-Packages-0078D4?style=for-the-badge&logo=nuget&logoColor=white" alt="NuGet"></a>
</p>

<br>

## What we build

PepperX exists around one idea: the unglamorous, repetitive parts of software — dynamic filtering, pagination, security validation, database concurrency, standardized contracts — should be solved once, well, and never rewritten per project. Every project under this org is built with the same principles:

- 🛡️ **Safe by default** — security in QueryForge, concurrency correctness in SqliteGate. Never something you bolt on later.
- 🧩 **One core, many front doors** — the hard thinking happens once, in a provider-agnostic engine; the adapters stay thin.
- ✅ **Tested and CI-gated** before anything ships — no publish without a green build.
- 📖 **Documented like it matters**, because a library nobody can learn fast is a library nobody adopts.

---

## Projects

| Project | Stack | What it is | Status |
| :--- | :--- | :--- | :---: |
| **[QueryForge](https://github.com/PepperX-Dev/QueryForge)** | C# / .NET 10 | A **provider-agnostic dynamic query engine**. Define filtering, sorting, paging and hierarchical grouping once — via fluent C# or a JSON contract — and execute it through Dapper, EF Core, or an in-memory collection. Nothing is deployed to your database. | ✅ Active |
| **[SqliteGate](https://github.com/PepperX-Dev/SqliteGate)** | C# / .NET 10 | **Concurrency-safe SQLite.** Stops `SQLITE_BUSY` / "database is locked" by putting one write queue in front of each database file — writes queue, reads never block — behaving identically whether you're on raw ADO.NET, Dapper, or EF Core. | 🚀 New |
| **QueryForge Grid Adapters** | TypeScript / JS | Frontend adapters translating enterprise data-grid `loadOptions` (DevExtreme, AG Grid, Kendo UI) directly into QueryForge's JSON query contract — no manual mapping required. | 🔧 In Development |

---

## Which one am I looking for?

- Building a filter/sort/page API and tired of hand-writing `WHERE` clauses per screen? → **QueryForge**
- Seeing `database is locked` from a SQLite-backed service under load? → **SqliteGate**
- Wiring a DevExtreme / AG Grid / Kendo grid to a QueryForge backend? → **Grid Adapters**

The two .NET engines are independent — use either on its own, or both together.

---

## Roadmap

- First public release of the JS/TS grid-adapter package
- Continued provider and engine coverage across both .NET engines, driven by real usage

---

<p align="center">
  <sub>Questions, ideas, or found a bug? Open an issue on the relevant repo above — we read all of them.</sub>
</p>
