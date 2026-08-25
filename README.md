<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:00D9FF,100:7C3AED&height=200&section=header&text=PIYUSH%20AGARWAL&fontSize=54&fontColor=FFFFFF&fontAlignY=34&desc=I%20build%20the%20harness,%20not%20just%20the%20agent&descAlignY=54&descSize=18&animation=fadeIn" alt="Piyush Agarwal" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=900&color=00D9FF&center=true&vCenter=true&width=940&lines=Most+people+ship+a+prompt+and+hope.;I+ship+the+layer+that+catches+the+agent+being+wrong.;5+role-bounded+agents+that+spend+real+money;Self-hosted+MCP+servers+across+4+projects;LLM-as-judge+harnesses+gated+in+CI;Sub-second+voice.+0+to+1000%2B+users.+Shipped+solo." alt="Typing animation" />

<br />

<a href="https://practers.com/"><img src="https://img.shields.io/badge/Practers-1000%2B_users_live-00D9FF?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://portfolio-of-piyush.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="mailto:piyushaga2005@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/piyush-agarwal-284988332"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

</div>

---

## The 30 second version

<div align="center">

### The agent does not have taste. Either I do, or nobody on that surface does.

</div>

Pre-final year CS student. Already took a product from **zero to 1000+ users** and built the tooling underneath it.

I do not write prompts and hope.

I build **the harness that catches an agent being confidently wrong**, because that is what decides whether a surface ships or embarrasses me.

I run **several plans in parallel** with Claude Code, custom skills and parallel subagents.

I have opinions about **which model gets which job**, and I did not get them from a blog post.

I ship agents that **spend real money unsupervised**, and agents that **act on their own without being asked**. That is a fast way to learn exactly where these systems fail, and to build the habit of catching it.

On mobile I ship **React Native and Expo to production**, with **live push** and **row-level security**, in a **CI/CD pipeline with automated tests**.

<div align="center">

<img src="https://img.shields.io/badge/0_%E2%86%92_1000%2B_users-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/shipped_solo-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/sub--second_voice-00D9FF?style=for-the-badge" /> <img src="https://img.shields.io/badge/4_MCP_servers-00D9FF?style=for-the-badge" /> <img src="https://img.shields.io/badge/parallel_agent_plans-F59E0B?style=for-the-badge" /> <img src="https://img.shields.io/badge/agents_that_move_money-F59E0B?style=for-the-badge" /> <img src="https://img.shields.io/badge/evals_gated_in_CI-F59E0B?style=for-the-badge" />

</div>

---

## Agent tooling, the part most people skip

<div align="center">

**Anyone can get a demo working.**
**The hard part is knowing in ten seconds that an agent has confidently produced garbage.**

<sub>Here is what I built so that I would know.</sub>

</div>

### Self-hosted MCP servers

- **LaunchOps** exposes **13 tools** over a self-hosted MCP server, which an agent uses to provision live cloud infrastructure, databases, hosting and domains.
- **FlowForge** runs its own MCP server, exposing a node-based workflow engine as an **agent-callable tool**.
- MCP integrations across **4 separate projects**, over both HTTP and Stdio transports.

<img src="https://img.shields.io/badge/13_tools-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/4_projects-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/HTTP_%2B_Stdio-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/agent--callable_tools-00D9FF?style=flat-square" />

### LLM-as-judge eval harnesses

- Every Practers interview is scored by **parallel specialised judge models**, combined by an orchestrator into a **rubric-grounded verdict**.
- Judge-to-human agreement is **measured on a golden set**, and where judges disagree the case **auto-escalates to a human** instead of being silently scored.
- The whole suite runs **in CI, so a bad prompt change fails the build** exactly like a unit test.

<img src="https://img.shields.io/badge/golden_set-7C3AED?style=flat-square" /> <img src="https://img.shields.io/badge/measured_agreement-7C3AED?style=flat-square" /> <img src="https://img.shields.io/badge/auto--escalates-7C3AED?style=flat-square" /> <img src="https://img.shields.io/badge/fails_the_build-7C3AED?style=flat-square" />

### Guardrails enforced outside the model

- In **Pounce** an agent completes real purchases with **nobody watching when money moves**, so the cap sits **inside the payment mandate where the bank enforces it**, not in my code and not in a prompt. A fully compromised agent still cannot exceed it.
- Deterministic state machine with the **model advisory only**, plus idempotency keys on every attempt, advisory locks so two triggers cannot double-fire, and signature-verified webhooks.
- A **replayable audit trail** of every decision, so any action can be reconstructed with the state that caused it.

<img src="https://img.shields.io/badge/bank--enforced_cap-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/model_advisory_only-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/idempotency_%2B_locks-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/replayable_trail-F59E0B?style=flat-square" />

