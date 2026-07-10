<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3500&pause=1000&color=512BD4&center=true&vCenter=true&width=800&lines=Backend+Architect+%7C+.NET+Ecosystem;Architecting+Native+BPMN+%26+DMN+Engines;Designing+Resilient+Distributed+Systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://gravatar.com/instantlycc0316cf35"><img src="https://img.shields.io/badge/Gravatar-Profile-1E8CBE?style=flat-square&logo=gravatar&logoColor=white" alt="Gravatar"></a>
</p>

<br>

### 👨‍💻 About Me

I am a **Backend Software Architect** specializing in the **.NET ecosystem**. My engineering philosophy sits at the intersection of complex business orchestration and high-performance distributed systems. I don't just write APIs; I build the underlying engines that allow enterprises to model, execute, and scale their core business logic autonomously.

Over the years, I have architected mission-critical platforms for national enterprises, government sectors, and large-scale municipalities. I thrive in the deep end of concurrency, state-machine orchestration, and bulletproof security layers.

* 🔭 I’m currently architecting native **BPMN 2.0** & **DMN** execution engines.
* 🌱 I’m exploring **.NET 10** and **performance optimization**.
* ⚡ **Fun fact:** I write literary fantasy when I'm not writing C#.

---

### 🚀 Flagship Open Source: PepperX.QueryForge

<p align="center">
  <img src="https://raw.githubusercontent.com/amirhosseinmp02/PepperX/main/icon.png" width="120" alt="PepperX Logo" />
</p>

<p align="center">
  <a href="https://www.nuget.org/packages/PepperX.QueryForge.Dapper"><img src="https://img.shields.io/nuget/v/PepperX.QueryForge.Dapper?style=for-the-badge&logo=nuget&logoColor=white&label=Version" alt="NuGet Version"></a>
  <a href="https://github.com/amirhosseinmp02/PepperX"><img src="https://img.shields.io/badge/Explore_Source-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

A lightweight, provider-agnostic, dynamic query engine for .NET 10. Build complex, paginated, and hierarchically grouped queries using a fluent C# API or accept them as JSON payloads from any frontend. Published via **OIDC Trusted Publishing** with automated GitHub Actions CI/CD.

<details>
<summary><b>🌟 Core Capabilities & Architecture</b></summary>
<br>

* **Native Hierarchical Grouping:** Generates deeply nested `key/count/items` JSON trees directly from SQL.
* **Zero Boilerplate:** Beautiful Fluent API or raw JSON payload acceptance from any frontend.
* **Performance & .NET 10:** Built on `System.Text.Json` and Dapper. Zero heavy reflection overhead.

</details>

<details>
<summary><b>🛡️ Enterprise Security & Validation</b></summary>
<br>

* **Bulletproof Validation:** Built-in `SilentStrip` mode prevents schema enumeration and malicious data dumps.
* **Strict Mode:** Throws granular `QueryValidationException`s for internal API governance.
* **Automated Schema:** `IHostedService` auto-deploys required Stored Procedures on startup.

</details>

<details>
<summary><b>🖥️ Frontend Grid Synergy</b></summary>
<br>

* **Purpose-Built for UI Grids:** The ultimate backend counterpart for **DevExtreme**, **AG Grid**, and **Kendo UI**.
* **Complex Filtering:** Natively parses deeply nested `AND` / `OR` / `AND NOT` logic groups.
* **Server-Side Paging:** Accurately paginates top-level groups or flat rows with total counts.

</details>

#### 🧪 Architectural Sandboxes

