<a href="https://www.aiwithdiego.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.gif">
    <img alt="Diego Bauer: I build responsible AI that solves real problems." src="assets/header-light.gif" width="100%">
  </picture>
</a>

<p>
  <a href="https://www.aiwithdiego.com"><img alt="Website" src="https://img.shields.io/badge/aiwithdiego.com-0B0F14?style=for-the-badge&logo=googlechrome&logoColor=5AA9FF"></a>
  <a href="https://www.linkedin.com/in/diego-bauer-domeyko/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0B0F14?style=for-the-badge&logo=linkedin&logoColor=5AA9FF"></a>
</p>

I start with people. I talk to the ones doing the work, research how it really runs, and find the problem worth solving. Then I decide what's worth making and, just as important, what isn't. I ship what has to be done and run it in production, owning both the product decisions and the code along the way.

Most of my work answers one question: **how do you let an agent act on a business without it doing something the owner wouldn't?** I design for the EU AI Act and GDPR from the start, and [Hank](https://github.com/AIwithDiego/hank), a security and compliance reviewer I made, checks my projects before they ship. AI governance keeps those rules enforced once the agent is live: the owner's rules run as evals on every change, and a human stays in the loop to approve before the agent acts.

**Latest:** [AI Exposure Scan](https://github.com/AIwithDiego/ai-exposure-scan), built in a day with Devin at the Cognition x Give(a)Go build day, Dublin, November 2026. [Try the demo](https://aiwithdiego.github.io/ai-exposure-scan/).

## Featured work

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/ai-exposure-scan"><img src="assets/cover-ai-exposure-scan.png" alt="AI Exposure Scan: a café scores 52/100 because its OpenAI key sits in public JavaScript"></a>
<h3><a href="https://github.com/AIwithDiego/ai-exposure-scan">AI Exposure Scan</a></h3>
Type in a website and see what AI it exposes: chat widgets, AI keys in public code, where the data goes, and whether the site says it uses AI. Every finding comes with its evidence. Built in a day with Devin. <a href="https://aiwithdiego.github.io/ai-exposure-scan/">Try the demo</a>.
<br><br>
<code>Python</code> <code>Playwright</code> <code>React</code> <code>EU AI Act</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/taste-to-evals"><img src="assets/cover-taste-to-evals.png" alt="taste-to-evals: a rota change sent back because Tom would work 48 hours"></a>
<h3><a href="https://github.com/AIwithDiego/taste-to-evals">taste-to-evals</a></h3>
An agent interviews a business owner, turns their rules into typed checks and an AI judge, and gates every change another agent proposes before a human approves. Presented at AI Tinkerers Dublin.
<br><br>
<code>TypeScript</code> <code>Claude</code> <code>MCP</code> <code>Evals</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/aigentsmith-architecture"><img src="assets/cover-aigentsmith.png" alt="AIgentSmith architecture: control plane, single-use tokens and sealed tenants"></a>
<h3><a href="https://github.com/AIwithDiego/aigentsmith-architecture">AIgentSmith architecture</a></h3>
Case study of the agent platform I designed and built for small businesses: an agent engine, a runtime gateway with signed single-use tokens, and a sealed unit per business.
<br><br>
<code>Architecture</code> <code>Security</code> <code>Multi-tenant</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/haven"><img src="assets/cover-haven.png" alt="Haven: an approval card before the agent runs a shell command"></a>
<h3><a href="https://github.com/AIwithDiego/haven">Haven</a></h3>
A calm macOS workspace for Claude Code, Codex and real terminals, side by side as named tasks, with an approval card before any risky action.
<br><br>
<code>Electron</code> <code>TypeScript</code> <code>Swift</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/hank"><img src="assets/cover-hank.png" alt="Hank: security and compliance findings ranked by severity"></a>
<h3><a href="https://github.com/AIwithDiego/hank">Hank</a></h3>
An AI security and EU compliance analyst for Claude Code: OWASP LLM and Agentic Top 10 reviews, plus GDPR, AI Act, NIS2, CRA and DORA.
<br><br>
<code>Claude Code plugin</code> <code>OWASP</code> <code>EU law</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/AIwithDiego/byjosem-case-study"><img src="assets/cover-byjosem.png" alt="ByJoseM: the events hub in the admin"></a>
<h3><a href="https://github.com/AIwithDiego/byjosem-case-study">ByJoseM case study</a></h3>
A custom operations platform for an Irish premium bartending business: CRM, quotes, invoices, stock and staff. Shipped continuously for a year.
<br><br>
<code>Client work</code> <code>Case study</code>
</td>
</tr>
</table>

**Also built:** [Robogotchi](https://github.com/AIwithDiego/robogotchi), a virtual pet robot you raise in the browser ([play it](https://robogotchi-nine.vercel.app)) · [attendance-mcp](https://github.com/AIwithDiego/attendance-mcp), an MCP server that lets an AI assistant analyse staff attendance with read-only tools · [Gym Routine Builder](https://github.com/AIwithDiego/gym-routine-builder), plan routines and run them set by set ([live](https://gym-routine-builder.vercel.app)).

Most of my production work is for clients and lives in private repos. The case studies describe those systems without the code.

## What went wrong

Most repos close with "What I learned". These three taught me the most.

| | |
|---|---|
| **The server was an open door.** v1 kept the database key off the browser, and its API routes let anyone read and change the data anyway. | [Gym Routine Builder](https://github.com/AIwithDiego/gym-routine-builder#what-i-learned) |
| **An empty list is an answer.** A misspelt site name returned nothing, and the model would have reported "nobody was late". | [attendance-mcp](https://github.com/AIwithDiego/attendance-mcp#what-i-learned) |
| **An approval gate is only as honest as what it shows.** A tool name and a cut-off details view is really just "Allow?". | [Haven](https://github.com/AIwithDiego/haven#what-i-learned) |

## How I work

- **Design before code.** A written design doc before anything non-trivial, reviewed from product, architecture, QA and security angles.
- **Evals, not vibes.** Tests on everything that ships. For agent behaviour that means evals with deterministic checks.
- **Secure by default.** Auth and row-level security on anything that holds user data, secret scanning in CI, and an independent security review before release.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-0B0F14?style=flat-square&logo=typescript&logoColor=5AA9FF) ![Next.js](https://img.shields.io/badge/Next.js-0B0F14?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-0B0F14?style=flat-square&logo=react&logoColor=5AA9FF) ![Python](https://img.shields.io/badge/Python-0B0F14?style=flat-square&logo=python&logoColor=5AA9FF) ![Supabase](https://img.shields.io/badge/Supabase-0B0F14?style=flat-square&logo=supabase&logoColor=3FCF8E) ![Postgres](https://img.shields.io/badge/Postgres-0B0F14?style=flat-square&logo=postgresql&logoColor=5AA9FF) ![Electron](https://img.shields.io/badge/Electron-0B0F14?style=flat-square&logo=electron&logoColor=5AA9FF) ![Claude](https://img.shields.io/badge/Claude-0B0F14?style=flat-square&logo=anthropic&logoColor=D97757) ![MCP](https://img.shields.io/badge/MCP-0B0F14?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-0B0F14?style=flat-square&logo=vercel&logoColor=white)
