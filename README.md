# Diego Bauer

AI Product Manager and Technical Product Owner, based in Dublin, Ireland.
I build agentic AI systems that have run on real business data, and I work on both sides of them: the product decisions and the code.

## Projects

| Project | What it is | Links |
|---|---|---|
| **AIgentSmith architecture** | Case study of an agent platform I designed and built: the agent engine, a runtime gateway with signed single-use tokens, and a multi-tenant substrate where each business gets its own sealed agent. | [repo](https://github.com/AIwithDiego/aigentsmith-architecture) |
| **Haven** | macOS desktop app that gives Claude Code, Codex and real terminals one home. Electron. | [repo](https://github.com/AIwithDiego/haven) |
| **attendance-mcp** | MCP server that lets an AI assistant analyse staff attendance: 7 read-only tools, a resource and a prompt. TypeScript, official MCP SDK, tested live with Claude Code. | [repo](https://github.com/AIwithDiego/attendance-mcp) |
| **Hank** | AI-security scanner and training quiz for Claude Code setups, mapped to the OWASP LLM Top 10. | [repo](https://github.com/AIwithDiego/hank) |
| **ByJoseM case study** | Custom business platform for an Irish events company: CRM, quotes, invoices, stock, staff. | [repo](https://github.com/AIwithDiego/byjosem-case-study) |
| **Gym Routine Builder** | Plan gym routines and run them set by set. Next.js, Supabase Auth, members-only row-level security. | [repo](https://github.com/AIwithDiego/gym-routine-builder) · [live](https://gym-routine-builder.vercel.app) |
| **Robogotchi** | A virtual pet that lives in the browser. React, TypeScript, tested across three browser engines. | [repo](https://github.com/AIwithDiego/robogotchi) · [play](https://robogotchi-nine.vercel.app) |

Most of my production work is for clients and lives in private repos. The case studies describe those systems without the code.

## How I work

- A written design doc before any non-trivial code, reviewed from product, architecture, QA and security angles.
- Tests on everything that ships. For agent behaviour that means evals with deterministic checks, not vibes.
- Security by default: auth and row-level security on anything that holds user data, secret scanning in CI, and an independent security review before anything is released.

## Stack

TypeScript, Next.js, React, Supabase / Postgres, Electron, Python, Claude and agent tooling, Vercel.

## Contact

- Site: [www.aiwithdiego.com](https://www.aiwithdiego.com)
- LinkedIn: [diego-bauer-domeyko](https://www.linkedin.com/in/diego-bauer-domeyko/)
