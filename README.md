<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:00D9FF,100:7C3AED&height=200&section=header&text=PIYUSH%20AGARWAL&fontSize=54&fontColor=FFFFFF&fontAlignY=34&desc=I%20build%20the%20harness,%20not%20just%20the%20agent&descAlignY=54&descSize=18&animation=fadeIn" alt="Piyush Agarwal" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=900&color=00D9FF&center=true&vCenter=true&width=940&lines=Most+people+ship+a+prompt+and+hope.;I+ship+the+layer+that+catches+the+model+being+wrong.;Self-hosted+MCP+servers+across+4+projects;LLM-as-judge+eval+harnesses+gated+in+CI;Guardrails+enforced+outside+the+model,+not+in+a+prompt;Real-time+voice+agents+at+sub-second+latency;0+to+1000%2B+users,+shipped+solo" alt="Typing animation" />

<br />

<a href="https://practers.com/"><img src="https://img.shields.io/badge/Practers-1000%2B_users_live-00D9FF?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://portfolio-of-piyush.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="mailto:piyushaga2005@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/piyush-agarwal-284988332"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<br /><br />

<img src="https://img.shields.io/badge/MCP_servers-4_projects,_self--hosted-0F172A?style=flat-square&labelColor=00D9FF&color=0F172A" />
<img src="https://img.shields.io/badge/Eval_harnesses-gated_in_CI-0F172A?style=flat-square&labelColor=00D9FF&color=0F172A" />
<img src="https://img.shields.io/badge/Voice_latency-sub--second-0F172A?style=flat-square&labelColor=00D9FF&color=0F172A" />
<img src="https://img.shields.io/badge/Codeforces-1872_Knight-0F172A?style=flat-square&labelColor=7C3AED&color=0F172A" />
<img src="https://img.shields.io/badge/DSA-740%2B_solved-0F172A?style=flat-square&labelColor=7C3AED&color=0F172A" />

</div>

---

## The 30 second version

> **The agent does not have taste. Either I do, or nobody on that surface does.**

I am a **pre-final year CS student** who has already taken a product from **zero to 1000+ users** and built the tooling underneath it. I do not write prompts and hope. I build **the harness that catches an agent being confidently wrong**, because on every surface I own, that is what decides whether it ships or embarrasses me.

I **run several plans in parallel** with Claude Code, custom skills and parallel subagents, and I have **opinions about which model gets which job**. I have shipped agents that **spend real money unsupervised**, which is a fast way to learn exactly where these systems fail and to build the habit of catching it.

<table>
<tr>
<td width="33%" align="center">
<h3>Built the tooling</h3>
<b>Self-hosted MCP servers</b><br />
<b>LLM-as-judge harnesses</b><br />
<b>Policy-as-code guardrails</b><br />
<sub>Not autocomplete. Infrastructure.</sub>
</td>
<td width="33%" align="center">
<h3>Shipped solo</h3>
<b>0 to 1000+ users</b><br />
<b>1000+ live sessions</b><br />
<b>Backend, frontend, infra, 3am pages</b><br />
<sub>Nobody handed me a ticket.</sub>
</td>
<td width="33%" align="center">
<h3>Real-time and money</h3>
<b>Sub-second voice over WebSockets</b><br />
<b>Agents that spend real money</b><br />
<b>Prediction markets, OT collaboration</b><br />
<sub>Where being wrong actually costs.</sub>
</td>
</tr>
</table>

---

## Agent tooling, the part most people skip

<div align="center">
<b>Anyone can get a demo working. The hard part is knowing in ten seconds that an agent has confidently produced garbage.</b><br />
<sub>Here is what I built so I would know.</sub>
</div>

<br />

<table>
<tr>
<td width="50%" valign="top">

### Self-hosted MCP servers

**LaunchOps** exposes **13 tools over a self-hosted MCP server** that let an agent provision live cloud infrastructure, databases, hosting and domains.

**FlowForge** runs its own MCP server exposing a **node-based workflow engine as an agent-callable tool**.

MCP integrations across **4 separate projects**, HTTP and Stdio transports.