| 📦 Repository | 🛠️ Architecture & Tech Stack | 📖 Overview |
| :--- | :--- | :--- |
| **[Aroma-Store](https://github.com/amirhosseinmp02/Aroma-Store)** | `.NET Core` `EF Core` `Clean Arch` | A full-featured eCommerce platform built strictly on **Clean Architecture** principles. Demonstrates mastery of domain boundaries, code-first DB design, and repository patterns. |
| **[BitcoinMiningCalculator](https://github.com/amirhosseinmp02/BitcoinMiningCalculator)** | `ASP.NET Core` `Razor Pages` `PHP` | A financial utility for calculating crypto mining profitability. Engineered with resilient API proxy integrations to bypass regional network sanctions and restrictions. |

---

### 🧠 The Crown Jewels: Native BPMN & DMN Engines

Rather than relying on heavy, black-box third-party workflow libraries, I engineered **fully native, from-scratch execution engines** for enterprise business logic. These systems currently power thousands of daily operations for major governmental and semi-governmental organizations.

<details>
<summary><b>⚙️ Native BPMN 2.0 Execution Engine</b></summary>
<br>

* **Complete Node Implementation:** Built 30+ BPMN 2.0 nodes from scratch (Events, Gateways, Activities, Boundary Elements, Sub-processes).
* **Custom ADO.NET ORM:** Bypassed heavy ORMs to write a hyper-optimized, custom data-access layer specifically designed for state-machine persistence and rapid graph traversal.
* **Concurrency & Resilience:** Solved deep race conditions in distributed workflow executions using atomic operations, semaphores, SQL transactions, and SQL Server Service Broker.
* **Distributed Timers:** Engineered a resilient Quartz-based timer system with persistence and failover support for long-running business processes.

</details>

<details>
<summary><b>📊 Native DMN (Decision Model and Notation) Engine</b></summary>
<br>

* **Decoupled Business Rules:** Architected a complete DMN backend that allows business analysts to define complex decision tables and literal expressions without requiring C# code deployments.
* **High-Performance Evaluation:** Built a lightning-fast rule evaluation engine capable of processing complex, multi-hit decision tables in memory with minimal overhead.
* **Seamless Integration:** Integrated the DMN engine directly into the BPMN execution pipeline, allowing dynamic business rule tasks to resolve seamlessly during workflow orchestration.

</details>

---

### 🏛️ Enterprise Scale & Architecture

* 🌐 **Microservices & DDD:** Designed DDD/CQRS-driven ecosystems with **Ocelot** API Gateways and **RabbitMQ** event buses. Employed patterns like Customer-Supplier and Shared Kernel to decouple domains.
* 🔐 **Identity & Security:** Built custom **OpenID Connect / OAuth 2.0 Identity Providers** utilizing RSA512 JWTs, dynamic API permissions, and Redis-backed distributed session states.
* 🏢 **National Scale:** Delivered optimized BPMS and automation platforms for entities including the **Construction and Development of Transportation Infrastructures Company (CDTIC)** and major municipalities.

---

### 🛠️ The Architectural Arsenal

<table width="100%">
  <tr>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"><br>
      <sub><b>Core Language</b></sub>
    </td>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/.NET_10-0078D4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"><br>
      <sub><b>Frameworks</b></sub>
    </td>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL"><br>
      <sub><b>Data & ORM</b></sub>
    </td>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ"><br>
      <sub><b>Messaging</b></sub>
    </td>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"><br>
      <sub><b>Caching</b></sub>
    </td>
    <td align="center" width="16%">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"><br>
      <sub><b>DevOps</b></sub>
    </td>
  </tr>
</table>

<details>
<summary><b>📋 View Detailed Technology Matrix</b></summary>
<br>

* **Architecture:** Microservices, DDD, CQRS, Clean Architecture, Modular Monoliths, BPMN/DMN
* **Realtime & Web:** SignalR, SSE (Server-Sent Events), WebPush, Minimal APIs, Blazor
* **Security:** OAuth2/OIDC, JWT (RSA), SSO, Trusted Publishing (OIDC)

</details>

---

### 🎓 Education & Accolades

* 🎓 **MSc. Software Engineering** | *Islamic Azad University* (2025 - Present)
* 🎓 **BSc. Computer Engineering** | *Islamic Azad University* (2023 - 2025)
* 🏆 **Associate's, Computer Software Engineering** | *Shamsipour Technical and Vocational College, Tehran* (2021 - 2023)
  * *Achieved **147th National Rank** in the National Computer Technical Entrance Exam.*

---

<br>

### 🌌 Beyond the Terminal: Amnesia Barriers

Code is the architecture of logic; writing is the architecture of the soul. 
When I am not debugging distributed transactions or optimizing state-machine executions, I am a storyteller. I explore the liminal spaces between memory, oblivion, and the multiverse through literary fantasy.

<p align="center">
  <a href="https://t.me/Amnesia_Barriers">
    <img src="https://img.shields.io/badge/Join_Amnesia__Barriers-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Amnesia Barriers">
  </a>
</p>

<p align="center">
  <i>"You cannot forget it, because its forgetting is your oblivion.<br>
  So embrace it with all your heart."</i>
</p>

<p align="center">
  <sub>In the realm of literary fantasy, perceptions are born freely from parallel worlds where words flow not from the well of personal experience, but from the endless well of imagination and inspiration.</sub>
</p>

<br>

<p align="center">
  <i>"Software Engineer by profession, explorer by nature."</i><br>
  <sub>Let's connect and build something extraordinary.</sub>
</p>
