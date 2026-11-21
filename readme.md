<!-- ═══════════════════════  HEADER  ═══════════════════════ -->
<div align="center">

<img src="./assets/header.svg" width="100%" alt="Tarunya Yadav — Full-Stack & AI Engineer"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=A78BFA&center=true&vCenter=true&width=720&lines=Founding+Engineer+Intern+%40+Wildcard+AI+(YC+W25);Building+agentic+dev+tools+%26+MCP+servers;Fault-tolerant+queues%2C+pipelines+%26+state+machines;TypeScript+%E2%80%A2+Python+%E2%80%A2+Multi-LLM+systems" alt="Typing SVG" />
</a>

<br/>

<a href="mailto:tarunya.7470@gmail.com"><img src="https://img.shields.io/badge/Email-tarunya.7470%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/tarunyayadav"><img src="https://img.shields.io/badge/LinkedIn-tarunyayadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://tarunyayadav.netlify.app"><img src="https://img.shields.io/badge/Portfolio-Visit-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Tarunya0704&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS" />

</div>

<br/>

<!-- ═══════════════════════  ABOUT  ═══════════════════════ -->
## ⚡ whoami

```ts
const tarunya = {
  role:        "Full-Stack & AI Engineer",
  currently:   "Founding Engineer Intern @ Wildcard AI (YC W25)",
  previously:  ["Full Stack AI Engineer @ Vryse Tech", "Full Stack Dev @ Datalab Consulting (Fintech)"],
  education:   "B.Tech CSE @ Bennett University ('27)",
  focus:       ["Agentic AI", "MCP servers", "Distributed systems", "Durable job pipelines"],
  shipping:    "400+ commits into a production TypeScript monorepo in my first months at a YC startup",
  funFact:     "I write retry logic for my retry logic 🔁",
};
```

- 🤖 I build **agentic developer tools** — systems where LLMs actually *do* things: browse, diff, deploy, ship.
- 🏗️ I care about the boring-but-critical parts: **idempotency, dead-letter queues, checkpointing, backoff**.
- 🌍 Spent the last year deep in **GEO (Generative Engine Optimization)** — how ChatGPT, Claude, Gemini & Perplexity answer real user prompts.
- 🚀 Selected for **Round 1 of Entrepreneur First** · 🔥 **100-day LeetCode streak**

<br/>

<!-- ═══════════════════════  EXPERIENCE  ═══════════════════════ -->
## 💼 Where I've Shipped

<table>
<tr>
<td width="33%" valign="top">

### 🟣 Wildcard AI
**Founding Engineer Intern** · YC W25
<sub>Aug 2026 – Present · Remote</sub>

- **400+ commits** · 21 epics · 1,146 files · +41K LOC
- GEO analytics platform simulating how 4 major AI assistants answer shopping prompts
- **BullMQ** queues with idempotent processors + dead-letter handling
- Headless-browser automation pipeline hardened against **20+ failure modes**
- AI blog assistant with **SSE streaming**

<sub>`Fastify` `React` `Prisma` `PostgreSQL` `BullMQ`</sub>

</td>
<td width="33%" valign="top">

### 🔵 Vryse Tech
**Full Stack AI Engineer**
<sub>Nov 2025 – Aug 2026 · Pune</sub>

- GEO/SEO SaaS serving **35+ enterprise clients**
- AI Overview analysis at **1,000+ prompts/client**
- Migrated **55K+ records** (37 Firestore collections → Neon Postgres)
- Re-architected serverless pipeline into **durable Trigger.dev tasks** — zero timeout failures across 200+ runs

<sub>`Next.js` `Node.js` `Neon` `Trigger.dev`</sub>

</td>
<td width="33%" valign="top">

### 🟢 Datalab Consulting
**Full Stack Developer** · Fintech
<sub>Jul 2025 – Aug 2025 · Remote</sub>

- Trading platform for **500+ concurrent users**
- **25+ REST APIs** on AWS — 99.9% uptime, sub-200ms
- NestJS / PostgreSQL microservices
- Discord bot exporting **10K+ records** with RBAC

<sub>`React` `NestJS` `PostgreSQL` `AWS`</sub>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════  PROJECTS  ═══════════════════════ -->
## 🚀 Featured Builds

<table>
<tr>
<td width="50%" valign="top">

### 👁️ ShiroDiff
**Visual Regression Agent** · *Live on GitHub Marketplace*

A self-hosted GitHub App that catches UI regressions on **every pull request**.

- Runs base & head builds in parallel, screenshots routes with **Playwright**
- Weighted composite score from **pixelmatch + SSIM + pixel similarity** with Lanczos3 normalization
- Framework-aware route detection for **Next.js, Remix, SvelteKit, Nuxt**
- Per-route error isolation + exponential-backoff retries

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Probot-00B0D8?style=flat-square&logo=probot&logoColor=white"/> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>

</td>
<td width="50%" valign="top">

### ☄️ GodComet
**Figma → Production Agent**

Drop in a Figma design, get back a **deployed, GitHub-hosted website** — end to end.

- **7-stage pipeline** driven by a 12-state workflow state machine
- Python **MCP server with 14+ tools** — Playwright, Figma, GitHub, Vercel, Jira, AWS
- **Multi-LLM routing** across Claude, Llama 4 & GPT-4o with retries + caching
- Electron desktop shell

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white"/>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════  STACK  ═══════════════════════ -->
## 🧰 Tech Arsenal

<details open>
<summary><b>Languages</b></summary>
<br/>
<img src="https://skillicons.dev/icons?i=ts,js,python,java,cpp,php,html,css&perline=12" />
</details>

<details open>
<summary><b>Frameworks & Runtime</b></summary>
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,nestjs,express,redux,tailwind,vite,electron,prisma&perline=12" />
</details>

<details open>
<summary><b>Data, Queues & Infra</b></summary>
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,firebase,sqlite,docker,aws,vercel,githubactions,git&perline=12" />
</details>

<details open>
<summary><b>AI / LLM Toolkit</b></summary>
<br/>

<img src="https://img.shields.io/badge/Anthropic_Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini_%2F_Vertex-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Perplexity-1FB8CD?style=for-the-badge&logo=perplexity&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel_AI_SDK-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Whisper-74AA9C?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
<img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white"/>

</details>

<br/>

<!-- ═══════════════════════  STATS  ═══════════════════════ -->
## 📊 GitHub Pulse

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Tarunya0704&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tarunya0704&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa" height="170" />

<img src="https://streak-stats.demolab.com/?user=Tarunya0704&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=f472b6&currStreakLabel=a78bfa" height="170" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Tarunya0704&bg_color=0d1117&color=a78bfa&line=7c3aed&point=f472b6&area=true&area_color=7c3aed&hide_border=true" width="100%" />

</div>

<br/>

<!-- ═══════════════════════  SNAKE  ═══════════════════════ -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tarunya0704/Tarunya0704/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Tarunya0704/Tarunya0704/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Tarunya0704/Tarunya0704/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<br/>

<!-- ═══════════════════════  FOOTER  ═══════════════════════ -->
<div align="center">

### 🤝 Let's build something

Open to conversations about **agentic AI, dev tooling, and backend systems that don't fall over**.

<a href="mailto:tarunya.7470@gmail.com"><img src="https://img.shields.io/badge/Say_Hi-7c3aed?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="./assets/footer.svg" width="100%"/>

</div>
