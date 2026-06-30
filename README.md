# Scott Murphy — Software Engineering Portfolio

> **Senior Software Engineer & Solutions Architect**
> .NET modernization + AI / agentic systems · 15+ years
> Enterprise .NET & cloud architecture, and an independent founder shipping AI-native products end to end.

---

## About

I'm a senior software engineer and solutions architect with 15+ years building enterprise-grade systems across .NET, cloud, and integration-heavy environments — and the founder of **Carborundum AI**, where I design and ship AI-native products from zero.

My work spans two complementary tracks. The first is **application modernization**: legacy .NET decomposition, migration to .NET Core / .NET 10, Clean Architecture and modular-monolith refactoring, Azure-native APIs, and enterprise integrations (Salesforce, document-management platforms, AI-assisted processing). The second is **applied AI engineering**: multi-agent orchestration on the Claude API, RAG and memory pipelines, and agentic workflow design — built from first principles, not wrapper libraries.

I own complex architecture end-to-end and move from architecture to working code to deployed system without a committee. Most recently I delivered cloud-native .NET 10 microservices and AI-assisted insurance workflows for Lockton on a Perficient app-modernization engagement; independently I've built and shipped two complete products — Carborundum AI and MiChoice — solo.

**What I bring to a team:**

- Application modernization from assessment to delivery — legacy decomposition, microservices and modular-monolith refactoring, Azure-native APIs
- Applied AI engineering — multi-agent orchestration on the Claude/Anthropic API, RAG/memory pipelines, agentic workflow design
- Full-stack product delivery — Next.js/React front ends, .NET/Blazor services, Stripe, CI/CD, deployed and running in production
- Enterprise integration depth — Salesforce (Forza.Net/SOQL), M-Files, document processing, distributed caching
- The ability to go from architecture to deployed system independently

---

## Featured Projects