</td>
<td width="50%" valign="top">

### LLM-as-judge eval harnesses

Every Practers interview is scored by **parallel specialised judge models** covering correctness, problem solving, code quality and communication, combined by an **orchestrator** into a rubric-grounded verdict.

Judge-to-human agreement is **measured on a golden set**. Where judges disagree with each other, the case **auto-escalates to a human** instead of being silently scored. The whole suite runs **in CI, so a bad prompt change fails the build like a unit test**.

**Pounce** runs a second judge harness on Groq against recorded agent runs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Guardrails enforced outside the model

In **Pounce**, an agent completes real purchases with **nobody watching when money moves**. So the spending cap does not sit in my code or in a prompt. It sits **inside the payment mandate, where the bank enforces it**. A fully compromised agent still cannot exceed it.

Deterministic state machine with the **model advisory only**, idempotency keys on every attempt, advisory locks so two triggers cannot double-fire, signature-verified webhooks, and a **replayable audit trail** of every decision.

**LaunchOps** adds **policy-as-code**: a scope, budget and approval engine, a dry-run mode, and a ledger.

</td>
<td width="50%" valign="top">

### How I actually work

I run **several plans in parallel** with Claude Code, custom skills and parallel subagents, and I **route work by which model is genuinely good at it** rather than by habit.

I write **CI guard scripts that fail a build on policy violations**, not just on failing tests. One of mine fails the build if a credential identifier appears **anywhere outside the single module allowed to hold it**.

The rule I work by: **the model advises, deterministic code decides.**

</td>
</tr>
</table>

---

## Shipped, with real people using it

<table>
<tr>
<td width="60%" valign="top">

### [Practers](https://practers.com/) &nbsp; <img src="https://img.shields.io/badge/live-1000%2B_users-00D9FF?style=flat-square" />

A **real-time AI interviewer**. It holds a live voice conversation at **sub-second latency over WebSockets** and **adapts its questions to the candidate's own resume** mid-interview.

Taken **0 to 1000+ users across 1000+ sessions**, with live health monitoring. Turborepo monorepo, secure coding rounds on Judge0, contest infra, ATS analysis, OA proctoring.

The hard part was never the interview. It was making the **score defensible**, which is where the judge harness came from.

**Stack** Next.js 16, React 19, Fastify 5, Prisma, Supabase, PostgreSQL, MongoDB, Redis, BullMQ, Socket.IO, Judge0
**Infra** Google Cloud Run, Docker, Cloud Build, Cloudflare R2, Razorpay, Resend, MSG91

</td>
<td width="40%" valign="top">

### Contribution proof

Verified from the private **mockr-labs/practers** repository insights.

**#2** contributor by commits
**210,311** lines added, the **highest of any contributor** on the team
**105** commits to main
**92,608** additions in a single peak week

<img src="images/image4.png" alt="Practers contributor leaderboard showing 105 commits and 210,311 additions" width="100%" />

