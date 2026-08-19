<!-- ==================================================================== -->
<!--  SETUP                                                               -->
<!--  1. Repo name must equal your username:  usman-naeem-dev            -->
<!--  2. Save as README.md in that repo                                  -->
<!--  3. See "RELIABILITY" note at the bottom re: the stats cards        -->
<!-- ==================================================================== -->

<h1 align="center">Muhammad Usman</h1>

<p align="center">
  <b>Full-Stack Engineer</b> &nbsp;·&nbsp; MERN / Next.js &nbsp;·&nbsp; Voice AI Lead
</p>

<p align="center">
  <a href="https://usman-next-folio.vercel.app">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/usmannaeem">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:usmannaeem52666@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-3%2B%20years-0d1117?style=flat-square&labelColor=0d1117&color=00b894"/>
  <img src="https://img.shields.io/badge/Based%20in-Lahore,%20PK%20(GMT%2B5)-0d1117?style=flat-square&labelColor=0d1117&color=0984e3"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20roles-0d1117?style=flat-square&labelColor=0d1117&color=6c5ce7"/>
</p>

---

I build and operate production web systems end to end — schema design, REST APIs, auth, deployment, and 24/7 production ops. For the past two years I've led **voice AI** engineering at [VohoAI](https://linkedin.com/in/usmannaeem), taking every agent the company ships from prototype to live enterprise traffic across Saudi Arabia, Germany, and the wider GCC.

Most of my work sits where **realtime systems, LLM infrastructure, and multi-tenant SaaS** meet — the parts that have to stay up, stay fast, and stay correct across tenants and languages.

<br/>

## Selected Impact

| | |
|---|---|
| **< 800 ms** | End-to-end voice response latency — Deepgram → LLM → ElevenLabs pipelines on LiveKit / Pipecat with custom VAD tuning and barge-in handling |
| **169 endpoints** | REST API surface across 20 collections on the SAMINA multi-tenant booking & POS platform (NestJS / MongoDB) |
| **4 languages** | Production voice agents in Arabic (Najdi), English, German, and Urdu, with per-language tool routing to eliminate code-switching failures |
| **30K+ tokens** | Per-session cost reduction on the Miku booking agent via v2 state-machine prompt architecture and slot-validation caching |
| **24/7** | Production uptime ownership — GCP infrastructure via Coolify, PM2, Nginx, Certbot, and self-hosted GitHub Actions runners |

<br/>

## Focus Areas

**Voice AI & LLM Infrastructure**
Low-latency realtime pipelines on LiveKit and Pipecat. Multilingual agent design, prompt architecture, RAG, and tool routing. Retell AI, VAPI, Twilio SIP, Deepgram, ElevenLabs, GPT-4o, Gemini, Claude.

**Multi-Tenant SaaS & Platform Engineering**
White-label platforms with tenant isolation, usage-based Stripe billing, and role-based access. Next.js / React front-ends over NestJS or Express APIs, documented with Swagger/OpenAPI.

**Systems Integration**
Wiring products into enterprise and legacy estates — SAP PI/PO, on-prem Java/WebLogic, GoHighLevel CRM, Twilio SIP — handling auth, retries, and idempotency end to end.

**Web3**
NFT / digital-asset marketplace with on-chain interactions and wallet integration (MetaMask, ethers.js), plus a digital-asset custody SaaS with role-based admin.

<br/>

## Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,nestjs,express,mongodb,postgres,redis,supabase,tailwind,redux&perline=12" alt="core stack"/>
</p>
<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,laravel,flutter,dart,docker,gcp,azure,nginx,githubactions,git,vercel&perline=12" alt="secondary stack"/>
</p>

<details>
<summary><b>Full breakdown</b></summary>

<br/>

**Frontend** — React 18, Next.js 14, TypeScript, Redux Toolkit, TanStack Query, React Hook Form + Zod, Tailwind, Radix UI, Material UI, shadcn/ui, Vue.js, Astro

**Backend** — Node.js, Express, NestJS, REST APIs, Swagger/OpenAPI, JWT / Passport, WebSockets (Socket.io), Python (FastAPI / Flask), Laravel

**Databases** — MongoDB (Atlas / Mongoose), PostgreSQL / Supabase, MySQL, Redis

**Cloud & DevOps** — GCP (Compute Engine, Cloud Storage), Azure, Docker, PM2, Nginx, Coolify, Sentry, GitHub Actions CI/CD

**Mobile** — Flutter, Dart, Provider, go_router, Dio + Retrofit, Hive, Google ML Kit — shipped to Google Play and the App Store

**Voice AI & LLMs** — LiveKit Agents SDK, Pipecat, Retell AI, VAPI, Twilio SIP, Deepgram, ElevenLabs, Whisper, GPT-4o, Gemini 2.5 Pro, Claude

