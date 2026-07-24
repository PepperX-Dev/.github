<p align="center">
  <img src="https://raw.githubusercontent.com/PepperX-Dev/QueryForge/main/icon.png" width="110" alt="PepperX" />
</p>

<h1 align="center">PepperX</h1>

<p align="center">
  <strong>High-performance, enterprise-grade engines and tools for the .NET & JS ecosystems.</strong><br/>
  Built for security by default, and designed to get out of your way.
</p>

<p align="center">
  <a href="https://github.com/PepperX-Dev/QueryForge"><img src="https://img.shields.io/badge/Flagship-QueryForge-512BD4?style=for-the-badge&logo=github&logoColor=white" alt="QueryForge"></a>
  <a href="https://www.nuget.org/profiles/AmirHosseinMp02"><img src="https://img.shields.io/badge/NuGet-Packages-0078D4?style=for-the-badge&logo=nuget&logoColor=white" alt="NuGet"></a>
</p>

<br>

## What we build

PepperX exists around one idea: the unglamorous, repetitive parts of software — dynamic filtering, pagination, security validation, standardized contracts — should be solved once, well, and never rewritten per project. Every project under this org is built with the same principles:

- 🛡️ **Security by default**, not as an afterthought bolted on later.
- 🧩 **Provider/runtime-agnostic cores**, so the same intent can execute anywhere.
- ✅ **Tested and CI-gated** before anything ships — no publish without a green build.
- 📖 **Documented like it matters**, because a library nobody can learn fast is a library nobody adopts.

---

## Projects

| Project | Stack | What it is | Status |
| :--- | :--- | :--- | :---: |
| **[QueryForge](https://github.com/PepperX-Dev/QueryForge)** | C# / .NET 10 | A provider-agnostic dynamic query engine. Define filtering, sorting, paging, and hierarchical grouping once — via fluent C# or a JSON contract — and execute it through Dapper today, EF Core and in-memory providers next. | ✅ Active |
| **QueryForge Grid Adapters** | TypeScript / JS | Frontend adapters translating enterprise data-grid `loadOptions` (DevExtreme, AG Grid, Kendo UI) directly into QueryForge's JSON query contract — no manual mapping required. | 🔧 In Development |

---

## Roadmap

- `PepperX.QueryForge.EFCore` — Entity Framework Core execution provider
- `PepperX.QueryForge.InMemory` — in-memory provider for `IEnumerable`-based data
- First public release of the JS/TS grid-adapter package

---

<p align="center">
  <sub>Questions, ideas, or found a bug? Open an issue on the relevant repo above — we read all of them.</sub>
</p>
