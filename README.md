# Scott Murphy — AI Engineering Portfolio

> **Principal AI Engineer · Head of AI · Fractional CTO**
> Building agentic infrastructure, LLM tooling, and autonomous systems for businesses that need AI to actually work.

---

## About

I'm the founder of **Foundry Familiars** and **Ghost Foundry Syndicate (GFS)** — an AI operations platform that deploys autonomous AI systems for SMBs. My work lives at the intersection of applied AI engineering and practical business automation: agentic architectures, multi-model orchestration, LLM tooling, and the operational infrastructure that makes AI systems reliable at scale.

I don't build demos. I build systems that run in production — autonomous agents that deploy code, manage purchases, maintain persistent memory, and communicate with humans through structured interfaces. The projects in this portfolio represent real infrastructure used in real operations.

**What I bring to a team:**

- Agentic system design from first principles (not wrapper libraries)
- Production experience with multi-model orchestration and long-running autonomous agents
- A framework-level approach to AI capability management — skills, versioning, composability
- Deep familiarity with the LLM tool ecosystem: Claude, GPT-4, Vercel AI SDK, Supabase, and the APIs that matter
- The ability to move from architecture to working code to deployed system without a committee

**Reach me:** ghostfoundrysyndicate@outlook.com

---

## Featured Projects

| Project | What it does | Tech stack | Link |
|---------|-------------|------------|------|
| **A.S.K (Agent Skills Kernel)** | A versioned, composable library of AI agent capabilities. Think `.dll` files for AI systems — write a capability once (GitHub push, Telegram notify, Vercel deploy, autonomous purchase), invoke it from any agent. Includes a three-tier skill taxonomy, a reference executor, cryptographic skill signing, and the full production skill set powering the GFS platform. | Python (stdlib), Markdown, YAML, Supabase, Telegram Bot API, Vercel API, Privacy.com, HeyGen | [srmbsrg/ask-kernel](https://github.com/srmbsrg/ask-kernel) |
| **agent-spawner-demo** | Dynamic agent instantiation with template inheritance, capability resolution, and full lifecycle management. Extracted from a production multi-agent ERP platform running 8+ concurrent domain agents (Finance, HR, Sales, Compliance…). Shows how to make agents data-driven: templates define blueprints, the spawner resolves inheritance at instantiation time, and a single command dispatcher handles all lifecycle transitions (spawn / start / pause / terminate / restart / assignTask). | TypeScript, Node.js | [srmbsrg/agent-spawner-demo](https://github.com/srmbsrg/agent-spawner-demo) |
| **multi-model-router** | Per-stage multi-LLM routing with cost/quality/speed metadata, deterministic-first reasoning, and a hard token gate for budget enforcement. Extracted from a production 4-stage code-generation pipeline (architecture → DB schema → API routes → UI components) that routes across 7 model providers. Architecture stage gets Claude Sonnet 4 for reasoning depth; UI stage gets GPT-4o for speed. Daily token budget + per-minute rate limit cut runaway spend. | TypeScript, Node.js, OpenAI-compatible API | [srmbsrg/multi-model-router](https://github.com/srmbsrg/multi-model-router) |

---

## What I'm Building

**Ghost Foundry Syndicate** is an autonomous AI operations platform. The core components:

- **Tesa** — A persistent AI operator that manages the GFS platform: deploying code, handling purchases, maintaining memory across sessions, generating content, and interfacing with external APIs — all without human intervention for routine operations.
- **Dark Factory** — A self-building code generator that designs, writes, evaluates, and commits code autonomously. DF generates A.S.K skill invocations rather than re-implementing known capabilities — it uses the library, not the scratch pad.
- **OpenBrain** — A vector memory layer (Supabase) that gives AI agents persistent, searchable knowledge across sessions. Tesa's context doesn't evaporate when a conversation ends.
- **A.S.K** — The skill library that ties it all together. Every capability the system needs is defined once, versioned, and callable by name.

The design philosophy: AI systems should be *engineered*, not prompted. Skills over prompts. Versioning over vibes. Composition over monoliths.

---

## Contact

**Email:** ghostfoundrysyndicate@outlook.com
**GitHub:** [github.com/srmbsrg](https://github.com/srmbsrg)

Open to Principal AI Engineer, Head of AI, and Fractional CTO engagements where the work involves building real agentic infrastructure — not slide decks.
