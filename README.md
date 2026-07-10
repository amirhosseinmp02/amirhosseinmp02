<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3500&pause=1000&color=512BD4&center=true&vCenter=true&width=800&lines=Backend+Architect+%7C+.NET+Ecosystem;Architecting+Native+BPMN+%26+DMN+Engines;Designing+Resilient+Distributed+Systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://gravatar.com/instantlycc0316cf35"><img src="https://img.shields.io/badge/Gravatar-Profile-1E8CBE?style=flat-square&logo=gravatar&logoColor=white" alt="Gravatar"></a>
  <a href="https://www.linkedin.com/in/amirhosseinmp02"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:amirhosseinmp02@gmail.com"><img src="https://img.shields.io/badge/Email-amirhosseinmp02@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<br>

I am a **Backend Software Architect** specializing in the **.NET ecosystem**. My engineering philosophy sits at the intersection of complex business orchestration and high-performance distributed systems. I don't just write APIs; I build the underlying engines that allow enterprises to model, execute, and scale their core business logic autonomously.

Over the years, I have architected mission-critical platforms for national enterprises, government sectors, and large-scale municipalities. I thrive in the deep end of concurrency, state-machine orchestration, and bulletproof security layers.

---

### 📂 Open Source & Architectural Explorations

I believe in building in public and pushing the boundaries of the .NET ecosystem. Here is a selection of my open-source work, engineered for scale, security, and developer experience.

#### ⚡ Flagship: PepperX.QueryForge
> *A lightweight, provider-agnostic, dynamic query building and execution engine for .NET 10.*

| 🌟 Core Capabilities | 🛡️ Enterprise Security | 🖥️ Frontend Grid Synergy |
| :--- | :--- | :--- |
| **Native Hierarchical Grouping:** Generates deeply nested `key/count/items` JSON trees directly from SQL. | **Bulletproof Validation:** Built-in `SilentStrip` mode prevents schema enumeration and malicious data dumps. | **Purpose-Built for UI Grids:** The ultimate backend counterpart for **DevExtreme**, **AG Grid**, and **Kendo UI**. |
| **Zero Boilerplate:** Beautiful Fluent API or raw JSON payload acceptance from any frontend. | **Strict Mode:** Throws granular `QueryValidationException`s for internal API governance. | **Complex Filtering:** Natively parses deeply nested `AND` / `OR` / `AND NOT` logic groups. |
| **Native AOT & .NET 10:** Built on `System.Text.Json` and Dapper. No heavy reflection overhead. | **Automated Schema:** `IHostedService` auto-deploys required Stored Procedures on startup. | **Server-Side Paging:** Accurately paginates top-level groups or flat rows with total counts. |

<p align="center">
  <a href="https://www.nuget.org/packages/PepperX.QueryForge.Dapper"><img src="https://img.shields.io/badge/NuGet-PepperX.QueryForge.Dapper-512BD4?style=for-the-badge&logo=nuget&logoColor=white" alt="NuGet Dapper"></a>
  <a href="https://github.com/amirhosseinmp02/PepperX"><img src="https://img.shields.io/badge/GitHub-Explore_Source-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

