<div align="center">

**Developer who builds products, not just code**

Running a startup, shipping freelance systems, and contributing to open source

</div>

---

### Founder & CEO

<div align="center">

<img src="https://github.com/Jeong-Ryeol/Jeong-Ryeol/raw/main/bisit-icon.png" width="80" alt="Bisit"/>
<br/><br/>
<b>Bisit</b>
<br/>
O2O platform connecting people with on-demand services, anytime, anywhere
<br/><br/>
<code>Currently in operation</code>
<br/><br/>
Business registration, Toss PG, NTS API, Open Banking, SMS Auth
<br/><br/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>

</div>

---

### Featured Work

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

**Personal AI Knowledge Platform** `Freelance`

Full-stack knowledge infrastructure on a single NAS for a private client. Collects every Claude / GPT conversation, enriches it with LLMs, embeds it, and turns it into a searchable wiki, visual briefs, and a multi-engine agent console. Runs 24/7 on subscription tokens with zero per-call API cost.

- ~26k LOC · 323 automated tests · 8 containers
- Pipeline: scan → poll → enrich → embed → wiki → brief
- Claude + GPT side-by-side chat via Agent SDK / Codex SDK, event-sourced so any device resumes mid-stream
- MCP server so AI agents can search the archive
- Cloudflare Zero Trust tunnel, 0 open ports, app-side JWT re-check