### Proactive agents, not request-response bots

- **Pounce's mandate agent** runs as a **long-lived watcher**. It holds state across days and **acts on its own** the moment a price drops.
- The hard part was never the acting, it was the **arming**: a **capped, time-bound authorization** granted once, so a watcher that fires unattended at 3am **cannot do damage**.
- That is the shape of any proactive system. Something is always running, and the real question is what it is allowed to do **when nobody is looking**.

<img src="https://img.shields.io/badge/long--lived_watcher-EC4899?style=flat-square" /> <img src="https://img.shields.io/badge/acts_unprompted-EC4899?style=flat-square" /> <img src="https://img.shields.io/badge/time--bound_authority-EC4899?style=flat-square" />

### Knowing when to stay silent

- For anything proactive the failure mode is **not being wrong, it is being noisy**. A suggestion nobody asked for costs **trust**, and then the feature gets switched off.
- So the interesting engineering is **suppression, not generation**. My judge harness already behaves that way: **act on high confidence, escalate on disagreement, stay quiet otherwise**.
- I **route work by which model is genuinely good at it**, because once something runs continuously, **what it costs to run is a product decision** rather than an afterthought.

<img src="https://img.shields.io/badge/suppression_first-EC4899?style=flat-square" /> <img src="https://img.shields.io/badge/confidence_gated-EC4899?style=flat-square" /> <img src="https://img.shields.io/badge/cost--aware_routing-EC4899?style=flat-square" />

### How I actually work

- I run **several plans in parallel** with Claude Code, custom skills and parallel subagents, and I have opinions about **which model gets which job**.
- I write **CI guard scripts that fail a build on policy violations**, not just on failing tests. One of mine fails the build if a credential identifier appears **anywhere outside the single module allowed to hold it**.
- The rule I work by: **the model advises, deterministic code decides.**

<img src="https://img.shields.io/badge/Claude_Code-10B981?style=flat-square" /> <img src="https://img.shields.io/badge/custom_skills-10B981?style=flat-square" /> <img src="https://img.shields.io/badge/parallel_subagents-10B981?style=flat-square" /> <img src="https://img.shields.io/badge/CI_guard_scripts-10B981?style=flat-square" />

---

## Shipped, with real people using it

<table>
<tr>
<td width="58%" valign="top">

### [Practers](https://practers.com/)

A **real-time AI interviewer**.

It holds a live voice conversation at **sub-second latency over WebSockets**, and **adapts its questions to the candidate's own resume** while the interview is happening.

Taken **0 to 1000+ users across 1000+ sessions**, with live health monitoring.

The hard part was never the interview. It was making the **score defensible**, which is where the judge harness came from.

<img src="https://img.shields.io/badge/1000%2B_users-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/1000%2B_sessions-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/sub--second_voice-00D9FF?style=for-the-badge" />

**Stack** Next.js 16, React 19, Fastify 5, Prisma, Supabase, PostgreSQL, MongoDB, Redis, BullMQ, Socket.IO, Judge0

**Infra** Google Cloud Run, Docker, Cloud Build, Cloudflare R2, Razorpay, Resend, MSG91

</td>
<td width="42%" valign="top">

### Contribution proof

<sub>Verified from the private <b>mockr-labs/practers</b> repository insights.</sub>

<img src="https://img.shields.io/badge/%232-contributor_by_commits-00D9FF?style=for-the-badge" /> <img src="https://img.shields.io/badge/210,311-lines_added,_most_on_the_team-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/105-commits_to_main-0F172A?style=for-the-badge" /> <img src="https://img.shields.io/badge/92,608-additions_in_peak_week-F59E0B?style=for-the-badge" />

<img src="images/image4.png" alt="Practers contributor leaderboard showing 105 commits and 210,311 additions" width="100%" />

