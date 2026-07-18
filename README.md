# hi, I'm Rodolfo 👋

> 🧰 Local-first tools for AI agents and developers.

I build things that run on **your own machine** — agent plugins, CLIs, and local-first infrastructure.
No SaaS, no daemon, no data leaving your laptop.

Most of my work lives at the seam between **AI agents and real engineering process**: how you get from
an idea to shipped code without the agent hallucinating the middle. Everything I ship is plain files,
plain markdown, and commands you can read before you run them.

---

### Tech I ship with

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![SvelteKit](https://img.shields.io/badge/-SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white)
![Shell](https://img.shields.io/badge/-Shell-4D4D4D?style=flat&logo=gnu-bash&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-6E40C9?style=flat&logoColor=white)

[![Sponsors](https://img.shields.io/github/sponsors/rodolfochicone?label=Sponsors&color=ea4aaa&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/rodolfochicone)

---

## 🧭 Start here

If you only have a minute, these are the ones I'd point you to:

- 🧩 **[rc-project](https://github.com/rodolfochicone/rc-project)** — An agent plugin that drives the full lifecycle of AI-assisted development: idea → PRD → TechSpec → tasks → execution → review → remediation. Runs inside Claude Code, Codex and friends.
- 🧹 **[gh-repo-audit](https://github.com/rodolfochicone/gh-repo-audit)** — Points at the junk in your public GitHub profile: stale forks, abandoned projects, committed secrets. Prints the fix, executes nothing.
- 🔌 **[lib-acp](https://github.com/rodolfochicone/lib-acp)** — Talk to Claude Code and Codex from Node.js over the Agent Client Protocol. Three methods, streaming sessions, typed errors.
- 🏅 **[gh-achievements](https://github.com/rodolfochicone/gh-achievements)** — The GitHub API doesn't expose profile achievements — but it exposes the numbers behind them. One shell script, no deps beyond `gh`.

---

## 🤖 The RC stack — *the agent harness*

The thesis: agents are strong at writing code and terrible at knowing **what** to write and **when
they're done**. They need a harness — artifacts, phases, review gates — to turn a one-shot generation
into shippable software.

| Project | What it does |
| --- | --- |
| 🧩 **[rc-project](https://github.com/rodolfochicone/rc-project)** | Skills and agents plugin for Claude Code: real engineering workflows from PRD to PR. Cost-tiered specialists route recon to cheap models and hard reasoning to strong ones. Every artifact is plain markdown under `.rc/`. *(MIT)* |
| 🔌 **[lib-acp](https://github.com/rodolfochicone/lib-acp)** | Node.js client library for Claude Code and Codex over the **Agent Client Protocol**. Hides subprocess management, JSON-RPC framing and session lifecycle behind three methods: create a client, start a session, stream prompts. *(TypeScript, MIT)* |

---

## 🛠️ Shell tools for GitHub

Small, dependency-free scripts. Read them in one sitting.

| Project | What it does |
| --- | --- |
| 🧹 **[gh-repo-audit](https://github.com/rodolfochicone/gh-repo-audit)** | Finds forks you never touched, projects dead for years, and secrets you committed by accident. Prints the `gh` commands to clean it up — you decide what runs. I ran it on myself and deleted 77 repos. |
| 🏅 **[gh-achievements](https://github.com/rodolfochicone/gh-achievements)** | Computes which GitHub achievements you've already earned and prints the exact unlock criteria for the rest. |

---

## 🧪 Fullstack work

| Project | What it is |
| --- | --- |
| 🔴 **[pokemon-platform](https://github.com/rodolfochicone/pokemon-platform)** | Take-home turned reference project: NestJS + Next.js 15 + Drizzle in a Turborepo. JWT auth, PokéAPI integration, paginated search. |

---

## ⚡ What I'm doing now

- Shipping **rc-project** and using it as my daily driver — then fixing whatever breaks
- Building a **Rust + SvelteKit** SaaS for church music teams (repertoire and scheduling), live with real users
- Self-hosting everything on my own VPS behind **Caddy + Cloudflare** — no platform lock-in
- Writing about **agentic engineering**: what actually works when agents touch a real codebase

---

## 🤝 Let's connect

- 🌐 Website — [rodolfochicone.dev](https://rodolfochicone.dev)
- 📦 Code — [@rodolfochicone](https://github.com/rodolfochicone)

---

<sub>🇧🇷 Brasil · Local-first · Always shipping</sub>