</td>
</tr>
</table>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Pounce](https://github.com/piyushagarwal-55/teampounce) &nbsp; <img src="https://img.shields.io/badge/agents_that-spend_real_money-7C3AED?style=flat-square" />

**5 role-bounded LLM agents** running through a **tool-calling harness on Groq**, transacting with live merchants over **MCP and Shopify UCP**, grounding every pick on a **Senso RAG context layer**.

The **autonomous mandate agent** arms a **capped, time-bound authorization once**, then buys on its own **on a price drop**, with nobody watching when the money moves.

**Why it matters:** I shipped an **LLM-as-judge eval harness scoring every tool call on real merchant data**, specifically to catch **confident-wrong actions before checkout**. The cap itself lives outside the model, so a compromised agent still cannot exceed it.

**Stack** OpenAI gpt-4o, MCP / Shopify UCP, Prava, Senso (RAG), Next.js, TypeScript, WebSockets

[Live](https://teampounce.vercel.app) · [Code](https://github.com/piyushagarwal-55/teampounce)

</td>
<td width="50%" valign="top">

### [LaunchOps](https://github.com/piyushagarwal-55/launchops-hackathon) &nbsp; <img src="https://img.shields.io/badge/built_in-a_weekend-00D9FF?style=flat-square" />

An agent that **provisions live cloud resources**, exposed as **13 tools over a self-hosted MCP server**.

**Why it is interesting:** **policy-as-code** with a scope, budget and approval engine plus a dry-run mode, so an agent cannot exceed granted authority.

**Stack** Next.js, TypeScript, MCP (HTTP and Stdio), Socket.io, Node.js

[Live](https://launchops-hackathon.vercel.app) · [Code](https://github.com/piyushagarwal-55/launchops-hackathon)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [FlowForge](https://github.com/piyushagarwal-55/flowforge)

**Natural language specs compiled into deployable REST APIs** through an LLM tool-calling pipeline, with a node-based workflow engine exposed as an agent-callable tool over its own MCP server.

**Stack** Next.js, TypeScript, Node.js, MCP, LLM tool-calling

[Live](https://flowforge-i871.vercel.app) · [Demo](https://youtu.be/VcgeOuzxbdg) · [Code](https://github.com/piyushagarwal-55/flowforge)

</td>
<td width="50%" valign="top">

### [Sheet AI Pro](https://github.com/piyushagarwal-55/sheet-ai-pro) &nbsp; <img src="https://img.shields.io/badge/real--time-multi--user-00D9FF?style=flat-square" />

Real-time collaborative spreadsheet with **Operational Transformation over WebSockets**, persistent multi-user state and reconnect-safe synchronisation.

**Proof** under **100ms recalculation across 2,500+ cells**

[Code](https://github.com/piyushagarwal-55/sheet-ai-pro)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Prediction Market](https://pridiction-market-frontend-nfrj.vercel.app/) &nbsp; <img src="https://img.shields.io/badge/risk-%26_markets-7C3AED?style=flat-square" />

A **prediction market** where positions are priced by what people actually believe, not by what they say. Building it is the fastest way to learn that **a probability only means something when someone has money on it**.

[Live](https://pridiction-market-frontend-nfrj.vercel.app/)

<!-- SWAPPR: send me these four things and I will write this card properly.
     1. one line on what it does
     2. Swift or React Native
     3. App Store link
     4. any user or download number
     They list "shipped something to the App Store yourself, at any scale" as a brownie point,
     so this is worth getting right rather than guessing.
-->



</td>
<td width="50%" valign="top">

### [ShopSage](https://github.com/piyushagarwal-55/hackathon-we-make-devs)

AI shopping assistant on **AWS Bedrock and Llama 3** for search, recommendations, personalisation, budget flows and generative UI.

[Live](https://hackathon-we-make-devs.vercel.app/) · [Demo](https://youtu.be/2icL9ZYp3SY)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexus Flow](https://nexusflowbeta.vercel.app/)

Built on **SKALE Network**. [Live](https://nexusflowbeta.vercel.app/) · [Demo](https://youtu.be/S1DNJXRR7LI)

</td>
<td width="50%" valign="top">

### [RepVote](https://repvote-v1.vercel.app/) &nbsp; and &nbsp; [LNMIIT Carpool](https://github.com/piyushagarwal-55/carpool-lnmiit-work)

Reputation-weighted voting, and a carpool app used on my own campus.

</td>
</tr>
</table>

---

## Experience

<table>
<tr>
<td width="50%" valign="top">

### Practers &nbsp;|&nbsp; Co-Founder and Founding Engineer
<sub>Apr 2026 to Present</sub>

Led architecture for an **AI-native interview and hiring platform** as a Turborepo monorepo.

Built **resume-aware AI mock interviews** with authenticated WebSockets, Groq voice and text sessions, Gemini and OpenAI integrations, stage orchestration, code and canvas snapshots, and **rubric-scored reports**.

Built secure coding, contest and hiring modules on Judge0 with Redis and BullMQ queues, hidden tests, real-time verdicts, ATS resume analysis and OA proctoring.

Deployed on **Google Cloud Run** with Docker, Secret Manager, R2-style storage, Razorpay, Resend and MSG91.

</td>
<td width="50%" valign="top">

### Swyft Ventures &nbsp;|&nbsp; SDE 1 Intern
<sub>Jan 2026 to Jun 2026 · Gemini-focused startup · Remote</sub>

Designed and shipped a **real-time swipe-based matching engine** where mutual opt-ins **instantly create matches**, backed by **Supabase row-level security** and live **Expo push on React Native**.

Shipped **high-quality releases** with automated unit and integration tests in a **GitHub Actions CI/CD pipeline**, plus real-time monitoring and error tracking for production reliability.

**React Native (Expo), Supabase, PostgreSQL, Prisma, Express, WebSockets, Jest/Vitest, GitHub Actions**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### A1 Selectors &nbsp;|&nbsp; Software Developer Intern
<sub>Aug 2025 to Dec 2025</sub>

Built scalable REST APIs for **automated resume parsing** using NLP-based extraction, **cutting manual screening effort by 35 percent** across recruiter workflows.

Developed AI recruitment workflows for candidate matching, ranking, scheduling automation, filtering and recruiter decision support.

</td>
<td width="50%" valign="top">

### Teaching Assistant &nbsp;|&nbsp; LNMIIT
<sub>Ongoing</sub>

Mentored students across **two semesters**, communicating complex ideas and presenting solutions in labs.

**B.Tech Communication and Computer Engineering**, CGPA **7.52**, Aug 2024 to Aug 2028.

</td>
</tr>
</table>

---

## Open source

<div align="center">

| Project | What I did | Why it counts |
|---|---|---|
| **[Zulip](https://github.com/zulip/zulip)** <sub>GSoC org</sub> | Merged PR migrating banners to a **shared component** across their large-scale Django codebase | Code other engineers actually use, in a repo I did not control |
| **AOSSIE** <sub>GSoC org</sub> | Diagnosed and fixed a **governance-audit bug** in OrgExplorer | It was **inflating dashboard metrics by up to 12x** |

</div>

---

## Competitive

<div align="center">

<table>
<tr>
<td align="center" width="25%"><h3>LeetCode</h3><h2>450+</h2><sub>solved</sub></td>
<td align="center" width="25%"><h3>Codeforces</h3><h2>1872</h2><sub>Knight, 220+ solved</sub></td>
<td align="center" width="25%"><h3>GeeksforGeeks</h3><h2>200+</h2><sub>solved</sub></td>
<td align="center" width="25%"><h3>Hackathons</h3><h2>Top 1%</h2><sub>Google Big Code 2026, AWS ML</sub></td>
</tr>
</table>

<sub><b>Google Big Code Hackathon 2026</b>: top 1% after three national elimination rounds. <b>Teaching Assistant</b> at LNMIIT.</sub>

</div>

---

## Stack

<div align="center">

**AI and agents** &nbsp; MCP · eval harnesses · LLM-as-judge · agentic workflows · RAG · prompt evaluation · tool-calling

<img src="https://skillicons.dev/icons?i=ts,js,python,cpp,c,nodejs,nextjs,react,tailwind,fastapi,express,postgres,mongodb,redis,supabase,prisma,docker,gcp,aws,git,githubactions,vercel" alt="Stack" />

</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=piyushagarwal-55&show_icons=true&theme=react&hide_border=true&bg_color=0F172A&title_color=00D9FF&icon_color=7C3AED&text_color=FFFFFF" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=piyushagarwal-55&theme=react&hide_border=true&background=0F172A&ring=00D9FF&fire=7C3AED&currStreakLabel=00D9FF" height="165" />

<img src="https://raw.githubusercontent.com/piyushagarwal-55/piyushagarwal-55/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="100%" />

<br />

### If you are hiring someone to own a surface end to end, I am the one you point at when it breaks.

<a href="mailto:piyushaga2005@gmail.com"><img src="https://img.shields.io/badge/piyushaga2005@gmail.com-Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://practers.com/"><img src="https://img.shields.io/badge/See_it_running-practers.com-00D9FF?style=for-the-badge&logo=vercel&logoColor=white" /></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:00D9FF,100:0F172A&height=120&section=footer" alt="" />