#### 🧪 Architectural Sandboxes
| 📦 Repository | 🛠️ Architecture & Tech Stack | 📖 Overview |
| :--- | :--- | :--- |
| **[Aroma-Store](https://github.com/amirhosseinmp02/Aroma-Store)** | `.NET Core` `EF Core` `Clean Arch` | A full-featured eCommerce platform built strictly on **Clean Architecture** principles. Demonstrates mastery of domain boundaries, code-first DB design, and repository patterns. |
| **[BitcoinMiningCalculator](https://github.com/amirhosseinmp02/BitcoinMiningCalculator)** | `ASP.NET Core` `Razor Pages` `PHP` | A financial utility for calculating crypto mining profitability. Engineered with resilient API proxy integrations to bypass regional network sanctions and restrictions. |

---

### 🧠 The Crown Jewels: Native BPMN & DMN Engines

Rather than relying on heavy, black-box third-party workflow libraries, I engineered **fully native, from-scratch execution engines** for enterprise business logic. These systems currently power thousands of daily operations for major governmental and semi-governmental organizations.

#### ⚙️ Native BPMN 2.0 Execution Engine
*   **Complete Node Implementation:** Built 30+ BPMN 2.0 nodes from scratch (Events, Gateways, Activities, Boundary Elements, Sub-processes).
*   **Custom ADO.NET ORM:** Bypassed heavy ORMs to write a hyper-optimized, custom data-access layer specifically designed for state-machine persistence and rapid graph traversal.
*   **Concurrency & Resilience:** Solved deep race conditions in distributed workflow executions using atomic operations, semaphores, SQL transactions, and SQL Server Service Broker.
*   **Distributed Timers:** Engineered a resilient Quartz-based timer system with persistence and failover support for long-running business processes.

#### 📊 Native DMN (Decision Model and Notation) Engine
*   **Decoupled Business Rules:** Architected a complete DMN backend that allows business analysts to define complex decision tables and literal expressions without requiring C# code deployments.
*   **High-Performance Evaluation:** Built a lightning-fast rule evaluation engine capable of processing complex, multi-hit decision tables in memory with minimal overhead.
*   **Seamless Integration:** Integrated the DMN engine directly into the BPMN execution pipeline, allowing dynamic business rule tasks to resolve seamlessly during workflow orchestration.

---

### 🏛️ Enterprise Scale & Architecture

*   **Microservices & DDD:** Designed DDD/CQRS-driven ecosystems with **Ocelot** API Gateways and **RabbitMQ** event buses. Employed patterns like Customer-Supplier and Shared Kernel to decouple domains.
*   **Identity & Security:** Built custom **OpenID Connect / OAuth 2.0 Identity Providers** utilizing RSA512 JWTs, dynamic API permissions, and Redis-backed distributed session states.
*   **National Scale:** Delivered optimized BPMS and automation platforms for entities including the **Construction and Development of Transportation Infrastructures Company (CDTIC)** and major municipalities.

---

### 🛠️ The Architectural Arsenal

| Domain | Technologies & Patterns |
| :--- | :--- |
| **Core & Frameworks** | `.NET 10/9/8`, `C#`, `ASP.NET Core Minimal APIs`, `Blazor`, `Razor Pages` |
| **Engines & Logic** | `BPMN 2.0`, `DMN`, `State Machines`, `Quartz.NET`, `FluentValidation` |
| **Architecture** | `Microservices`, `DDD`, `CQRS`, `Clean Architecture`, `Modular Monoliths` |
| **Data & Resilience** | `SQL Server`, `EF Core`, `Dapper`, `Custom ADO.NET`, `Redis`, `Elasticsearch` |
| **Messaging & Realtime** | `RabbitMQ`, `SignalR`, `SSE (Server-Sent Events)`, `WebPush`, `Docker`, `GitHub Actions` |
| **Security** | `OAuth2/OIDC`, `JWT (RSA)`, `SSO`, `Trusted Publishing (OIDC)` |

---

### 📊 Community & Ecosystem Footprint

<p align="center">
  <a href="https://github.com/amirhosseinmp02?tab=repositories">
    <img src="https://img.shields.io/badge/Dynamic_Query_Engines-Published_to_NuGet-0078D4?style=for-the-badge&logo=nuget&logoColor=white" alt="NuGet">
  </a>
  <a href="https://github.com/amirhosseinmp02?tab=repositories">
    <img src="https://img.shields.io/badge/BPMN_%26_DMN-Engines_Architected-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
  </a>
  <a href="https://github.com/amirhosseinmp02?tab=repositories">
    <img src="https://img.shields.io/badge/Clean_Architecture-Enterprise_E--Commerce-28A745?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

---

### 🎓 Education & Accolades

*   **MSc. Software Engineering** | *Islamic Azad University* (2026 - Present)
*   **BSc. Computer Engineering** | *Islamic Azad University* (2023 - 2025)
*   **Associate's, Computer Software Engineering** | *Shamsipour Technical and Vocational College, Tehran* (2021 - 2023)
    *   🏆 **Achieved 147th National Rank** in the National Computer Technical Entrance Exam.

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