**Automation** — n8n, GoHighLevel, RAG pipelines

</details>

<br/>

## Experience

**Full-Stack Software Engineer — Voice AI Lead** · VohoAI · Berlin (Remote) · *Nov 2024 – Aug 2026*
Lead developer on every voice agent shipped by the company. Led the white-label multi-tenant SaaS platform — Next.js front-end, Supabase/Postgres backend, Stripe usage billing — positioned against Retell and VAPI. Owned architecture decisions, prompt design, and production rollouts for enterprise engagements, and mentored junior engineers across LiveKit, Pipecat, n8n, and Next.js/Supabase.

**Freelance Full-Stack Developer** · Upwork & Local Clients · *Apr 2024 – Nov 2024*
Delivered full-stack applications for international and local clients — Next.js/React front-ends, Node/Express and Laravel back-ends, responsive dashboards, REST APIs, and payment/CRM/email integrations. Owned each project from scoping through deployment and post-launch support.

**MERN Stack / Laravel Developer** · Amco IT Systems Inc. · Lahore · *Mar 2023 – Apr 2024*
Built a Web3 NFT / digital-asset marketplace with on-chain interactions and wallet integration, a SaaS custody platform with role-based access control, and Stripe-powered fundraising platforms with live progress tracking.

<br/>

## Selected Work

**SAMINA — Multi-Tenant Booking & POS Platform** · `NestJS · React 18 · Flutter`
Production platform for a sleep-health retail chain across Austria and Germany. Contributed across all three codebases as part of a small team. Owned the integration layer syncing customers, orders, appointments, health data, and catalogs from the legacy Remedi system, plus Scaneca body-scan ingestion to Google Cloud Storage. Implemented timezone-correct scheduling with per-service durations, per-resource capacity, branch hours, and blocked ranges. Delivered digital health-intake with signature capture and PDF generation, QR check-in via Google ML Kit, a Mailgun campaign module, and German localisation.

> Diagnosed and resolved a production CI incident where duplicate self-hosted GitHub Actions runners on an orphaned VM were silently absorbing ~50% of deployments.

**Miku — Outbound Booking Voice Agent** · `Retell AI · n8n · GoHighLevel`
German-language outbound booking agent with Node.js middleware and calendar API integration. Authored the v2 state-machine prompt architecture, cutting per-session token spend by 30K+.

**Smart-Buildings & Fleet-Master** · `MERN`
CRM dashboards for building and fleet management with map views, live status tracking, and role-based admin.

<sub><a href="https://usman-next-folio.vercel.app">More on the portfolio →</a></sub>

<br/>

## Beyond Work

Engineering contributor to **AI Vibe Club**, an AI builders community covering voice AI, n8n automation, and the AI Consultant Pathway curriculum. I also build and maintain technical content — scripts, demos, and graphics — on modern AI tooling and agentic coding workflows.

<br/>

## Education

**BS in Business & Information Technology** — Virtual University of Pakistan *(ongoing)*
**Full-Stack Web Development** — PNY Trainings, Lahore *(2022–2023)*

<br/>

---

<details>
<summary><sub>GitHub activity</sub></summary>

<br/>

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=usman-naeem-dev&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00b894&icon_color=0984e3&text_color=c9d1d9&cache_seconds=86400"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=usman-naeem-dev&layout=compact&hide_border=true&bg_color=0d1117&title_color=00b894&text_color=c9d1d9&langs_count=8&cache_seconds=86400"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=usman-naeem-dev&hide_border=true&background=0d1117&stroke=30363d&ring=00b894&fire=0984e3&currStreakLabel=00b894&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9"/>
</p>

</details>

<!-- ==================================================================== -->
<!--  RELIABILITY NOTE                                                     -->
<!--                                                                       -->
<!--  The two stats cards use the SHARED public instance at                -->
<!--  github-readme-stats.vercel.app, which is used by thousands of        -->
<!--  people and regularly hits GitHub's API rate limit. When that         -->
<!--  happens the images render as broken — nothing is wrong with your     -->
<!--  markdown.                                                            -->
<!--                                                                       -->
<!--  To make them reliable, deploy your own instance (10 min, free):      -->
<!--    1. Fork  https://github.com/anuraghazra/github-readme-stats        -->
<!--    2. Create a GitHub Personal Access Token (no scopes needed)        -->
<!--    3. Import the fork into Vercel                                     -->
<!--    4. Add env var  PAT_1  = your token                                -->
<!--    5. Deploy, then replace "github-readme-stats.vercel.app" above     -->
<!--       with your own <project>.vercel.app domain                       -->
<!--                                                                       -->
<!--  Streak card uses streak-stats.demolab.com (the current official      -->
<!--  domain). It has occasional downtime too and can be self-hosted the   -->
<!--  same way from DenverCoder1/github-readme-streak-stats.               -->
<!-- ==================================================================== -->