Client package: **[claude-archive-client](https://github.com/Jeong-Ryeol/claude-archive-client)**

`Python` `FastAPI` `SvelteKit` `TypeScript` `PostgreSQL` `pgvector` `Docker` `MCP`

</td>
<td width="50%" valign="top">

**Medical Device Intel & Early-Warning Service** `Freelance`

Look up any medical device by its reimbursement code and get a full dossier in seconds: approvals, competitors, papers, clinical trials, FDA records, hospital pricing, videos, and an LLM overview. Exports to PDF.

- Reverse-engineered the national reimbursement code scheme to mirror 39k+ items locally, with change-feed diffing on every sync
- Parallel collection from 10+ public sources, streamed live over SSE
- 7-stage early-warning watch (patents → papers → trials → FDA → approvals → reimbursement → news) with Telegram alerts
- Shipped as a one-click exe, then integrated into the NAS stack behind Zero Trust

`Python` `FastAPI` `SQLite` `SSE` `Headless Chromium`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**SHERBET** `Product`

Commercial line of FiveM graphics tools sold to paying users via Discord.

- **[Custom ReShade fork](https://github.com/Jeong-Ryeol/reshade)**: rebuilt UI, 34 themes, multi-key hotkeys, Korean localization, preset market, node-locked licensing, silent auto-update
- **Hub**: mod manager with one-click install, mod-pack switching, original-file backup/restore
- Cache optimizer, thermal-vision color tool, graphics preset switcher
- Discord-role–gated auth + update server self-hosted on a home Ubuntu server

`C++` `DirectX` `ImGui` `Electron` `React` `Node.js`

</td>
<td width="50%" valign="top">

**[Always with chu](https://always-with-chu.com)** `Freelance`

VTuber fan site in production. Backend for a client-designed site: OTP admin auth, SOOP/YouTube API sync, self-hosted on Synology NAS.

`Node.js` `Express` `SQLite` `Docker`

<br/>

**[Lecture Q&A](https://github.com/Jeong-Ryeol/Data-Communications-Junseon-Kim)** `Freelance`

Anonymous live Q&A for university lectures. Upvotes, live polls, comprehension meter, AI moderation. No student identifiers stored.

`Next.js` `Firestore` `Gemini` `Vercel`

</td>
</tr>
</table>
</div>

---

### Open Source Contributions

<div align="center">
<table>
<tr>
<td align="center" width="50%" valign="top">
<a href="https://github.com/usestrix/strix">
<img src="https://img.shields.io/github/stars/usestrix/strix?style=for-the-badge&label=strix&labelColor=black&color=black&logo=github" alt="strix"/>
</a>
<br/><br/>
<a href="https://trendshift.io/repositories/15362" target="_blank"><img src="https://trendshift.io/api/badge/repositories/15362" alt="Trendshift" width="200"/></a>
<br/><br/>
<b>AI-powered penetration testing agent</b>
<br/><br/>
<a href="https://github.com/usestrix/strix/pull/157"><img src="https://img.shields.io/badge/PR_%23157-Merged-8957e5?style=flat-square&logo=github"/></a>
<br/>Unit tests for argument_parser
</td>
<td align="center" width="50%" valign="top">
<a href="https://github.com/unhappychoice/gitlogue">
<img src="https://img.shields.io/github/stars/unhappychoice/gitlogue?style=for-the-badge&label=gitlogue&labelColor=black&color=black&logo=github" alt="gitlogue"/>
</a>
<br/><br/>
<a href="https://terminaltrove.com/gitlogue/"><img src="https://cdn.terminaltrove.com/media/badges/tool_of_the_week/svg/terminal_trove_tool_of_the_week_green_on_black_bg.svg" height="48"/></a>
<br/><br/>
<b>Replay git commits like a movie</b>
<br/><br/>
<a href="https://github.com/unhappychoice/gitlogue/pull/117"><img src="https://img.shields.io/badge/PR_%23117-Merged-8957e5?style=flat-square&logo=github"/></a>
<br/>Per-file playback speed option
</td>
</tr>
</table>
</div>

---

### Tech Stack

<div align="center">

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
<br/>
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Svelte](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

### More Projects

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

**[ku-edu-chatbot](https://github.com/Jeong-Ryeol/ku-edu-chatbot)** `Solo`

AI admissions counselor for a graduate school, grounded on 2,300+ official Q&A answers via RAG.

`Next.js` `TypeScript` `Gemini` `RAG`

</td>
<td width="50%" valign="top">

**[AInote](https://github.com/Jeong-Ryeol/AInote)** `Solo`

Self-hosted Notion-style note app. Block editor, real-time collaboration, AI writing assist, RAG Q&A.

`Next.js` `Prisma` `pgvector` `BlockNote`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[raid-together](https://github.com/Jeong-Ryeol/raid-together)** `Solo`

Lost Ark raid party recruiting platform with Discord OAuth login. Live service.

`TypeScript` `Discord OAuth2`

</td>
<td width="50%" valign="top">

**[cryptominer-incident-response](https://github.com/Jeong-Ryeol/cryptominer-incident-response)** `Report`

Detected, contained, and remediated an XMR miner intrusion on my home server (unauthenticated Redis), plus a follow-up Next.js RCE incident.

`Incident Response` `Linux` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[BeautiFlow_BE](https://github.com/Jeong-Ryeol/BeautiFlow_BE)** `Team`

Salon booking backend. Booking API, customer management, custom group system.

`Spring Boot` `Redis` `WebSocket` `JPA`

</td>
<td width="50%" valign="top">

**[jpetstore-6](https://github.com/Jeong-Ryeol/jpetstore-6)** `Team`

LLM agent–based real-time recommendation system. User preference analysis via game simulation.

`Spring` `MyBatis` `Ollama` `LLM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[SibaServerMonitering](https://github.com/Jeong-Ryeol/SibaServerMonitering)** `Solo`

FiveM community scam record lookup. Blacklist management, real-time reports. Running on Oracle Cloud.

`Node.js` `Express` `MySQL` `PM2`

</td>
<td width="50%" valign="top">

**[ToolKitV](https://github.com/Jeong-Ryeol/ToolKitV)** `Solo`

FiveM texture optimization. Fixed 16MB streaming errors for 600+ skins.

`C#` `Texture Optimization`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[ASA-server-monitering](https://github.com/Jeong-Ryeol/ASA-server-monitering)** `Solo`

ARK: Survival Ascended server monitoring dashboard.

`Node.js` `JavaScript`

</td>
<td width="50%" valign="top">

**[Bitcoin-Price-Prediction](https://github.com/Jeong-Ryeol/Bitcoin-Price-Prediction-System)** `Solo`

Data mining–based price prediction. Random Forest, SVM comparison.

`Python` `scikit-learn` `WEKA`

</td>
</tr>
</table>
</div>