| Project | What it does | Tech stack | Link |
|---------|-------------|------------|------|
| **Carborundum AI** | AI-native field-operations platform for trades businesses (HVAC, plumbing, electrical), built from zero. A Next.js platform (25+ routes, subdomain routing, Vercel auto-deploy) over a modular ERP suite (Manifold) covering job costing, scheduling, CRM, and invoicing; a multi-agent AI layer integrating the Claude API, ElevenLabs voice, and HeyGen avatars under a written operating constitution; Stripe payment flows; and a React Native companion field app (Titanium). WCAG 2.1 AA across the product surface. | Next.js, React, Node, Claude API, React Native, Stripe, Vercel | [carborundum.ai](https://www.carborundum.ai) |
| **MiChoice** | Multi-module K-12 school-nutrition SaaS suite, built end-to-end. Multi-tenant modules for district back-office (miComs), parent free-&-reduced applications (miFAR), cashier POS (miMeal), and time-clock (miTimes), plus an AI advisory insight layer (miAgentic) that switches to the Anthropic API for recommendations. Deployed on Railway. | C#/.NET, Blazor Server, EF Core, Next.js/React, Anthropic API, Railway | private — demo on request |
| **A.S.K (Agent Skills Kernel)** | A versioned, composable library of AI agent capabilities. Think `.dll` files for AI systems — write a capability once (GitHub push, Telegram notify, Vercel deploy), invoke it from any agent. Includes a three-tier skill taxonomy, a reference executor, cryptographic skill signing, and a production skill set. | Python (stdlib), Markdown, YAML, Supabase, Telegram Bot API, Vercel API | [srmbsrg/ask-kernel](https://github.com/srmbsrg/ask-kernel) |
| **agent-spawner-demo** | Dynamic agent instantiation with template inheritance, capability resolution, and full lifecycle management. Extracted from a multi-agent platform running concurrent domain agents — templates define blueprints, the spawner resolves inheritance at instantiation time, and a single command dispatcher handles all lifecycle transitions (spawn / start / pause / terminate / restart / assignTask). | TypeScript, Node.js | [srmbsrg/agent-spawner-demo](https://github.com/srmbsrg/agent-spawner-demo) |
| **multi-model-router** | Per-stage multi-LLM routing with cost/quality/speed metadata, deterministic-first reasoning, and a hard token gate for budget enforcement. Extracted from a 4-stage code-generation pipeline (architecture → DB schema → API routes → UI components) that routes across multiple model providers — reasoning-heavy stages get a stronger model; latency-sensitive stages get a faster one. Daily token budget + per-minute rate limit cut runaway spend. | TypeScript, Node.js, OpenAI-compatible API | [srmbsrg/multi-model-router](https://github.com/srmbsrg/multi-model-router) |
| **ThreadingTemplate** | Async I/O patterns — concurrent task orchestration with thread pools and non-blocking operations. | C#, .NET, System.Threading, TPL, log4net | [srmbsrg/ThreadingTemplate](https://github.com/srmbsrg/ThreadingTemplate) |

---

## Professional Experience

**Perficient, Inc.** — Senior Technical Consultant, App Modernization · *Nov 2025 – Apr 2026*
Delivered cloud-native .NET 10 microservices and enterprise API engineering for Lockton on a large-scale application-modernization engagement. Designed a Binder Management API suite using Clean Architecture and modular domain layers; integrated QuoteCompare AI to automate binder document extraction and premium calculation; implemented M-Files document-management integration; architected an Azure Redis distributed-caching strategy that reduced redundant Salesforce calls; built Salesforce integration microservices (Forza.Net / SOQL); and established CI/CD with NUnit/Moq test coverage.

**Loomis Armored** — Senior Software Engineer · *Mar 2022 – Mar 2025*
Led the modernization of Loomis Direct from legacy .NET to .NET Core and a React SPA, improving maintainability and UI responsiveness. Drove Azure cloud adoption and optimized CI/CD pipelines, cutting deployment time by 30%.

**Transcore** — Senior Software Engineer (Contract) · *Oct 2019 – Nov 2021*
Delivered modernization solutions for state-government systems using Angular, C#, and Azure-hosted SQL; converted multi-threaded legacy data processing into scalable, maintainable modules.

**Roquemore** — Senior Software Engineer · *Jun 2015 – Sep 2019*
Modernized internal WPF and MVC applications and led multiple third-party integrations including Equifax, TransUnion, and CarFax.

**Automated Integration** — Senior Software Engineer · *Jan 2011 – Mar 2015*
Revitalized a legacy ERP/dispatching system and developed C# / SQL Server field-service mobile applications.

---

## Skills & Stack

- **Backend:** C#, .NET 10 / .NET Core, Clean Architecture, DDD, REST APIs, EF Core
- **Front-end:** Next.js, React, Angular, Blazor Server, React Native
- **AI engineering:** Multi-agent orchestration (Claude / Anthropic API), RAG & memory pipelines, agentic workflow design, prompt architecture, ElevenLabs voice
- **Cloud & DevOps:** Azure (App Services, Redis, Storage), Vercel, Railway, CI/CD (Azure DevOps, Jenkins, Git, Octopus)
- **Integrations & payments:** Salesforce (Forza.Net / SOQL), M-Files, Stripe, document processing
- **Also:** Node.js, Python, SQL Server, NUnit / Moq

---

## What I'm Building

**Carborundum AI** is an AI-native operations platform for small-to-mid trades businesses — the kind running on whiteboards and spreadsheets, underserved by enterprise ERP. The core components:

- **Manifold** — the ERP foundation: lead capture → customer record → sales order → dispatch → fulfillment → invoicing → payment, with a plugin/element architecture for vertical-specific add-ons.
- **Tesa** — a persistent AI operator running on the Claude API: inbound communications (SMS, Telegram, voice), RAG-based memory, and scheduled autonomous workflows.
- **A multi-agent layer** — AI officers operating with bounded autonomy under a written operating constitution, with persistent file-based memory across sessions.

The design philosophy: AI systems should be *engineered*, not prompted. Skills over prompts. Versioning over vibes. Composition over monoliths.

---

## Contact

**Email:** scott@carborundum.ai
**Web:** [scottroymurphy.com](https://scottroymurphy.com) · [carborundum.ai](https://www.carborundum.ai)
**GitHub:** [github.com/srmbsrg](https://github.com/srmbsrg)
**LinkedIn:** [linkedin.com/in/scottroymurphy](https://linkedin.com/in/scottroymurphy)

Open to senior engineering, solutions-architect, and app-modernization roles where the work involves building real systems — .NET modernization, AI/agentic infrastructure, or both.