</td>
</tr>
</table>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Pounce](https://github.com/piyushagarwal-55/teampounce)

**5 role-bounded LLM agents** on a tool-calling harness, transacting with **live merchants** over MCP and Shopify UCP.

Every pick grounded on a **Senso RAG context layer**.

The **mandate agent** arms a **capped, time-bound authorization once**, then buys on its own **on a price drop**.

I shipped an **LLM-as-judge harness scoring every tool call on real merchant data**, to catch **confident-wrong actions before checkout**.

<img src="https://img.shields.io/badge/5_role--bounded_agents-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/spends_real_money-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/judge_harness-7C3AED?style=flat-square" />

**Stack** OpenAI gpt-4o, MCP / Shopify UCP, Prava, Senso (RAG), Next.js, TypeScript, WebSockets

[Live](https://teampounce.vercel.app) · [Code](https://github.com/piyushagarwal-55/teampounce)

</td>
<td width="50%" valign="top">

### [LaunchOps](https://github.com/piyushagarwal-55/launchops-hackathon)

An agent that **provisions live cloud resources**, exposed as **13 tools over a self-hosted MCP server**.

Since the agent is spending and provisioning on its own, guardrails are **policy-as-code**.

A **scope, budget and approval engine** checks every action before it runs, with a **dry-run mode** and a **replayable audit trace**.

**No agent can ever exceed its granted authority.** Built with Claude Code, custom skills and parallel subagents, full stack in days.

<img src="https://img.shields.io/badge/13_tools-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/policy--as--code-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/built_in_days-10B981?style=flat-square" />

**Stack** Next.js, TypeScript, MCP (HTTP and Stdio), Socket.io, Node.js

[Live](https://launchops-hackathon.vercel.app) · [Code](https://github.com/piyushagarwal-55/launchops-hackathon)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [FlowForge](https://github.com/piyushagarwal-55/flowforge)

Compiles **natural-language specs into deployable REST APIs** through an LLM tool-calling pipeline.

A node-based workflow engine handles data models, auth, validation and business logic, with an execution runtime and one-click deploy.

Its **self-hosted MCP server exposes every generated endpoint as an agent-callable tool**.

<img src="https://img.shields.io/badge/spec_%E2%86%92_REST_API-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/self--hosted_MCP-00D9FF?style=flat-square" />

[Live](https://flowforge-i871.vercel.app) · [Demo](https://youtu.be/VcgeOuzxbdg) · [Code](https://github.com/piyushagarwal-55/flowforge)

</td>
<td width="50%" valign="top">

### [Sheet AI Pro](https://github.com/piyushagarwal-55/sheet-ai-pro)

Real-time collaborative spreadsheet using **Operational Transformation over WebSockets**.

Persistent multi-user state, reconnect-safe synchronisation.

**Under 100ms recalculation across 2,500+ cells.**

<img src="https://img.shields.io/badge/real--time-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/multi--user_OT-00D9FF?style=flat-square" /> <img src="https://img.shields.io/badge/%3C100ms-7C3AED?style=flat-square" />

[Code](https://github.com/piyushagarwal-55/sheet-ai-pro)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Prediction Market](https://pridiction-market-frontend-nfrj.vercel.app/)

A market where positions are priced by **what people actually believe**, not by what they say.

Building it teaches you one thing fast: **a probability only means something when someone has money on it.**

<img src="https://img.shields.io/badge/risk_%26_markets-F59E0B?style=flat-square" />
[Live](https://pridiction-market-frontend-nfrj.vercel.app/)

<!-- SWAPPR: send me these four things and I will write this card properly.
     1. one line on what it does
     2. Swift or React Native
     3. App Store link
     4. any user or download number
     They list "shipped something to the App Store yourself" as a brownie point,
     so this is worth getting right rather than guessing.
-->

</td>
<td width="50%" valign="top">

### [Sloop](https://swyclr.com) &nbsp; <img src="https://img.shields.io/badge/iOS_%2B_Android-000000?style=flat-square&logo=apple&logoColor=white" />

A **barter marketplace** for iPhone and Android, built at Swyft Ventures. Swipe to match items, **AI item valuation**, hybrid cash-plus-item deals, **auction rooms**, escrow, location discovery and in-app chat.

I wrote a **custom native Expo module** for Truecaller authentication, with its own Android sources, Gradle build and ProGuard rules.

I also wrote an **Expo config plugin** to fix a silent **Android 11+ package-visibility** bug: the payment SDK ships an empty manifest, so UPI apps were invisible to the checkout and **the sandbox VPA passed while production quietly failed**.

**Native** custom Expo module, config plugins, Hermes, New Architecture, Apple and Google Sign In, push
**Payments** Cashfree UPI, RevenueCat subscriptions, escrow flow
**Backend** Supabase, Express feed API, Jest and Testing Library

<img src="https://img.shields.io/badge/native_module-EF4444?style=flat-square" /> <img src="https://img.shields.io/badge/config_plugin-EF4444?style=flat-square" /> <img src="https://img.shields.io/badge/payments_%2B_escrow-F59E0B?style=flat-square" />

[Site](https://swyclr.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ShopSage](https://github.com/piyushagarwal-55/hackathon-we-make-devs)

AI shopping assistant on **AWS Bedrock and Llama 3**.

Search, recommendations, personalisation, budget flows and generative UI.

[Live](https://hackathon-we-make-devs.vercel.app/) · [Demo](https://youtu.be/2icL9ZYp3SY)

</td>
<td width="50%" valign="top">

### [Nexus Flow](https://nexusflowbeta.vercel.app/)

Built on **SKALE Network**.

[Live](https://nexusflowbeta.vercel.app/) · [Demo](https://youtu.be/S1DNJXRR7LI)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [RepVote](https://repvote-v1.vercel.app/)

Reputation-weighted voting. [Live](https://repvote-v1.vercel.app/)

</td>
<td width="50%" valign="top">

### [LNMIIT Carpool](https://github.com/piyushagarwal-55/carpool-lnmiit-work)

A carpool app **used on my own campus**. [Code](https://github.com/piyushagarwal-55/carpool-lnmiit-work)

</td>
</tr>
</table>

---

## Experience

<table>
<tr>
<td width="50%" valign="top">

### Practers · Co-Founder and Founding Engineer
<sub>Apr 2026 to Present</sub>

Led architecture for an **AI-native interview and hiring platform** as a Turborepo monorepo.

Built **resume-aware AI mock interviews** with authenticated WebSockets, Groq voice and text sessions, Gemini and OpenAI integrations, stage orchestration and **rubric-scored reports**.

Built secure coding, contest and hiring modules on Judge0 with Redis and BullMQ queues, hidden tests, real-time verdicts, ATS analysis and OA proctoring.

Deployed on **Google Cloud Run** with Docker, Secret Manager, R2-style storage, Razorpay, Resend and MSG91.

</td>
<td width="50%" valign="top">

### Swyft Ventures · SDE 1 Intern
<sub>Jan 2026 to Jun 2026 · Gemini-focused startup · Remote</sub>

Designed and shipped a **real-time swipe-based matching engine** where mutual opt-ins **instantly create matches**.

Backed by **Supabase row-level security** and live **Expo push on React Native**.

Shipped **high-quality releases** with automated unit and integration tests in a **GitHub Actions CI/CD pipeline**, plus real-time monitoring and error tracking.

<img src="https://img.shields.io/badge/React_Native-10B981?style=flat-square" /> <img src="https://img.shields.io/badge/CI%2FCD-10B981?style=flat-square" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### A1 Selectors · Software Developer Intern
<sub>Aug 2025 to Dec 2025</sub>

Built scalable REST APIs for **automated resume parsing** using NLP-based extraction.

**Cut manual screening effort by 35 percent** across recruiter workflows.

Developed AI recruitment workflows for candidate matching, ranking, scheduling automation and recruiter decision support.

</td>
<td width="50%" valign="top">

### Teaching Assistant · LNMIIT

Mentored students across **two semesters**, communicating complex ideas and presenting solutions in labs.

**B.Tech Communication and Computer Engineering**
CGPA **7.52** · Aug 2024 to Aug 2028

</td>
</tr>
</table>

---

## Open source

<div align="center">

| Project | What I did | Why it counts |
|---|---|---|
| **[Zulip](https://github.com/zulip/zulip)** <sub>GSoC org</sub> | Onboarded into their **large-scale production Django codebase** and was assigned by a **core maintainer** to migrate message-editing banners to a modern shared component. Shipped with **passing unit tests** and a design proposal. | Code other engineers actually use, in a repo I did not control. **[PR #39811](https://github.com/zulip/zulip)** |
| **AOSSIE** <sub>GSoC org</sub> | Diagnosed and fixed a **governance-audit bug** in OrgExplorer that counted closed issues and PRs as open. | It was **inflating dashboard metrics by up to 12x**. **PR #123** |

</div>

---

## Competitive

<div align="center">

<img src="https://img.shields.io/badge/LeetCode-450%2B_solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /> <img src="https://img.shields.io/badge/Codeforces-1872_Knight-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" /> <img src="https://img.shields.io/badge/GeeksforGeeks-200%2B_solved-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" /> <img src="https://img.shields.io/badge/Top_1%25-Google_Big_Code_Hackathon_2026-4285F4?style=for-the-badge&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/Top_1%25-AWS_ML_Hackathon-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />

<sub><b>Google Big Code Hackathon 2026</b>: top 1% after <b>three national elimination rounds</b>.</sub>

</div>

---

## Stack

<div align="center">

**AI and agents** &nbsp;·&nbsp; MCP &nbsp;·&nbsp; eval harnesses &nbsp;·&nbsp; LLM-as-judge &nbsp;·&nbsp; multi-agent orchestration &nbsp;·&nbsp; RAG &nbsp;·&nbsp; prompt evaluation &nbsp;·&nbsp; tool-calling

<img src="https://skillicons.dev/icons?i=ts,js,python,java,cpp,c,nodejs,nextjs,react,tailwind,express,spring,postgres,mongodb,redis,supabase,prisma,docker,gcp,aws,git,githubactions,vercel" alt="Stack" />

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
