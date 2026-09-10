<div align="center">
  <h1>👋 Hi, I'm Luigi Ferri Maines</h1>
  <p>
    <strong>QA Automation Engineer @ Bridge Lab · SDET-track · Information Systems @ UFSC</strong>
  </p>
  <p>
    <a href="README.pt-br.md">🇧🇷 Ler em português</a>
  </p>

  <p>
    <a href="https://github.com/luigiferrim/assistente-juridico">
      <img src="https://img.shields.io/badge/-Assistente_Jurídico:_agentic_system_in_production-339933?style=flat&logo=node.js&logoColor=white" alt="Assistente Jurídico" />
    </a>
    <a href="https://github.com/luigiferrim/stock_finance_management_system">
      <img src="https://img.shields.io/badge/-Stockfee:_Coffee_Management_System-000?style=flat&logo=next.js&logoColor=white" alt="Stockfee" />
    </a>
    <a href="https://github.com/luigiferrim/cafe-landing">
      <img src="https://img.shields.io/badge/-Coxilha:_My_Coffee_Brand-6F4E37?style=flat&logo=buymeacoffee&logoColor=white" alt="Coxilha" />
    </a>
  </p>
</div>

---

### 👨‍💻 About Me

I write test code and product code, and I like the problems where being wrong has a real cost for someone.

I'm an Information Systems student at UFSC working as a **QA Automation Engineer at Bridge Lab**, on a nationwide education platform built with Brazil's Ministry of Education. I test its Java/Spring Boot backend, its REST APIs and its Flutter app, and I'm leading the migration of the established manual suite into code.

Before Bridge I spent a year at LabTrans on **Monitora SP**, a São Paulo State government platform for traffic enforcement. There I built an automation framework from scratch in Playwright and C#, and learned most of what I know about why test suites fail for reasons that have nothing to do with the product.

On the side I build and ship things. The one I'm proudest of is an agentic legal assistant that has been running a fully automated daily cycle **in production since August 2026**.

* 🌍 **Languages:** Portuguese (native) · English (fluent) · French (fluent)
* 📍 **Location:** Florianópolis, SC — Brazil *(GMT-3, full overlap with US hours)*
* 🇮🇹 **Work authorization:** Italian citizen — EU work authorization, no sponsorship needed
* 🎯 **Focus:** Test automation (Playwright / C#), backend engineering (Node.js, TypeScript), and agentic systems with human-in-the-loop design

---

### 🛠️ Tech Stack

<div align="center">

**QA & Test Automation**
<br>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />

**Development & Data**
<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />

**Environments I test**
<br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />

</div>

---

### 🚀 Experience

**QA Automation Engineer — Bridge Lab** *(Jun 2026 – present)*
* Testing the Java/Spring Boot backend, REST APIs and Flutter app of a platform with 18M+ downloads, built with Brazil's Ministry of Education.
* Auditing the existing manual suite and leading its migration into code-based automation.
* Validating persisted state directly in SQL instead of trusting the interface.

**QA Analyst — LabTrans/UFSC (Monitora SP)** *(Jul 2025 – Jun 2026)*
* Built an automation framework from scratch in **Playwright + C#**, structured in Page Object Model across **50+ screen and file flows**.
* Found that **40% of failures were false negatives**: static test data kept colliding with business rules. Rebuilt the data layer to select valid, unused records from the database at runtime, with a teardown that restores state. False negatives went to near zero.
* Cut regression of the core flows from **over a day of manual work to 90 seconds across 30 paths**.
* Validated 60+ releases across 4 environments and 3 institutions, with grey-box root cause analysis on source and logs.

---

### 📊 Featured Projects

#### [Assistente Jurídico](https://github.com/luigiferrim/assistente-juridico) — *agentic legal assistant, in production*
Every morning it reads Brazil's official judicial gazette, triages what arrived for each lawyer, sends a briefing by email, and with **one approval click** creates the hearing in Google Calendar and drafts the client notice. Built for a real labor-law firm and running a fully automated daily cycle since Aug 2026.

The rule it will not break: **the system proposes, the lawyer approves.** No external action happens without explicit human approval.

* **Engineering worth reading:** append-only audit enforced by a database trigger; idempotency keys written *before* the external call; a failed collection returns `incomplete`, so "0 items" never becomes "nothing exists"; secrets in the OS keychain; recursive log sanitization; a hermeticity test that fails the build if any real term from the local config leaks into the repo.
* **Triage is deterministic, not AI.** Every card states which signals classified it. No "the model thought it was urgent."
* **CI as a gate, not a badge:** GitHub Actions runs the suite, a zero-dependency linter and a leak audit over the tree and the *entire git history*; any real case number, bar ID, e-mail or secret fails the build, and the report comes out redacted because the log is public.
* **Tech:** Node.js 22, **zero npm dependencies** (native modules only, including `node:sqlite` and `node:test`), SQLite with `STRICT` tables, Google Apps Script, launchd. 131 hermetic tests.

#### [Stockfee](https://github.com/luigiferrim/stock_finance_management_system) — *coffee management system (team project, UFSC)*
A full inventory and financial management system for coffee shops and roasters, built with three teammates for a web development course and deployed to production. Goal: turn it into a real SaaS.
* **My part:** integration and internal modules (dashboard, stock, financial, history).
* **Tech:** Next.js, TypeScript, PostgreSQL (Neon), NextAuth, Tailwind, Vercel.

#### [Coxilha](https://github.com/luigiferrim/cafe-landing) — *coffee sales landing page (solo)*
A landing page I built on my own to sell specialty coffee, focused on a clean front-end and responsive design.
* **Tech:** React, Tailwind CSS, Vercel.

#### [Sistema CaFerri](https://github.com/salmoriadev/Sistema_CaFerri) — *coffee shop desktop system (team, academic)*
A Python desktop app with an MVC + DAO architecture: suppliers, products, customers, inventory, sales, plus reports exported to timestamped files.
* **Tech:** Python 3, OOP, MVC, DAO, pickle, FreeSimpleGUI.

---

<div align="center">

### 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luigiferrimaines)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luigiferrimaines@gmail.com)

</div>
