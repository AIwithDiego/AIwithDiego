<a href="https://www.aiwithdiego.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.png">
    <img alt="Diego Bauer: Product Owner who builds the AI, ships it, and owns what it does." src="assets/header-light.png" width="100%">
  </picture>
</a>

<p>
  <a href="https://www.aiwithdiego.com"><img alt="Website" src="https://img.shields.io/badge/aiwithdiego.com-0B0F14?style=for-the-badge&logo=googlechrome&logoColor=5AA9FF"></a>
  <a href="https://www.linkedin.com/in/diego-bauer-domeyko/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0B0F14?style=for-the-badge&logo=linkedin&logoColor=5AA9FF"></a>
</p>

I build agentic AI systems that have run on real business data, and I work on both sides of them: the product decisions and the code. Most of what I build is about one question: **how do you let an agent act on a business without it doing something the owner wouldn't?**

**Latest:** [taste-to-evals](https://github.com/AIwithDiego/taste-to-evals), presented at AI Tinkerers Dublin, October 2026.

## Featured work

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/taste-to-evals"><img src="assets/cover-taste-to-evals.png" alt="taste-to-evals: a rota change sent back because Tom would work 48 hours"></a>
<h3><a href="https://github.com/AIwithDiego/taste-to-evals">taste-to-evals</a></h3>
An agent interviews a business owner, turns their rules into typed checks and an AI judge, and gates every change another agent proposes before a human approves. Presented at AI Tinkerers Dublin.
<br><br>
<code>TypeScript</code> <code>Claude</code> <code>MCP</code> <code>Evals</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/aigentsmith-architecture"><img src="assets/cover-aigentsmith.png" alt="AIgentSmith architecture: control plane, single-use tokens and sealed tenants"></a>
<h3><a href="https://github.com/AIwithDiego/aigentsmith-architecture">AIgentSmith architecture</a></h3>
Case study of the agent platform I designed and built for small businesses: an agent engine, a runtime gateway with signed single-use tokens, and a sealed unit per business.
<br><br>
<code>Architecture</code> <code>Security</code> <code>Multi-tenant</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/haven"><img src="assets/cover-haven.png" alt="Haven: an approval card before the agent runs a shell command"></a>
<h3><a href="https://github.com/AIwithDiego/haven">Haven</a></h3>
A calm macOS workspace for Claude Code, Codex and real terminals, side by side as named tasks, with an approval card before any risky action.
<br><br>
<code>Electron</code> <code>TypeScript</code> <code>Swift</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/hank"><img src="assets/cover-hank.png" alt="Hank: security and compliance findings ranked by severity"></a>
<h3><a href="https://github.com/AIwithDiego/hank">Hank</a></h3>
An AI security and EU compliance analyst for Claude Code: OWASP LLM and Agentic Top 10 reviews, plus GDPR, AI Act, NIS2, CRA and DORA.
<br><br>
<code>Claude Code plugin</code> <code>OWASP</code> <code>EU law</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/byjosem-case-study"><img src="assets/cover-byjosem.png" alt="ByJoseM: the events hub in the admin"></a>
<h3><a href="https://github.com/AIwithDiego/byjosem-case-study">ByJoseM case study</a></h3>
A custom operations platform for an Irish premium bartending business: CRM, quotes, invoices, stock and staff. Shipped continuously for a year.
<br><br>
<code>Client work</code> <code>Case study</code>
</td>
<td width="50%" valign="top">
<a href="https://robogotchi-nine.vercel.app"><img src="assets/cover-robogotchi.png" alt="Robogotchi: the landing screen with a robot in its nursery"></a>
<h3><a href="https://github.com/AIwithDiego/robogotchi">Robogotchi</a></h3>
A virtual pet in the browser: raise a robot in real time, teach it how to treat humans, and keep it alive. <a href="https://robogotchi-nine.vercel.app">Play it</a>.
<br><br>
<code>React</code> <code>TypeScript</code> <code>No backend</code>
</td>
</tr>
</table>

**Also built:** [attendance-mcp](https://github.com/AIwithDiego/attendance-mcp), an MCP server that lets an AI assistant analyse staff attendance with read-only tools · [Gym Routine Builder](https://github.com/AIwithDiego/gym-routine-builder), plan routines and run them set by set ([live](https://gym-routine-builder.vercel.app)).

Most of my production work is for clients and lives in private repos. The case studies describe those systems without the code.

## How I work

- **Design before code.** A written design doc before anything non-trivial, reviewed from product, architecture, QA and security angles.
- **Evals, not vibes.** Tests on everything that ships. For agent behaviour that means evals with deterministic checks.
- **Secure by default.** Auth and row-level security on anything that holds user data, secret scanning in CI, and an independent security review before release.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-0B0F14?style=flat-square&logo=typescript&logoColor=5AA9FF) ![Next.js](https://img.shields.io/badge/Next.js-0B0F14?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-0B0F14?style=flat-square&logo=react&logoColor=5AA9FF) ![Python](https://img.shields.io/badge/Python-0B0F14?style=flat-square&logo=python&logoColor=5AA9FF) ![Supabase](https://img.shields.io/badge/Supabase-0B0F14?style=flat-square&logo=supabase&logoColor=3FCF8E) ![Postgres](https://img.shields.io/badge/Postgres-0B0F14?style=flat-square&logo=postgresql&logoColor=5AA9FF) ![Electron](https://img.shields.io/badge/Electron-0B0F14?style=flat-square&logo=electron&logoColor=5AA9FF) ![Claude](https://img.shields.io/badge/Claude-0B0F14?style=flat-square&logo=anthropic&logoColor=D97757) ![MCP](https://img.shields.io/badge/MCP-0B0F14?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-0B0F14?style=flat-square&logo=vercel&logoColor=white)
